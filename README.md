# AstroView - NASA Picture of the Day

## Description:
AstroView is an interactive, responsive web application that fetches and displays NASA’s Astronomy Picture of the Day using the NASA API. The app provides detailed information about the image, including its title, date, and description, which can be viewed in a modal. This project aims to showcase daily space photography and educate users about astronomical phenomena.

## Features:
- Fetch and display NASA’s Astronomy Picture of the Day
- Modal view with detailed information (title, date, description)
- Fully responsive design for a seamless experience across devices

## Technologies Used:
- React.js (Frontend)
- NASA API (Data source)
- Tailwind CSS (Styling)

## How to Run:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ShaikhAman01/AstroView-nasa
   ```

2. **Navigate into the project directory**:
   ```bash
   cd AstroView-nasa
   ```

3. **Set up environment variables for NASA API**:
   - Create a `.env` file in the root of the project and add your NASA API key:

     ```bash
     REACT_APP_NASA_API_KEY=your-nasa-api-key
     ```

   - Replace `your-nasa-api-key` with your actual NASA API key, which you can get from the [NASA API portal](https://api.nasa.gov/).

4. **Install dependencies**:
   ```bash
   npm install
   ```

5. **Run the application**:
   ```bash
   npm start
   ```

6. Open `http://localhost:3000` in your browser to view the app.
