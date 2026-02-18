This project demonstrates how to read digital input from a push button connected to a Raspberry Pi GPIO pin.

When the button is:

✅ Pressed → Displays: Button is pressed

❌ Not Pressed → Displays: Button is not pressed

This is a beginner-level hardware interfacing project for learning Raspberry Pi GPIO input handling.

🛠 Hardware Requirements

🖥 Raspberry Pi

🔘 Push Button

🔌 Jumper Wires

🍞 Breadboard (optional)

Resistor (if not using internal pull-up/down)

🔌 Circuit Connection
Component	Raspberry Pi GPIO
Button Pin 1	GPIO 2
Button Pin 2	GND

⚠️ Note: The gpiozero library uses an internal pull-up resistor by default.

💻 Software Requirements

Python 3

gpiozero library

Install gpiozero (if not installed):

pip install gpiozero

▶️ How to Run

Connect the push button as shown above.

Save the file as Button.py

Run the program:

python Button.py


The terminal will continuously display the button status.

📂 Project Structure
Button.py
README.md
