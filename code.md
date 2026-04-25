students = []

while True:
    print("\n1. Add Student")
    print("2. View Students")
    print("3. Delete Student")
    print("4. Exit")

    ch = input("Enter choice: ")

    if ch == "1":
        name = input("Enter name: ")
        rollno = input("Enter Roll no: ")

        marks1 = int(input("Enter marks1: "))
        marks2 = int(input("Enter marks2: "))
        marks3 = int(input("Enter marks3: "))
        marks4 = int(input("Enter marks4: "))
        marks5 = int(input("Enter marks5: "))
        marks6 = int(input("Enter marks6: "))

        total = marks1 + marks2 + marks3 + marks4 + marks5 + marks6
        percentage = total / 6   # correct formula

        if percentage > 80:
            grade = "A"
        elif percentage > 50:
            grade = "B"
        else:
            grade = "C"

        students.append({
            "name": name,
            "roll": rollno,
            "total": total,
            "percentage": percentage,
            "grade": grade
        })

        print("Student added!")

    elif ch == "2":
        for s in students:
            print(s)

    elif ch == "3":
        r = input("Enter roll no to delete: ")
        for s in students:
            if s["roll"] == r:
                students.remove(s)
                print("Deleted")
                break

    elif ch == "4":
        print("Exit")
        break

    else:
        print("Invalid choice")
