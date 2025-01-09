# PG_LIFE_MANAGEMENT Web Application

---

PG_LIFE_MANAGEMENT is a **Full-Stack Web Application**. This is a project that I was assigned to make during my **Internshala Full Stack Web Development Internship Training**. I got the guidance, and following that, I made this web application with my own understanding and knowledge. It is customized according to what I thought would be better functionalities in this app, from the user perspective.

The entire web app is fully responsive and is operational from any device.

## Tech Stack

- **Frontend**: HTML, CSS, Bootstrap 5, JavaScript, AJAX
- **Backend**: PHP
- **Database**: MySQL

## Features

### 1. The Home Page
- **Search Bar**: Users can enter a city name (in any case), and PGs listed in that city (if they exist in the database) will be shown as a list.
- **City Sections**: Main cities are displayed as circular sections. Clicking on any city will show the list of PGs existing in that city.

### 2. The PG List Page
- **PG List**: Displays the list of all PGs in the selected city in the form of beautiful cards.
- **Filter Bar**: PGs can be sorted by rent and rating, either in ascending or descending order.
- **Interest Count**: Shows how many users have marked each PG as "interested" to indicate its popularity.
- **Heart Icon**: After logging in, users can mark any PG(s) as "interested" by clicking the heart icon. The icon toggles its fill color when clicked, and the number of interested users updates dynamically.

### 3. The PG Details Page
- **PG Information**: Displays detailed information about a selected PG, such as amenities, testimonials, and address.
- **Carousel**: Displays images of the selected PG in a beautiful carousel.
- **Interest Count**: Shows how many users have marked the PG as "interested".
- **Heart Icon**: Users can mark the PG as "interested" or "not interested" by clicking the heart icon. The number of interested users updates dynamically.

### 4. The Dashboard
- **User Profile**: Visible only to logged-in users, showing account details and information about their interests.
- **Interested Properties**: Displays cards of PGs marked as "interested" by the user across any city. Users can click the heart icon to remove a PG from the list.
- **Dynamic Updates**: Changes to the list are dynamically updated based on user actions.

### 5. The Navbar
- **Brand Name**: Contains the brand name of the web app.
- **Login/Signup Options**: If not logged in, it shows options to sign up or log in.
- **Dashboard/Logout**: If logged in, it shows options to go to the dashboard and log out. It also displays the user's first name, retrieved using **SESSION**.
- **Responsive Toggler Navbar**: Fully responsive and adjusts according to the screen size.

### 6. The Breadcrumb
- **Navigation Aid**: Shows the relative location of the user in the web app, making it easier to navigate.
- **Hyperlinks**: Provides hyperlinks for easy navigation back and forth through different pages.

### 7. The Footer
- **Popular Cities**: Displays a list of popular cities with hyperlinks to show PGs in those cities.
- **Copyright Information**: Contains copyright information at the bottom.

### 8. User Experience
- **Guest Browsing**: The web app can be used without logging in, allowing users to browse PGs freely. Certain features like the dashboard and marking interest are available only after logging in.

### 9. Error Handling
- **Custom Error Handling**: The web app ensures that all exceptions are well-handled, providing users with meaningful error messages and maintaining a smooth experience.

---



## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/PG_LIFE_MANAGEMENT.git
    cd PG-Life
    ```

2. Set up the database:
   - Import the SQL files from the `database` folder into MySQL.

3. Configure the PHP server:
   - Use XAMPP/WAMP or a similar local server to run the app.

4. Access the app:
   - Open the web app in your browser at `http://localhost/PG_LIFE_MANAGEMENT`.

---

## Contributing

Feel free to fork the repository, create a branch for your feature, and submit a pull request.





