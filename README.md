# 🏥 Hospital Appointment & Triage Management System (Java)

A fully functional **Command-Line Hospital Management System** developed using **Core Java & Data Structures**.  
This system efficiently manages **routine appointments, emergency triage, doctor scheduling, patient records, and undo functionality** using optimized data structures.

---

## 🚀 Features

### 👤 Patient Management
- Register new patients
- Update patient information
- Delete patients
- Track number of visits per patient
- Top-K most frequent patients report

### 👨‍⚕️ Doctor & Slot Management
- Add doctors with specialization
- Add appointment slots (Linked List)
- Cancel slots
- Automatically assigns the nearest free slot

### 📅 Routine Appointment System
- Book routine appointments
- Walk-in routine handling
- Per-doctor circular token queue

### 🚨 Emergency Triage (Priority-Based)
- Emergency patients inserted using **Min Heap**
- Lower severity = Higher priority
- Emergency patients are always served first

### 🔁 Undo System (Stack)
Undo supported for:
- Patient registration
- Slot addition
- Routine & walk-in booking
- Emergency insertion
- Serving routine patients
- Serving emergency patients

### 📊 Reports
- Per-doctor report
- Overall hospital summary
- Top-K patients by visit count
- Active token listing
- Time & Space complexity report

---

## 🧩 Data Structures Used

| Feature | Data Structure |
|--------|----------------|
| Doctor schedule | Singly Linked List |
| Routine queue | Circular Queue |
| Emergency triage | Min Heap |
| Patient records | Hash Table with Chaining |
| Undo system | Stack |
| Token lookup | HashMap |

---

## 🛠️ How to Run

### ✅ Requirements
- Java JDK 8 or later
- Any Java IDE or Command Line

### ▶️ Compile & Run

```bash
javac Main.java
java Main
```

---

## 📋 Menu Options

```
1. Register Patient
2. Update Patient
3. Delete Patient
4. Add Doctor
5. Add Slot
6. Cancel Slot
7. Book Routine Appointment
8. Emergency In
9. Serve Next Patient
10. Undo Last Action
11. Reports
12. List Active Tokens
13. Exit
```

---

## 🧪 Preloaded Data

- Doctors:
  - Dr. Arjun (Cardio)
  - Dr. Leela (Ortho)

- Slots:
  - Dr. Arjun → 10:00–11:00
  - Dr. Leela → 09:00–09:30

---

## ⚙️ Time & Space Complexity

| Operation | Time Complexity |
|------------|------------------|
| Queue Enqueue / Dequeue | O(1) |
| Heap Insert / Extract | O(log n) |
| Hash Insert / Search | O(1) average |
| Linked List Slot Search | O(k) |
| Undo Stack Operations | O(1) |
| Top-K Frequent Patients | O(n log n) |

---

## 📂 Project Structure

```
Main.java
├── Patient
├── Token
├── SlotNode
├── CircularQueue
├── EmergencyHeap
├── HashTablePatients
├── Doctor
├── UndoAction
└── HospitalSystem
```

---

## ✅ Learning Outcomes

- Practical implementation of **DSA concepts**
- Priority handling using **Heaps**
- Circular Queue implementation
- Undo system using **Stacks**
- Hash Tables with chaining
- Real-world system simulation using Java

---

## ✨ Future Improvements (Optional)

- GUI using Java Swing or JavaFX
- Database integration (MySQL)
- File-based data persistence
- Doctor-wise emergency auto-assignment
- Login system for staff

---

## 👩‍💻 Author

**Krishika Sinha**  
B.Tech Computer Science Engineering  
DSA | Java | System Design  

---

✅ This project is ideal for:
- College Mini Project
- DSA Practical File
- Resume Project
- Viva & Interviews
