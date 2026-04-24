# welcomescreen
This application ensures that users read and accept lab rules before accessing a computer system, promoting discipline and proper usage.

The Computer Lab Access System is a desktop-based application developed using Tkinter, designed to enforce discipline and ensure proper usage of computer lab resources. The primary objective of this system is to make users aware of important lab rules and require their acknowledgment before granting access to the system.

When the application starts, it opens in a full-screen mode, creating a controlled environment where the user cannot easily exit or bypass the interface. This is achieved by disabling common keyboard shortcuts such as Alt+F4, Escape, and Alt+Tab, ensuring that the user remains on the screen until the process is completed.

The interface displays a list of predefined lab rules, such as maintaining silence, avoiding unauthorized software installation, handling hardware carefully, and following instructor guidelines. Each rule is presented with a checkbox, requiring the user to actively select and acknowledge every instruction. Additionally, there is a final confirmation checkbox stating that the user has read and understood all the rules.

The system continuously monitors user interaction. The “Continue” button remains disabled until all rule checkboxes and the final confirmation checkbox are selected. Once all conditions are satisfied, the button becomes active, allowing the user to proceed. Upon clicking the button, the application closes, indicating that the user has accepted all terms.

This application is particularly useful in environments where controlled access and rule enforcement are critical, such as:

Educational institutions (schools and colleges)
Computer training centers
Public computer labs and cyber cafés
Office environments with shared systems

From a functional perspective, the system helps in:

Promoting discipline and responsible behavior
Reducing misuse of computers and lab resources
Ensuring users are informed about rules before usage
Creating a structured and secure lab environment.
