#Q4
a = int(input("Enter Number:"))
ans = ["Even","odd"][a%2]
print(ans)
#Q5
vote=int(input("Enter an age :"))
result=["Not eligible","Eligible"][vote>=18]
print(result)
#Q11
age = int(input("Enter age: "))
cgpa = float(input("Enter CGPA: "))
arrears = int(input("Enter arrears: "))
attendance = float(input("Enter attendance: "))
skill = input("Enter required skill: ")

skills = ["Python", "Java", "C", "HTML", "CSS"]

eligible = age >= 18 and cgpa >= 7.0 and arrears == 0 and attendance >= 75 and skill in skills

print("Eligible:", eligible)
#Q12
balance = float(input("Enter account balance: "))
amount = float(input("Enter withdrawal amount: "))
card_status = input("Enter card status: ")
pin_status = input("Enter PIN status: ")

allowed = (card_status == "active" and
           pin_status == "correct" and
           amount > 0 and
           amount <= balance)

print("Withdrawal Allowed:", allowed)
#Q13
num = int(input("Enter an integer: "))

both = num % 3 == 0 and num % 5 == 0
only_3 = num % 3 == 0 and num % 5 != 0
only_5 = num % 5 == 0 and num % 3 != 0
neither = num % 3 != 0 and num % 5 != 0

print("Divisible by both 3 and 5:", both)
print("Divisible by 3 but not 5:", only_3)
print("Divisible by 5 but not 3:", only_5)
print("Divisible by neither:", neither)
#Q14
basic = float(input("Enter basic salary: "))
bonus = float(input("Enter bonus: "))
deductions = float(input("Enter deductions: "))
tax_percentage = float(input("Enter tax percentage: "))

gross = basic + bonus
tax = gross * (tax_percentage / 100)
final_salary = gross - tax - deductions

print("Gross Salary:", gross)
print("Tax Amount:", tax)
print("Final Salary:", final_salary)
#Q15
username = input("Enter username: ")
password = input("Enter password: ")
status = input("Enter account status: ")
role = input("Enter role: ")

registered_username = "admin"
registered_password = "1234"

login = (username == registered_username and
         password == registered_password and
         status == "active" and
         role in ["admin", "manager"])

print("Login Successful:", login)

#Q17
total_seconds = int(input("Enter total seconds: "))

hours = total_seconds // 3600
minutes = (total_seconds % 3600) // 60
seconds = total_seconds % 60

print("Hours:", hours)
print("Minutes:", minutes)
print("Seconds:", seconds)

#Q18
A = input("Enter A (True/False): ") == "True"
B = input("Enter B (True/False): ") == "True"
C = input("Enter C (True/False): ") == "True"
D = input("Enter D (True/False): ") == "True"
E = input("Enter E (True/False): ") == "True"

result = (A and B) or (C and not D and not E)

print("Final Result:", result)

#Q19
list1 = [10, 20, 30]
list2 = [10, 20, 30]
list3 = list1

print("list1 == list2:", list1 == list2)
print("list1 is list2:", list1 is list2)
print("list1 is list3:", list1 is list3)
print("list1 is not list2:", list1 is not list2)
print("list1 is not list3:", list1 is not list3)

#Q20
name = input("Enter student name: ")
age = int(input("Enter age: "))
cgpa = float(input("Enter CGPA: "))
attendance = float(input("Enter attendance: "))
arrears = int(input("Enter number of arrears: "))
language = input("Enter programming language: ")
coding = int(input("Enter coding score: "))
communication = int(input("Enter communication score: "))

approved_skills = ["Python", "Java", "C", "C++"]

total_score = coding + communication
average_score = total_score / 2

skill_valid = language in approved_skills
eligible = (age >= 18 and
            cgpa >= 7.0 and
            attendance >= 75 and
            arrears == 0 and
            skill_valid and
            coding >= 60 and
            communication >= 50)
status = "Not Eligible"

if eligible:
    status = "Eligible for Placement Drive"

    if coding >= 85:
        category = "High Technical Potential"
    elif coding >= 60 and coding <= 84:
        category = "Eligible"
    else:
        category = "Needs Improvement"
else:
    category = "Needs Improvement"

print("\n--- Placement Decision ---")
print("Student Name:", name)
print("Total Score:", total_score)
print("Average Score:", average_score)
print("Skill Approved:", skill_valid)
print("Placement Status:", status)
print("Category:", category)

        
#Q21
price = int(input())
quantity = int(input())
discount = int(input())
total_cost = price * quantity
final_amount = total_cost - discount
print(final_amount)
