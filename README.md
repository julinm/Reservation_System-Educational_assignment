Reservation system – Java Project


Status: Educational assignment – part of my training

Description:
This project is a Java Swing desktop application developed as part of a course assignment. It implements a reservation interface for "Salón Habana", a hall used for conventions, events, and conferences, following a specific set of requirements provided by the instructor.
The application allows users to enter reservation details, select the type of event, number of attendees, type of cuisine, and, if applicable, additional options for conferences. It includes validations to ensure that all necessary fields are filled out correctly.

-----------
Assignment Context

Objective:
Develop a reservation interface for a hotel management application that fulfills the following requirements:
Record the name and contact phone number of the person making the reservation.
Capture the following event information:
Event date (implemented using a spinner with a custom model)
Event type: Banquet, Workshop, or Conference (component at your discretion)
Number of attendees (component at your discretion)
Type of cuisine: Buffet, À la carte, Chef appointment, or Not required (component at your discretion)
If the event type is Conference, additionally request:
Number of sessions
Whether rooms are required for attendees

These fields should be initially disabled and only enabled when "Conference" is selected.

Non-functional requirements:

Assign a name and ToolTipText to each component.
Modify label fonts and organize components with panels, titles, and separators for visual clarity.
Use free design mode to arrange components harmoniously.
The interface should be connected to the main application via the main menu and a button, opening as a modal dialog.
Enable or disable conference-specific fields depending on the selected event type.

----------------
Features

Input fields for:

Full name
Phone number
Event date (Spinner)
Event type (ComboBox)
Number of attendees
Type of cuisine (ComboBox)
Additional options for Conferences:
Number of sessions (ComboBox)
Requires rooms? (Yes/No RadioButtons)

Field validation using JOptionPane
Confirmation message after reservation
Option to reset the form for another reservation

------------------
Project Structure

Formulario.java: Main class with all interface logic and Swing components.
Swing components used: JFrame, JPanel, JLabel, JTextField, JComboBox, JSpinner, JRadioButton, JButton
Event handling: ActionListener and ItemListener
Input validations implemented with JOptionPane dialogs

----------------
How to Run

Open the project in NetBeans (or any Java IDE that supports Swing).
Compile and run Formulario.java.
Fill out all required fields and click "Reservar" to save the reservation.
If the event type is Conference, the additional fields will automatically become enabled.

-------------
Notes

Designed as an educational assignment, demonstrating the use of Swing components, event handling, and UI validation.
All data is handled in-memory; there is no database connection.
Interface designed for clarity and usability, following the assignment guidelines for layout, fonts, and component arrangement.
