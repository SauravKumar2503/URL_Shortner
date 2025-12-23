📎 URL Shortener Web Application

A full-stack URL Shortener application that allows users to convert long, complex links into short, easy-to-share URLs with analytics and a seamless redirect experience. Built using React for the frontend, Node.js & Express for the backend, and MongoDB for data persistence, this project demonstrates modern web development practices and best practices in REST API design. 


🚀 Live Demo

👉 https://url-shortner-two-liard.vercel.app


🚧 Features

🔗 Shorten Long URLs: Enter any valid URL and receive a shortened version.

📊 Trackable: Store and serve all shortened URLs in a database.

🔁 Automatic Redirect: Navigate to the original URL when visiting a shortened link.

📋 Copy to Clipboard: Easily copy the shortened link with one click.

📱 Responsive UI: Built with a clean and intuitive React interface. 
<img width="1919" height="863" alt="Screenshot 2025-12-23 121429" src="https://github.com/user-attachments/assets/45f5db94-262c-4e78-a482-b0eb85d38b8f" />


🧠 Tech Stack
Layer	Technologies
Frontend	React, JavaScript, HTML, CSS
Backend	Node.js, Express.js
Database	MongoDB
Tools	Git & GitHub
📁 Project Structure
URL_Shortner/
├── backend/                # Server API built with Node.js & Express
├── frontend/               # React web application
├── .gitignore
├── README.md

🛠 Installation & Setup
1. Clone the repository
git clone https://github.com/SauravKumar2503/URL_Shortner.git
cd URL_Shortner

2. Backend Setup
cd backend
npm install


Create a .env file in the backend folder and add:

MONGO_URI=your_mongodb_connection_string
PORT=5000


Start the backend server:

npm start

3. Frontend Setup
cd ../frontend
npm install
npm start


The application should now be running at http://localhost:3000
.

🧪 Usage

Open the web app in your browser.

Enter a long URL in the input field.

Click Shorten.

View and copy the shortened link.

Share or use the link — it will redirect users to the original URL.

🙌 Improvements & Roadmap

Future enhancements could include:

🔐 User authentication & dashboard

📊 Click analytics and link performance stats

⚙️ Custom short link aliases

🧪 Comprehensive testing (unit & integration tests)

🚀 Deployment pipelines (Vercel, Render, Heroku)

🧑‍💻 About the Developer

Saurav Kumar
Aspiring Full-Stack Developer | Java & MERN Stack | Passionate About Building Real-World Web Applications

📫 Email: sourav2002kumar@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/saurav232/

💻 GitHub: https://github.com/SauravKumar2503

⭐ Feedback & Contributions

Feel free to ⭐ star the repo, submit issues, or send PRs to help improve the project!
