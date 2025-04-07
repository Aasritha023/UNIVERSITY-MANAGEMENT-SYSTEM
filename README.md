# UNIVERSITY-MANAGEMENT-SYSTEM
🎓 College Management System – Python OOP Project
This is a simple console-based College Management System developed in Python using Object-Oriented Programming (OOP). It allows users to manage colleges, students, and teachers with features like adding, searching, and displaying data.

📌 Features
✅ Create and manage multiple colleges

👨‍🎓 Add & display students (with roll number, name, branch)

👩‍🏫 Add & display teachers (with roll number, name, subject)

🔍 Search for a student or teacher by roll number

🧠 Structured with OOP: Person, Student, Teacher, and College classes

📎 Menu-driven interface using basic Python input/output

🧰 Technologies Used
🐍 Python 3

💻 Command-line Interface (CLI)

🧱 Object-Oriented Programming (OOP)

🧠 OOP Structure
scss
Copy
Edit
Person
├── Student (inherits Person)
├── Teacher (inherits Person)
College
Person contains shared attributes like rollno and name.

Student and Teacher add their specific attributes (branch, subject).

College class holds lists of students and teachers and provides methods to manage them.

📸 Sample Output
bash
Copy
Edit
Choose the Required option: 
1. Create College.
2. Add Student.
3. Add Teacher.
4. Display Students.
5. Display Teachers.
6. Search Student by Roll Number.
7. Search Teacher by Roll Number.
8. Exit.
Enter your Option: 1
Enter College Name: XYZ College

College Added Successfully
🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/college-management-system.git
cd college-management-system
Run the script:

bash
Copy
Edit
python college_system.py
📈 Future Improvements
💾 Add file/database storage for data persistence

🖼️ GUI interface using Tkinter or web frontend (Flask/Django)

🔐 Admin login system

📊 Export reports as CSV

🤝 Contributing
Pull requests are welcome! If you'd like to suggest improvements or add features, feel free to fork this repo and submit a PR.

📬 Contact
Feel free to connect with me on LinkedIn
Or email me at: your.email@example.com

⭐️ Show Some Love
If you found this project helpful, please consider giving it a ⭐️ on GitHub!

