
# 🏋️ Gym Management System

A **Python Tkinter-based desktop application** designed to help gym owners and staff **easily manage member records**. This lightweight and user-friendly tool allows you to store, update, and manage gym membership details in a simple graphical interface—no technical background required.

---

## 📦 Features

✅ **Add New Members**  
Easily input and register members using unique IDs, names, and age fields.

✅ **Update Member Details**  
Modify existing member data whenever needed.

✅ **Delete Members**  
Remove inactive or old member records.

✅ **View All Members**  
Display a list of all saved members for quick reference.

✅ **Data Persistence via JSON**  
Member data is saved locally using JSON format, allowing data to persist between sessions without a database.

✅ **Simple and Responsive UI**  
The app uses Tkinter to provide an intuitive layout with labels, entry fields, and buttons.

---

## 🎥 Preview

> _Add screenshots or GIFs of your GUI here to show how the system looks in action._

---

## 📁 Project Structure

```
gym_management_system/
│
├── gym_managemt_system.py      # Main application logic with GUI
├── README.md                   # This file
└── members.json                # Auto-generated file to store gym member data
```

---

## 🧰 Tech Stack

| Technology | Purpose                     |
|------------|-----------------------------|
| Python     | Core programming language   |
| Tkinter    | GUI library for the frontend |
| JSON       | Local storage of member data |

---

## 💻 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/gym_management_system.git
cd gym_management_system
```

### 2. Install Python
Ensure you have **Python 3.6+** installed. You can check using:
```bash
python --version
```

### 3. Run the App
```bash
python gym_managemt_system.py
```

> **Note:** All dependencies (Tkinter, JSON) are included in Python by default—no need to install anything extra!

---

## 🧑‍🏫 How to Use

### ✅ Add Member
1. Launch the app.
2. Fill in the **Member ID**, **Name**, and **Age**.
3. Click **"Add Member"** to save the details.

### 📝 Update Member
1. Enter the ID of the member you want to edit.
2. Change the name or age.
3. Click **"Update Member"**.

### ❌ Delete Member
1. Enter the **Member ID**.
2. Click **"Delete Member"**.

### 📋 View Members
- The interface may show a list or confirmation message.
- You can also open the `members.json` file to view raw data.

---

## 📦 Data Format (`members.json`)

```json
{
  "101": {
    "name": "John Doe",
    "age": 25
  },
  "102": {
    "name": "Jane Smith",
    "age": 30
  }
}
```

Each member is stored with their unique ID as the key.

---

## 🌱 Future Enhancements (Ideas)

- Add member search functionality
- View members in a scrollable table inside the GUI
- Export member list to CSV
- Add gender, email, and membership type fields
- Use SQLite or Firebase for more advanced storage
- Integrate biometric or QR code login for members

---

## 🤝 Contribution Guidelines

If you'd like to contribute:

1. Fork the repo
2. Create a new branch (`git checkout -b feature-xyz`)
3. Commit your changes (`git commit -am 'Add feature'`)
4. Push to the branch (`git push origin feature-xyz`)
5. Open a pull request

---

## 📝 License

This project is licensed under the **MIT License** – feel free to use and modify it.
