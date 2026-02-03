# Apnacollage-demo
This is my first git repository 
<br>
author- Anuj Kumar
def calculate_result():
    name = input("Enter student name: ")
    m1 = int(input("Enter marks of Subject 1: "))
    m2 = int(input("Enter marks of Subject 2: "))
    m3 = int(input("Enter marks of Subject 3: "))

    total = m1 + m2 + m3
    percentage = total / 3

    print("\n--- Student Result ---")
    print("Name:", name)
    print("Total Marks:", total)
    print("Percentage:", percentage)

    if percentage >= 60:
        print("Grade: First Division")
    elif percentage >= 45:
        print("Grade: Second Division")
    else:
        print("Grade: Fail")

calculate_result()