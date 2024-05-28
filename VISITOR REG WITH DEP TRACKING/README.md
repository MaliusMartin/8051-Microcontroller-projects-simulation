8051 microcontroller-based visitor registration and counting system with departmental tracking and activity logging:

**Project Title:** 8051 Microcontroller-Based Visitor Registration and Counting System with Departmental Tracking and Activity Logging

**Description:**

This project implements a visitor registration and counting system using an 8051 microcontroller, simulating its functionality in Proteus. It offers the following functionalities:

* **Enhanced Visitor Registration:** Users can register their presence and select their department from a predefined list.
* **Real-time Departmental Visitor Counts:** The system keeps track of visitor counts per department, providing valuable occupancy insights.
* **Accurate Exit Detection and Counting:** An exit sensor (e.g., IR sensor) precisely tracks visitor departures, updating total and departmental counts accordingly.
* **External Memory Visitor Activity Logging:** Visitor activity data (date/time, entry/exit type, department, total departmental occupants) is stored in external memory (e.g., EEPROM) for future analysis.
* **Hourly High-Occupancy Tracking:** The system identifies and stores a list of departments with the highest occupancy every hour throughout a 24-hour cycle, providing insights into peak visitor traffic patterns within departments.
* **Informative LCD Display:** A Liquid Crystal Display (LCD) serves as a user-friendly interface, displaying the current total visitor count, departmental visitor counts, and potentially basic department occupancy information.

**Software Used:**

* **Simulation:** Proteus
* **Compiler:** Keil MDK-ARM 5 (formerly Keil51)

**Hardware Requirements (Simulation):**

* 8051 Microcontroller (model specific to your simulation)
* LCD Display (model specific to your simulation)
* Additional components as required for sensors, inputs, and external memory (simulation models may suffice)

**Getting Started:**

1. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/your-username/8051-visitor-counter.git
   ```
2. **Install Keil MDK-ARM 5:**
   Download and install Keil MDK-ARM 5 from [https://www.keil.arm.com/](https://www.keil.arm.com/) (ensure compatibility with your operating system).
3. **Open the Project in Keil MDK-ARM 5:**
   - Launch Keil MDK-ARM 5.
   - Go to **Project** -> **Open Existing Project**.
   - Navigate to the downloaded project directory and select the Keil project file (usually with a `.uvproj` extension).

**Compiling and Simulating:**

1. **Configure Keil Project (if necessary):**
   - In Keil MDK-ARM 5, you might need to adjust project settings (e.g., include paths, microcontroller model) to match your simulation setup. Refer to Keil's documentation for details.
2. **Compile the Code:**
   - Go to **Project** -> **Build Target**.
   - If compilation is successful, an executable file (usually with a `.hex` extension) will be generated in the project's output directory.
3. **Simulate in Proteus:**
   - Open your Proteus project.
   - Configure the 8051 microcontroller component to use the generated `.hex` file.
   - Add the LCD display and other required components to your Proteus schematic.
   - Connect the components according to the project's design.
   - Run the simulation in Proteus to observe the system's functionality.

**External Memory Integration (Optional):**

If you plan to implement external memory for activity logging, you'll need to modify the code to interact with the specific memory device (e.g., EEPROM) using Keil's library functions or custom routines. Consult the memory device's datasheet and Keil's documentation for guidance.

**Additional Notes:**

* This README provides a general overview. Refer to the project's code comments for detailed implementation specifics.
* The project is designed for simulation purposes. Adaptations might be necessary for real-world hardware deployment.

## Contributors

- [Eng Walid Waziri](https://github.com/liderwally)
<!-- - [Contributor 1](https://github.com/contributor1)
- [Contributor 2](https://github.com/contributor2) -->

## License

This project is licensed under the [Apache License](LICENSE).

**Feel free to contribute or ask questions!**

I hope this comprehensive README effectively guides you in setting up and running your project.