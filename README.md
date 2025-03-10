📥 ezSnap - Online Video Downloader

ezSnap is a simple and efficient video downloader that allows users to download videos from Instagram. It features a custom frontend and backend for seamless processing.

🚀 Features

    📌 Download Videos from Instagram.
    ⚡ Fast & Efficient processing using a Python script integrated with Node.js.
    🗃️ Database Logging (IP address, access timestamps, and device type).
    🎨 Custom UI/UX for a smooth user experience.
    🌐 Self-Hosted on an IONOS VPS.


🏗️ Tech Stack
| Component       | Technology Used |
|-----------------|----------------|
| **Frontend**    | HTML, CSS, JavaScript |
| **Backend**     | Node.js, Express.js |
| **Database**    | MySQL (Hostinger) |
| **Processing**  | Python  (for instagram Downloads) |
| **Hosting**     | IONOS |

    

🔧 Installation
1️⃣ Clone the Repository

git clone https://github.com/eZpiyush/ezsnap.git
cd ezsnap

2️⃣ Install Dependencies

npm install

3️⃣ Configure Environment Variables

configure the databse file according to your own database credentials

4️⃣ Run the Backend

node server.js

5️⃣ Run the Frontend

Open index.html in your browser or set up a local server.

⚙️ How It Works

    Users paste a video URL into the input field.
    The backend processes the request and, if necessary, calls the Python script for Instagram videos.
    The downloaded video is stored temporarily and provided for user download.
    User activity is logged in the SQL database.


📌 Future Enhancements

    📺 Support for more platforms
    📈 Dashboard for tracking downloads
    🔐 User authentication for premium features

🤝 Contributing

Feel free to submit issues and pull requests!
📝 License



