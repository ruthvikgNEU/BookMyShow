


# AMC Theaters

AMC Theaters is a Java and JavaFX-based application designed to simulate a movie theater management system. This application allows users to interact with a graphical interface to manage movie screenings, bookings, and customer interactions.

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed a Java Development Kit (JDK), version 8 or newer.
* You have Eclipse IDE installed.
* You have downloaded the JavaFX SDK that is compatible with your JDK version.

## Setup and Running the Project

Follow these steps to get your development environment set up:

1. **Clone the repository:**
   ```bash
   git clone [URL of the repo]
   ```

2. **Download JavaFX SDK:**
   - Download the JavaFX SDK from [https://gluonhq.com/products/javafx/](https://gluonhq.com/products/javafx/).
   - Extract the SDK to a known location on your machine.

3. **Import the JavaFX libraries:**
   - Open Eclipse IDE and import the project.
   - Right-click on the project, select `Build Path`, then `Configure Build Path`.
   - Under the `Libraries` tab, click `Add Library`, select `JavaFX SDK`, and navigate to where you extracted the JavaFX SDK.

4. **Set up VM arguments:**
   - Right-click on the project in Eclipse.
   - Select `Run As` > `Run Configurations`.
   - In the `Arguments` tab, under VM arguments, input:
     ```
     --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml
     ```
     Make sure to replace `/path/to/javafx-sdk/lib` with the actual path to the JavaFX libraries.

5. **Run the Project:**
   - In Eclipse, right-click on the project.
   - Select `Run As` > `Java Application`.

### Contributors

- **Arpita Desai** - Worked on Film Page, Film Management Page, View Films Page, design workflow, and presentation.
- **Mani Charan Reddy Loka** - Worked on Main class, Login Page, SignUp Page, and presentation.
- **Mohitha Edara** - Worked on Send Email Page, Employee Home Page, UI Design, and presentation.
- **Ruthvik Garlapati** - Worked on Ticket Booking Page, Booking Management Page, Booking History Item Page, and presentation.
- **Prakhya Dasari** - Worked on Confirmation Page, Seat Booking Page, and presentation.



