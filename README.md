# 🎓 Student Score Finder

A simple Python GUI application built using **Tkinter** that allows users to calculate a student's total marks, percentage, and result status based on marks entered for five subjects.

## 📌 Features

- User-friendly graphical interface
- Enter student's name and marks for five subjects
- Calculates:
  - Total Marks
  - Percentage
  - Result Status
- Displays different result colors:
  - 🟢 Green – PASS (Studious Student) for percentage above 80%
  - 🔵 Blue – PASS for percentage above 33%
  - 🔴 Red – FAIL for percentage below or equal to 33%
- Input validation for empty fields and invalid marks

## 🛠️ Technologies Used

- Python 3
- Tkinter (Python GUI Library)

## 📂 Subjects Included

- Mathematics
- Chemistry
- Physics
- Hindi
- English

## 📊 Result Criteria

| Percentage | Status |
|------------|--------|
| Above 80% | PASS (Studious Student) |
| Above 33% | PASS |
| 33% or Below | FAIL |

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/student-score-finder.git
```

2. Navigate to the project folder

```bash
cd student-score-finder
```

3. Run the Python file

```bash
python student_score_finder.py
```

## 📸 Output

The application displays:

- Student Name
- Total Marks (Out of 500)
- Percentage
- Final Result Status

## 📁 Project Structure

```
Student-Score-Finder/
│
├── student_score_finder.py
├── README.md
└── screenshots/ (Optional)
```

## 💡 Future Improvements

- Add Grade Calculation (A+, A, B, C, etc.)
- Export Result as PDF
- Save Student Records
- Display Subject-wise Analysis
- Add Database Integration

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📄 License

This project is created for learning and educational purposes.

---

**Made with ❤️ using Python and Tkinter**
