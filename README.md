📊 Social Media Performance Analyzer

✨ Welcome to Hack Code's Pre-Hackathon Assignment: Social Media Performance Analysis!
Our dynamic team consists of:
👨‍💻 Swadesh Jadhav
👨‍💻 Saniya Bhosale
👨‍💻 Divya Bhavsar
👨‍💻 Sanchit Shelke

---

This project provides an analytics module for analyzing social media engagement using **Langflow** and **DataStax Astra DB**. It enables users to generate insights from engagement data such as likes, shares, and comments. The project includes a chatbot interface for interacting with the system.

## 🚀 Features

- **Fetch Engagement Data**: Simulate and store mock social media engagement data in DataStax Astra DB.
- **Analyze Post Performance**: Calculate average engagement metrics for different post types (e.g., carousel, reels, static images).
- **Generate Insights**: Use GPT-powered Langflow workflows to provide actionable insights.
- **Interactive Chatbot**: Engage with the analytics module through a chatbot interface.

---

## 🛠️ Technology Stack

- **Frontend**: HTML templates (`index.html` and `chatbot.html`)
- **Backend**: Flask with REST API endpoints
- **Database**: DataStax Astra DB
- **Workflow Creation**: Langflow
- **Deployment**: Vercel

---



##  📈 Task Breakdown
1. 🔍 Fetch Engagement Data
Simulated dataset includes metrics like:
    ❤️ Likes
    💪 Shares
    💬 Comments
    Post types (e.g., 🎢 carousel, 🎥 reels, 🖼️ static images).
    Data is stored in DataStax Astra DB.
2. 🔄 Analyze Post Performance
A Langflow workflow was created to:
    💡 Accept input for post types.
    🔎 Query the dataset in Astra DB.
    📈 Calculate average engagement metrics for each post type.

---
## 🗂️ Directory Structure

```
shelkesanchit-Social-Media-Performance-Analyzer/
├── README.md
├── app.py
├── requirements.txt
├── vercel.json
└── templates/
    ├── chatbot.html
    └── index.html
```

---

## 🧩 Environment Variables

Ensure the following environment variables are set for the application to function properly:

- `LANGFLOW_ID`: Your Langflow instance ID.
- `FLOW_ID`: The ID of your Langflow workflow.
- `BASE_API_URL`: Base URL of the Langflow API.
- `TOKEN`: Authentication token for the Langflow API.

---

## ⚡ Quick Start

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Social-Media-Performance-Analyzer.git
   cd Social-Media-Performance-Analyzer
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Environment Variables**:
   Create a `.env` file in the root directory and add the required variables.

4. **Run the Application**:
   ```bash
   python app.py
   ```

5. **Access the Application**:
   Visit `http://127.0.0.1:5000` in your browser.

---

## 🚀 Deployment

The app is pre-configured for deployment on **Vercel**. Follow these steps:

1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy the App:
   ```bash
   vercel
   ```

---

## 📊 Showcase

### Home Page
![Home Page](https://via.placeholder.com/800x400?text=Home+Page)

### Chatbot Interface
![Chatbot Interface](https://via.placeholder.com/800x400?text=Chatbot+Interface)

*(Replace placeholders with actual screenshots.)*



---

## 📜 License

This project is licensed under the MIT License.

---

