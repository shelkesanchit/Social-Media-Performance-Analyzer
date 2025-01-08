

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
![Screenshot 2025-01-08 212020](https://github.com/user-attachments/assets/b19fd2df-3ead-4b01-9005-33474212be70)


![Screenshot 2025-01-08 211757](https://github.com/user-attachments/assets/306cf3cf-55f4-4f02-85d6-cf90f8960896)

### Chatbot Interface  
![Screenshot 2025-01-08 211907](https://github.com/user-attachments/assets/497a116b-5bb2-4288-8880-ef2db1852c8a)


---




## 📜 License

This project is licensed under the **MIT License**.

---


