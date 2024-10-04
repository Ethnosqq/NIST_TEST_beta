***Project Title: Enhancement of the NIST Randomness Test Suite

***Project Goal:
The goal of the project was to expand the functionality of the existing NIST randomness test suite, enabling it to handle multiple files and create an executable application for ease of use.

***Key Responsibilities and Achievements:

Code Modification and Enhancement:
Updated the execute method to support the processing of multiple input files, requiring substantial changes to the program logic. This ensured that data from various sources could be handled and analyzed concurrently. Also, ensured correct handling and cleaning of data from different file types, accounting for various formats and preprocessing needs.

File Management and Processing:
Developed a mechanism for selecting and processing multiple binary and string-based files. The functionality allowed users to select files interactively and ensured correct reading and processing, including optimizing the performance of data reading and handling potential exceptions for application stability.

GUI Enhancements:
Implemented features to allow users to select multiple files through a graphical user interface. The existing controls were updated to make the user experience more intuitive, including the creation of interactive components for displaying test results and managing test execution.

Executable Creation:
Configured and utilized PyInstaller to create a standalone executable file (main.exe). All necessary dependencies were packaged, ensuring the application could run autonomously across different systems without requiring additional library installations.

Documentation and Collaboration:
Created detailed documentation outlining the code changes and enhancements for both users and developers. Worked closely with the team, testing and validating the functionality to ensure that any issues were identified and resolved promptly.

Conclusion:
The project was successfully completed, and the enhanced NIST randomness test suite now supports multiple file processing, offers an improved user interface, and can be run as a standalone application. These improvements significantly increased the tool's functionality and user-friendliness.

Technologies Used:

Python
Tkinter (for GUI)
PyInstaller (for building executables)
NumPy, SciPy (for statistical calculations)
Importlib Resources (for resource management)
