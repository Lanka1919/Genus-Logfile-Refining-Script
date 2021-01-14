# Genus-Logfile-Refining-Script
This TCL script will refine the Cadence Genus generated logfile by seperating all generated errors (major) in each stage of each type. This is written using very basic format without including any data structures. 
Detailed explanation of each code line is mentioned in the comments. 

Genus Logfile generates messages along with particular code. Those codes are used to identify and extract messages from the logfile. The complete report is displayed on the command window itself. 
In few days, few changes will be made to this script including two options - whether to display everything on command prompt or dump all messages in a file. A command file will also be created for direct call of the command withoout using TCLSH command.

Since this is written without using any arrays, I will try to implement the whole script in data structures which decreases the code complexicity and improves efficiency. (I have started learning TCL very recently, so learning concepts and implementing here is my goal)


