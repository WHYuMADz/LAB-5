 LAB-5

Terminal Log Files

For Task 1, what i did at the beginning is to decide which CSV file to use and then searching the terminal commands for it. First, what I did during the project is to download the zip.file using curl and download it into a zip archive containing the CSV file to a Lab5 directory that I created already.Then, in order to unzip the CSV file, I use the command "unzip" to zip the file. Then I used the head command to read the first 10 lines of a CSV file that I selected. Then I read the total number of lines in the CSV. Then I selected the 3rd column in the CSV which contained movie ratings. I used cat to select the column and output it to a text file. Then I use the sort command to reverse sort the text file numerically line-by-line. Finally, I used head again to show what the selected and sorted column looks like in the text file.

For Task 2, I created a Shell scrip version of the task 1. I use Shell because it is a very helpful way to save time for repeated files that you have and you can throw a bunch of 
commands in a script.

For Task 3, The objective was to gain more familiarity with terminal and use it for more purposes. I decided to use ffmpeg to convert an MP4 video into an animated GIF. First, I installed ffmpeg. Then I input "ffmpeg -i giphy.mp4 -f gif giphy.gif" into terminal to output the video as a GIF named giphy.gif. This task seemed easier than expected.

