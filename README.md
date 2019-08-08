# Threading
First practice with concurrent threading

# Description
Runs multiple threads at the same time but is binded by a few rules. Each thread represents one student trying to visit the advisor during office hours. It cant collide with a student already in the office and have to keep track of student and length of visit before allowing someone else in. After ten straight visits, hold all threads from entering for lunch break and then continue on same loop until no threads left to process.
