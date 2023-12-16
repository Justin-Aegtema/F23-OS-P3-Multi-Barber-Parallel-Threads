Multi-threaded process

INPUT:
csmc #students #tutors #chairs #help_needed

Students study (sleep) and seek tutoring. 
Coordinator selects students to receive tutoring. 
Tutors and students then meet together and the help_received is increased.
Process ends when the students receive all the help they need (#help_needed for all students).

Students are arranged in priority queue based on arrival time and number of times help previously received.



Program is most interesting with high students and high help needed, but low chairs and mid or low tutors. So try big input! 
For example:
csmc 2000 20 2 40

2000 students*40 help_needed = 80000 tutoring sessions!

Try a low input to follow what happens more closely.
For example:
csmc 2 2 2 2