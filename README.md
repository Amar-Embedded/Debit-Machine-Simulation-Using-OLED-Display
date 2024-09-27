# Debit-Machine-Simulation-Using-OLED-Display

overview - This project simulates a basic debit card transaction machine using an OLED 1331 display and pushbuttons for user input. The project utilizes the SPI protocol for communication between the microcontroller and the OLED display.

Components Used:
OLED 1331 Display: A small OLED screen for displaying transaction details.
Pushbuttons: For user interaction to simulate entering the amount, selecting options, and confirming transactions.
Microcontroller: STM32l432KC handles logic, user inputs, and display updates.
SPI Protocol: Used to communicate with the OLED display, allowing for fast and efficient data transfer.

Functionality:

User Input via Pushbuttons:

Users can enter the transaction amount using the buttons.
One button simulates numeric entry, while others may be used for confirming the transaction or canceling.

OLED Display:

Displays transaction information such as "Enter Amount," the amount being entered, and confirmation messages.
Shows "Transaction Approved" or "Transaction Declined" messages after user input is confirmed.
SPI Communication:
The OLED 1331 display is connected to the microcontroller via the SPI protocol, ensuring smooth and efficient data transfer for updating the display in real-time as the user interacts with the buttons.
Transaction Simulation:
Once the amount is entered, the system simulates processing the transaction.
The result (approved or declined) is displayed on the OLED screen.
This project demonstrates the use of SPI communication for driving an OLED display, interfacing with input devices like pushbuttons, and simulating a real-world debit machine transaction process.
