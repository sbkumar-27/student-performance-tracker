# Student Performance Tracker 🎓

A Java-based project designed to manage student academic details and gradually develop into a student performance tracking system.

## 📌 About the Project

The Student Performance Tracker aims to provide a simple way to organize student information and, in future versions, track academic performance.

The project is being developed incrementally, starting with basic Java classes and expanding as new features are implemented.

## 🛠️ Technologies Used

- **Java** — Core programming language
- **Object-Oriented Programming (OOP)** — Structuring student data using classes and objects

## 🚀 Current Progress

- [x] Created the `Student` class.
- [x] Added fields for roll number, name, and semester.
- [x] Implemented a constructor to initialize student details.
- [ ] Add student records.
- [ ] Implement academic performance tracking.
- [ ] Develop GPA and CGPA calculation.
- [ ] Add data storage.
- [ ] Build a user interface.

## 💻 Current Implementation

```java
class Student {
    int rno, sem;
    String Name;

    Student(int rno, String Name, int sem) {
        this.rno = rno;
        this.Name = Name;
        this.sem = sem;
    }
}
```

The `Student` class currently stores three attributes:

| Attribute | Description |
|---|---|
| `rno` | Student's roll number |
| `Name` | Student's name |
| `sem` | Current semester |

The constructor initializes these attributes when a `Student` object is created.

## 🎯 Future Goals

- Manage multiple student records.
- Store subject details and marks.
- Calculate semester GPA and cumulative CGPA.
- Track academic progress across semesters.
- Generate useful performance summaries.

## 📈 Development Approach

This project is being developed step by step, with an emphasis on learning Java, applying object-oriented programming concepts, and writing clean, maintainable code.

More features will be added as development progresses.

---

**Status:** Initial development  
**Language:** Java"# student-performance-tracker" 
