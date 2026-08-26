# 🔐 Password Generator

A simple Python-based password generator that creates random and secure passwords based on the user's requirements.

The user can choose:
- Minimum password length
- Whether to include numbers
- Whether to include special characters

## 🚀 Features

- Generates random passwords automatically
- Supports uppercase and lowercase letters
- Optional numbers
- Optional special characters
- User-defined minimum password length
- Simple command-line interface
- Built using Python's built-in libraries

## 🛠️ Technologies Used

- **Python 3**
- `random` module
- `string` module

No external packages are required.

## 📁 Project Structure

```text
Password-Generator/
│
├── password_generator.py
└── README.md
```

## ⚙️ How It Works

The program uses Python's `string` module to create character sets:

* `string.ascii_letters` → uppercase and lowercase letters
* `string.digits` → numbers from 0–9
* `string.punctuation` → special characters

The program then randomly selects characters until the generated password:

1. Reaches the requested minimum length.
2. Contains a number if the user requested numbers.
3. Contains a special character if the user requested special characters.

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/shweshd/Password-Generator.git
```

### 2. Navigate to the project

```bash
cd Password-Generator
```

### 3. Run the program

```bash
python main.py
```

## 💻 Example

```text
Enter the minimum length: 12
Do you want to have numbers (Y/N)? y
Do you want to have special characters (Y/N)? y

The generated password is:  aK7@pL2#xQ9!
```

The generated password will be different each time because the program randomly selects characters.

## 📚 Concepts Practiced

This project helped practice several fundamental Python concepts:

* Functions
* Function parameters
* Conditional statements
* `while` loops
* Boolean variables
* User input
* String manipulation
* Python modules
* Random character generation
* Basic program logic

## 🔮 Future Improvements

Possible improvements for future versions:

* Add a maximum password length
* Add a graphical user interface (GUI)
* Add password strength indicators
* Allow users to exclude specific characters
* Generate multiple passwords at once
* Copy the generated password directly to the clipboard
* Use Python's `secrets` module for stronger password generation

## ⚠️ Security Note

This project is intended primarily for learning Python programming.

For passwords that require strong security, Python's `secrets` module is preferable to the `random` module because `secrets` is designed for security-sensitive random values.

## 📄 License

This project is open source and available under the MIT License.
