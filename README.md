Electronic Voting Machine (EVM) 🗳️

📌 Project Overview

This project is an Arduino-based Electronic Voting Machine (EVM) designed for educational and demonstration purposes. It allows users to cast votes using push buttons and displays the recorded votes and final results on a 16×2 I2C LCD.

The system also uses an SD card module to store voting data and provides LED and buzzer feedback whenever a vote is registered.

✨ Features

- 🗳️ Voting for 6 candidates/parties
- 📺 16×2 I2C LCD display
- 🔊 Buzzer notification after vote registration
- 💡 LED indication for a registered vote
- 💾 SD card storage for voting data
- 📊 Result display on LCD
- 🔘 Separate result button
- ⚡ Arduino-based implementation

🛠️ Hardware Components

- Arduino board
- 16×2 I2C LCD
- 6 Push Buttons for voting
- 1 Push Button for displaying results
- Buzzer
- LED
- SD Card Module
- Resistors
- Jumper Wires
- Breadboard
- USB Cable / Power Supply

💻 Software & Technologies

- Arduino IDE
- Embedded C/C++
- Arduino
- I2C Communication
- SD Card File Handling

🔌 Pin Configuration

Component| Arduino Pin
Voting Button 1| D2
Voting Button 2| D3
Voting Button 3| D4
Voting Button 4| D5
Voting Button 5| D6
Voting Button 6| D7
Buzzer| D8
Result Button| D9
SD Card CS| D10
LED| D11
I2C LCD| SDA/SCL

⚙️ Working

1. The system initializes the LCD and SD card.
2. The LCD displays "EVM Ready".
3. A voter presses one of the six voting buttons.
4. The selected candidate's vote count increases by one.
5. The LED lights up and the buzzer gives an indication.
6. The selected candidate is displayed on the LCD.
7. Voting data is saved to the SD card.
8. Pressing the Result Button displays the vote count of each candidate.
9. The results are also saved to the SD card.

📂 Project Files

- "EVM_Code.ino" — Arduino source code
- "EVM Circuit Diagram" — Circuit connection diagram
- "EVM Project Image" — Project/model image

🎯 Applications

This project can be used as an educational prototype to understand:

- Embedded systems
- Arduino programming
- Digital input/output
- LCD interfacing
- SD card data storage
- Button-based voting systems

👩‍💻 Author

Priyanka Diwakar

B.Tech – Electronics & Communication Engineering

⚠️ Disclaimer

This is an educational prototype/demo project and is not intended for use as an official election voting system.
