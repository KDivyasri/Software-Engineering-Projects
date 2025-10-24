💬 WhatsApp Chat Analysis
This project is a data-driven text analysis tool built using Python, Pandas, and Matplotlib to visualize and summarize WhatsApp group or individual chat data.
It helps uncover trends such as the most active participants, word usage frequency, and time-based activity patterns.

🧠 Project Overview
The WhatsApp Chat Analysis project reads exported chat files, cleans and structures the data, and generates visual reports.
It provides message statistics, emoji usage, and activity timelines, giving insights into conversation patterns.

📦 Project Features
📅 Chat Timeline: Visualizes daily, weekly, and monthly message activity  
👥 Participant Insights: Shows top active members and message distribution  
🔠 Word Cloud: Highlights the most frequently used words  
😀 Emoji Statistics: Displays the most used emojis and counts  
🕒 Hourly Activity Map: Identifies peak messaging hours  
📊 Visual Dashboards: Interactive charts using Matplotlib and Seaborn  

🧰 Tech Stack
| Category | Technologies |
|-----------|--------------|
| Language | 🐍 Python |
| Libraries | 📊 Pandas, Matplotlib, Seaborn, WordCloud, emoji |
| Frontend | 🧮 Streamlit (for visualization UI) |
| Data Source | 📱 Exported WhatsApp chat `.txt` file |
| Deployment | ☁️ Streamlit Cloud / Local Environment |

🚀 Getting Started (Local Setup)
1️⃣ Clone the Repository  
```bash
git clone https://github.com/<your-username>/Software-Engineering-Projects.git
cd whatsapp-chat-analysis  2️⃣ Create Virtual Environment python3 -m venv venv
source venv/bin/activate  3️⃣ Install Dependencies pip install -r requirements.txt  4️⃣ Run the App streamlit run app.py  5️⃣ Access the App
Open your browser → http://localhost:8501

📂 Project Structure whatsapp-chat-analysis/
│
├── app.py               # Streamlit main app
├── preprocessing.py     # Chat parsing and data cleaning
├── helper.py            # Analytics helper functions
├── requirements.txt     # Python dependencies
└── assets/              # WordClouds and visuals  ☁️ Deployment
This project can be deployed on Streamlit Cloud or any Python hosting service:
1️⃣ Push your project to GitHub
2️⃣ Create a new Streamlit Cloud app linked to your repo
3️⃣ Add necessary environment variables and deploy 🚀

📜 License
This project is licensed under the MIT License.
Feel free to modify and use it for your learning or analysis needs.

💡 Author
👩‍💻 Divyasri Kadambi
✨ Python | Data Analysis | Visualization Enthusiast
