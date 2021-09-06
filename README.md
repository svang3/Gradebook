# Codecademy -- Gradebook

# This project is to utilize lists method where student like me is trying to organize the subjects and grades using Python.

last_semester_gradebook = [["politics", 80], ["latin", 96], ["dance", 97], ["architecture", 65]]

# Create a subject list to fill in the classes I am taking: 
subjects = ["physics", "calculus", "poetry", "history"]

# Create a grade list to fill with my scores from the class:
grades = [98, 97, 85, 88]

# Create a two-dimensional list to combine subjects and grades, and name it gradebook:
gradebook = [["physics", 98], ["calculus", 97], ["poetry", 85], ["history", 88]]

# Print gradebook:
print(gradebook)

# Add a new subject and grade to the gradebook variable:
gradebook.append(["computer science", 100])

# Add in grade for visual arts to gradebook:
gradebook.append(["visual arts", 93])

# Update the rewarding 5 points to visual art class and print to double check if update correctly:
gradebook[5][1] += 5
print(gradebook)

# Remove numerical grade value to Pass/Fail for poetry class:
gradebook[2].remove(85)
print(gradebook)

# Add 'Pass' value to the list where poetry class is located:
gradebook[2].append("Pass")
print(gradebook)

# Combine gradebook list and last_semester_gradebook list to create a new variable, full_gradebook, for my completed list:
full_gradebook = last_semester_gradebook + gradebook
print(full_gradebook)
