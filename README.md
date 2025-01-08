
---

📊 **Social Media Performance Analyzer** 
![Screenshot 2025-01-08 211907](https://github.com/user-attachments/assets/497a116b-5bb2-4288-8880-ef2db1852c8a)
✨ **Welcome to Hack Code's Pre-Hackathon Assignment: Social Media Performance Analysis!**  

### **Our Dynamic Team**  
👨‍💻 Swadesh Jadhav  
👨‍💻 Saniya Bhosale  
👨‍💻 Divya Bhavsar  
👨‍💻 Sanchit Shelke  

---

---

This project provides an analytics module for analyzing social media engagement using **Langflow** and **DataStax Astra DB**. It enables users to generate insights from engagement data such as likes, shares, and comments. The project includes a chatbot interface for interacting with the system.

-----

### 🚀 **Features**  
1. **Fetch Engagement Data**  
   Simulates and stores mock social media engagement data in **DataStax Astra DB**.  
   Simulated dataset includes metrics like:  
   - ❤️ **Likes**  
   - 💪 **Shares**  
   - 💬 **Comments**  
   - Post types: 🎢 **Carousel**, 🎥 **Reels**, and 🖼️ **Static Images**.  

2. **Analyze Post Performance**  
   A **Langflow workflow** was created to:  
   - 💡 Accept input for post types.  
   - 🔎 Query the dataset in Astra DB.  
   - 📈 Calculate average engagement metrics for each post type.  

3. **Generate Insights**  
   Use **GPT-powered Langflow workflows** to provide actionable insights.  

4. **Interactive Chatbot**  
   Engage with the analytics module through a **chatbot interface**.  

---

### 🛠️ **Technology Stack**  
- **Frontend**: HTML templates (index.html and chatbot.html)  
- **Backend**: Flask with REST API endpoints  
- **Database**: DataStax Astra DB  
- **Workflow Creation**: Langflow  
- **Deployment**: Vercel  

---

### 🗂️ **Directory Structure**  
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

### 🧩 **Environment Variables**  
Set the following environment variables for the application to function:  
- `LANGFLOW_ID`: Your Langflow instance ID.  
- `FLOW_ID`: The ID of your Langflow workflow.  
- `BASE_API_URL`: Base URL of the Langflow API.  
- `TOKEN`: Authentication token for the Langflow API.  

---

### ⚡ **Quick Start**  

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
   Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.  

---

### 🚀 **Deployment on Vercel**  

1. **Install the Vercel CLI**:  
   ```bash
   npm install -g vercel
   ```  

2. **Deploy the App**:  
   ```bash
   vercel
   ```  

---

### 📊 **Showcase**  

#### **Home Page**  
![Screenshot 2025-01-08 211757](https://github.com/user-attachments/assets/a3e0ad33-1ebe-48f3-81ad-918819bae65d)

#### **Chatbot Interface**  
![Screenshot 2025-01-08 211757](https://github.com/user-attachments/assets/306cf3cf-55f4-4f02-85d6-cf90f8960896)

---

### 🎥 **YouTube Video**  
Watch our project in action:  
[![YouTube Video]([https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=VIDEO_ID](https://www.youtube.com/watch?v=blsuzlHQNz0&feature=youtu.be))  

---

### 🌐 **Try it Now!**  
Check out our live deployment: [**Try it**]([https://your-deployment-link.vercel.app](https://supermind-hack.vercel.app/))  

---

### 📜 **License**  
This project is licensed under the MIT License.  

---  
