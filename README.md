# 🔐 Password Generator

A simple **Python password generator** that creates customizable random passwords based on the user's requirements.

The program allows users to choose a minimum password length and optionally include **numbers** and **special characters**.

> ⚠️ **Learning Project:** This project uses Python's `random` module to demonstrate password-generation logic. For passwords that require strong security, use Python's `secrets` module instead.

---

## ✨ Features

* 🔑 Generates random passwords automatically
* 🔠 Includes uppercase and lowercase letters
* 🔢 Optional numbers
* 🔣 Optional special characters
* 📏 User-defined minimum password length
* 💻 Simple command-line interface
* 📦 Uses only Python's built-in libraries
* 🚫 No external dependencies required

---

## 🛠️ Technologies Used

* **Python 3**
* `random` — randomly selects characters
* `string` — provides predefined character sets

No external packages are required.

---

## 📁 Project Structure

```text
Password-Generator/
│
├── main.py
└── README.md
```

---

## ⚙️ How It Works

The program builds a character pool using Python's `string` module.

### Character sets

```python
string.ascii_letters
```

Contains uppercase and lowercase letters:

```text
abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ
```

```python
string.digits
```

Contains numbers:

```text
0123456789
```

```python
string.punctuation
```

Contains special characters such as:

```text
! @ # $ % ^ & * ...
```

### Password generation process

The program:

1. Asks the user for the minimum password length.
2. Asks whether numbers should be included.
3. Asks whether special characters should be included.
4. Builds the appropriate character set.
5. Randomly selects characters.
6. Ensures the requested character requirements are satisfied.
7. Displays the generated password.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/shweshd/Password-Generator.git
```

### 2. Navigate to the project directory

```bash
cd Password-Generator
```

### 3. Run the program

```bash
python main.py
```

---

## 💻 Example

```text
Enter the minimum length: 12
Do you want to have numbers (Y/N)? y
Do you want to have special characters (Y/N)? y

The generated password is: aK7@pL2#xQ9!
```

The generated password will be different each time because the program randomly selects characters.

---

## 📚 Concepts Practiced

This project helped me practice fundamental Python concepts, including:

* Functions
* Function parameters
* Conditional statements
* `while` loops
* Boolean variables
* User input
* String manipulation
* Python modules
* Random character generation
* Character sets
* Basic program logic
* Input validation

---

## 🔮 Future Improvements

Possible improvements for future versions:

* [ ] Add a maximum password length
* [ ] Add a graphical user interface (GUI)
* [ ] Add a password strength indicator
* [ ] Allow users to exclude specific characters
* [ ] Generate multiple passwords at once
* [ ] Add a copy-to-clipboard option
* [ ] Replace `random` with Python's `secrets` module
* [ ] Add customizable character sets
* [ ] Add command-line arguments for faster generation

---

## 🔐 Security Note

This project is primarily intended for **learning Python and understanding password-generation logic**.

The current implementation uses Python's `random` module, which is **not designed for security-sensitive applications**.

For real-world password generation, Python's `secrets` module should be used because it is specifically designed for generating cryptographically strong random values.

For example:

```python
import secrets
```

This project may be upgraded to use `secrets` in a future version.

---

## 📄 License

This project is open source and available under the **MIT License**.

---

## 👨‍💻 Author

**Shwesh Dubey**

* GitHub: [@shweshd](https://github.com/shweshd)
* Portfolio: [shweshd.github.io/Portfolio](https://shweshd.github.io/Portfolio/)
