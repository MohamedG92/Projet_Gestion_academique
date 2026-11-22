<div align="center">

# 🎓 Projet Gestion Académique

**Academic management system in C++ connected to a MariaDB database, with a console version and a Qt desktop version**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

</div>

## ✨ Features

Two roles, each with its own login:

**👨‍🏫 Teacher**
- Add, edit, delete and search students
- Manage modules
- Enter grades and view class statistics

**🎓 Student**
- View their grades per module
- See their overall average
- See the **minimum exam grade** they need to pass

Grades are weighted: **TP 20%** · **CC 30%** · **Exam 50%**.

## 📦 What's inside

| Archive | Content |
|---|---|
| `PROJET_GESTION_ETUDIANTS.zip` | Console version (C++, Dev-C++ project), commented source |
| `PROJET_GESTION_GRAPHIQUE.zip` | Desktop version with a **Qt** interface (`.ui` forms), commented source |

The code is object-oriented: `Personne`, `Etudiant`, `Enseignant`, `Module`, `Controle`, `Note` and a `Database` class
that wraps the MariaDB C connector.

## 🚀 Run it

1. Install **XAMPP** and start **MySQL/MariaDB**.
2. Unzip the version you want.
3. Console version: open the `.dev` project in Dev-C++ and build (`libmariadb.dll` is included).
   Qt version: open the project in **Qt Creator** and build.

---

<div align="center">Made by <a href="https://github.com/MohamedG92">Mohamed Iraqi Houssaini</a></div>
