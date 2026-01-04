#intermediate level
def student_info_analyzer():
	name = input("Enter your full name: ")
	roll_Number=int(input("Enter roll number: "))
	branch =input("Enter Branch: ")
	subject=input("Enter your favorite subjects (comma-separated):")
	fav_sub=subject.split(",")
	sub1_marks =int(input(f"Enter marks of {fav_sub[0]}"))
	sub2_marks =int(input(f"Enter marks of {fav_sub[1]}"))
	sub3_marks =int(input(f"Enter marks of {fav_sub[2]}"))
	skills=input("Enter technical skills (comma-separated): ")
	tuple=(roll_Number,branch)
	sub_marks={fav_sub[0]:sub1_marks,fav_sub[1]:sub2_marks,fav_sub[2]:sub3_marks,}
	h=skills.split(",")
	tech_skills=set()
	for i in range(0,3):
		tech_skills.add(h[i])
	#favorite subjects in alphabetical order.
	fav_sub.sort()
	#Calculating Total and average marks
	total_marks=(sub1_marks+sub2_marks+sub3_marks)
	avg_marks=total_marks/3
	#subject with the highest marks.
	list_marks=[sub1_marks,sub2_marks,sub3_marks]
	list_marks.sort()
	for key,value in sub_marks.items():
		if value==list_marks[-1]:
			sub_highest=key
	print(f"Full Name: {name}")
	print(f"Roll Number & Branch: {tuple}")
	print(f"Favorite Subjects (Alphabetical): {fav_sub}")
	print(f"Subject-wise Marks: {sub_marks}")
	print(f"Total Marks: {total_marks}")
	print(f"Average Marks: {avg_marks}")
	print(f"Highest Scoring Subject:{sub_highest} ")
	print(f"Technical Skills: {tech_skills}")
student_info_analyzer()
