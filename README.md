# 🐾 CS 340 Project Two: Grazioso Salvare Dashboard

## 📁 Overview

This repository contains the final submission for CS 340: Client/Server Development. The project is built for the fictional organization Grazioso Salvare and focuses on developing an interactive dashboard application using Python, Dash, and MongoDB.

The project is backed by a custom CRUD Python module built in Project One, which handles communication with a MongoDB database. The dashboard visualizes shelter data, filtered by rescue type, breed, and geolocation.

---

## 🔧 Technologies Used

- Python
- Dash (Plotly)
- MongoDB
- Jupyter Notebook
- PyMongo

---

## 📂 Included Files

| File                         | Description                                      |
|------------------------------|--------------------------------------------------|
| `ProjectTwoDashboard.ipynb` | The completed dashboard application notebook     |
| `animal_shelter.py`         | Reusable Python CRUD module from Project One     |
| `README_ProjectTwo.docx`    | Screenshots and project explanation (as required)|
| `README.md`                 | This markdown file with reflection responses     |

---

## 📓 Journal Reflection

### 🧩 Writing Maintainable, Readable, and Adaptable Code

In this project, I designed the `animal_shelter.py` module to separate database operations from the dashboard logic. This made it easy to test, update, and reuse across projects. For instance, I didn’t have to rewrite connection logic or queries for Project Two — I just imported and reused my CRUD functions. This approach also helps reduce bugs and keep code organized.

### 🧠 Approaching Problems Like a Computer Scientist

I approached this assignment by first understanding the data schema, then building out modular query functions, and finally visualizing them with Dash. This was different from previous courses, where functionality was more isolated. Here, I had to think about how multiple pieces would work together: authentication, filtering logic, and user interface. I now see the value of sketching out flow diagrams or pseudocode before coding.

### 💼 The Role of Computer Scientists

Computer scientists help organizations solve real-world problems using technology. In this case, I built a tool that would help an animal rescue organization analyze trends, locations, and animal types more effectively. It saves time, enables data-driven decisions, and shows how dashboards can provide value with minimal setup.

---

## 🔗 Repository Link for Instructor

> [Insert your actual GitHub link here after pushing the repo]

Please ensure this repository is set to **Public** or that your instructor has been added as a **Collaborator**.

