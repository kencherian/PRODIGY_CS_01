🛡️ Caesar Cipher - GUI Version:
A simple GUI-based Python application to encrypt or decrypt text using the Caesar Cipher algorithm. Built using tkinter.

📂 Features:
Encrypt or decrypt any message using Caesar Cipher

User-friendly GUI (no terminal required)

Supports both uppercase and lowercase letters

Keeps numbers, punctuation, and spaces unchanged

🖥️ Requirements:
->Python 3.x

No external libraries needed (uses built-in tkinter)

🚀 How to Run
Clone or Download the Code

bash:
git clone https://github.com/yourusername/caesar-cipher-gui.git
cd caesar-cipher-gui
(Or just save the .py file manually)

#Run the Script

bash:
->python caesar_gui.py

🧠 How to Use
Enter your message in the top text area.

Enter a shift value between 0 and 25 in the "Shift" field.

Select Encrypt or Decrypt using the radio buttons.

Click the Submit button.

The result will be displayed in the "Output" box below.

🔐 Example
Message: Hello World

Shift: 3

Mode: Encrypt

Output: Khoor Zruog

📌 Notes
Only alphabetic characters are shifted.

Other characters (numbers, punctuation) remain unchanged.

Shift wraps around (e.g., Z with shift of 1 becomes A).
