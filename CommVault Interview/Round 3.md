
So round 3 was a Long Coding Challenge. I had no clue what they were going to ask in this round. I tried searching online and after reading all the stuff all i could think of was I cant do it.
All the questions that i found looked like they will ask us to code a file system or something related to Linux.
But in reality it was a complete different experience. I really liked this round. This round sure did test my Object oriented programming skills and logical ability to store data into a self designed Data Structure.

This round started at 8:40am . We were briefly introduced about what we were going to do. There were 26 students that were selected for this round , we were divided into groups of three but the task was to be performed independently.

The problem was:-
### We have to design a mp3 player. Sounds complicated right? But no we don't have to make any user interface or read any files nothing like that. We had to design a program that can store different songs details. A main player list, multiple playlist and we had to perform different operations on them.

Okay this might look complicated.
Here is what i did.

I made a class Song that contained attributes like songName, lengthOfSong, copyright, singer. Made a constructor to initialise values when an object is created.

Made another class for Playlist. That is gonna have a hashmap of SongName as key and Song as its Value.

Made another class called mp3Player for the whole logical operation.

And them there was this Main class that was provided to us as a template so that we can design the missing functions.
