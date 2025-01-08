

# 📊 Social Media Performance Analyzer

**✨ Welcome to Hack Code's Pre-Hackathon Assignment: Social Media Performance Analysis!**

Our dynamic team:  
👨‍💻 **Swadesh Jadhav**  
👨‍💻 **Saniya Bhosale**  
👨‍💻 **Divya Bhavsar**  
👨‍💻 **Sanchit Shelke**

---

## 🚀 Features

### 1. **Fetch Engagement Data**  
- Simulates and stores mock social media engagement data in **DataStax Astra DB**.
- Simulated dataset includes metrics like:  
  ❤️ **Likes**, 💪 **Shares**, 💬 **Comments**, and post types such as 🎢 **carousel**, 🎥 **reels**, and 🖼️ **static images**.

### 2. **Analyze Post Performance**  
- A **Langflow workflow** was created to:  
  💡 Accept **input for post types**.  
  🔎 Query the dataset in Astra DB.  
  📈 Calculate **average engagement metrics** for each post type.

### 3. **Generate Insights**  
- Use **GPT-powered Langflow workflows** to provide actionable insights.

### 4. **Interactive Chatbot**  
- Engage with the analytics module through a **chatbot interface**.

---

## 🛠️ Technology Stack

- **Frontend**: HTML templates (`index.html` and `chatbot.html`)  
- **Backend**: Flask with REST API endpoints  
- **Database**: DataStax Astra DB  
- **Workflow Creation**: Langflow  
- **Deployment**: Vercel  

---

## 🗂️ Directory Structure

```plaintext
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

Set the following environment variables for the application to function:

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

## 🚀 Deployment on Vercel

1. **Install the Vercel CLI**:  
   ```bash
   npm install -g vercel
   ```

2. **Deploy the App**:  
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

This project is licensed under the **MIT License**.

---


