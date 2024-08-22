# Email Deletion Impact Tracker

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Overview

The Email Deletion Impact Tracker is a simple web application that helps users measure the environmental impact of deleting emails. By entering the number and type of emails, users can see how much CO2 is saved and how many plastic bottles are equivalent to that impact. The goal is to promote more sustainable digital habits and raise awareness of the environmental footprint of our online activities.

## Features

- **Email Deletion Tracking:** Input the number of emails you want to delete and select the type (regular, with attachments, or spam).
- **Environmental Impact Calculation:** Calculates the CO2 saved based on the email type and the number deleted.
- **Firebase Realtime Database:** Stores and updates the data in real time.
- **User Notifications:** Informs users of the successful submission and directs them to view detailed results on the dashboard.
- **Responsive Design:** Works seamlessly on mobile and desktop devices.

## Technologies Used

- **Frontend:**
  - HTML, CSS (with Bootstrap)
  - JavaScript
- **Backend:**
  - Firebase Realtime Database
- **Hosting:**
  - Firebase Hosting

## Getting Started

### Prerequisites

- A Google Firebase account for setting up the Realtime Database and Hosting.
- Basic knowledge of HTML, CSS, and JavaScript.

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/gabriel-dalton/email-deletion-impact-tracker.git
    cd email-deletion-impact-tracker
    ```

2. **Set up Firebase:**

    - Go to the Firebase Console and create a new project.
    - Set up Firebase Realtime Database.
    - Add a new web app in the project settings and copy the Firebase config details.

3. **Configure the project:**

    - Replace the Firebase configuration in the script section of `index.html` with your Firebase project details.

4. **Deploy:**

    - Deploy the project using Firebase Hosting or your preferred hosting service.

## Usage

1. **Open the application in your web browser.**
2. **Enter the number of emails you want to delete.**
3. **Select the type of emails:**
   - Regular
   - With Image/Attachment
   - Spam
4. **Click on "Record Email Deletion" to save your data.**
5. **View your environmental impact and track your progress on the dashboard.**

## Contributing

Contributions are welcome! If you have suggestions, bug fixes, or improvements, feel free to submit a pull request. Please ensure your changes align with the project goals and coding standards.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Credits

- **Developer:** Gabriel Dalton
