# Sir-Noman-ass...
Salary reporting program:


def add_employee(self, emp):
    self.employees.append(emp)

def generate_salary_report(self):
    print("Salary Report:")
    print("Employee ID\tName\t\tSalary")
    print("----------------------------------")
    for emp in self.employees:
        print(f"{emp.emp_id}\t\t{emp.name}\t\t{emp.salary}")
    print("----------------------------------")
