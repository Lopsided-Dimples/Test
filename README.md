# Test - Old Project

last_semester_gradebook = [["politics", 80], ["latin", 96], ["dance", 97], ["architecture", 65]]

# Your code below: 

subjects = ["physics", "calculus", "poetry", "history"]
grades = [98, 97, 85, 88]

gradebook = [["physics", 98], ["calculus", 97], ["poetry", 85], ["history", 88]]
#print(gradebook)

new_grades = ["computer science", 100]
gradebook.append(new_grades)
#print(gradebook)

gradebook.append(["visual arts", 93])
#print(gradebook)

gradebook[-1][1] = 97
#print(gradebook)

gradebook[2].remove(85)
#print(gradebook)

gradebook[2].append("Pass")
#print(gradebook)

#One Big Gradebook

full_gradebook = last_semester_gradebook + gradebook
print(full_gradebook)


