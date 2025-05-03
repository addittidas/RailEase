# RailEase: Seamless Railway Booking

**RailEase** is a modern, interactive frontend web train booking application that provides a seamless and user-friendly experience for booking train tickets online. The platform takes users through a complete journey — from registration to ticket generation. It simulates booking functionality with dynamically generated train data.

## 🔧 Features

- Simple and clean UI with modern styling

- Responsive design (with external CSS)

- **Session Storage-Based State Management**
All user selections (departure, arrival, date, selected train, passenger details) are maintained across pages using sessionStorage, eliminating the need for backend sessions.

- **Dynamic Train Generation with Time Calculations**
Train options are generated randomly in real-time with dynamic departure and arrival times. Arrival date and travel duration are calculated using JavaScript Date APIs.

- **Modular Page-to-Page Navigation Flow**
The app is structured into distinct HTML files, mimicking a multi-page application where each page performs a dedicated function, ensuring clear code separation and modularity.

## Steps Involved

1. **User Registration**: 
    - Create an account with a username, phone number, email and password.
2. **Departure & Arrival Details**: 
    - Select departure and arrival locations along with the travel date.
3. **Train Availability**: 
    - View available trains based on the selected details.
4. **Passenger Details**: 
    - Enter passenger names and details to generate tickets.
5. **Payment**: 
    - Complete the payment process.
6. **Ticket Generation**: 
    - A random ticket ID is generated once payment is confirmed.

## ⚙️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript

## 💡 How to Run

1. Clone the repository or download the files.
    ```bash
    git clone https://github.com/addittidas/RailEase.git
    cd RailEase
    ```
2. Open `1_user_reg.html` in your browser to start.
3. Navigate through each step as you fill in the required details.

> Make sure all files are in the same directory structure to avoid broken links.

## License

This project is licensed under the MIT License - see the LICENSE file for details

## 📌 Note

This is a frontend-only mock project for showcasing available train options, and finally booking a ticket, submitted as a task of Web Technologies course, Sem-IV (April 2024).