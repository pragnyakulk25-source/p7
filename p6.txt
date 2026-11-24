def employee(name, empid, dept, salary):
    return f"Name: {name}\nID: {empid}\nDepartment: {dept}\nSalary: {salary}"

if __name__ == "__main__":
    name = input("Enter employee name: ")
    empid = input("Enter employee ID: ")
    dept = input("Enter department: ")
    salary = input("Enter salary: ")

    result = employee(name, empid, dept, salary)
    print(result)

