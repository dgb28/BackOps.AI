
## 🚀 BackOps.AI

🎉 Winner of the 2024 Annual Luddy Hackathon at Indiana University Bloomington 🎉

## 🌟 Overview

BackOps.AI is an intelligent assistant designed to streamline backend operations using natural language inputs. By leveraging powerful LLMs, BackOps.AI parses user commands into structured JSON formats, enabling efficient and seamless execution of database operations such as insertions, updates, and deletions.

![Screenshot 2024-11-18 171524](https://github.com/user-attachments/assets/8a10da9f-0892-41cd-8640-c7a34a73a21c)


## 🔧 Core Tasks

### 🎯 Prompt Design

Implemented few-shot prompting to capture various actions like insert, delete, update, and create.

### 🗃️ Backend System Design

Created an in-memory database for a key-value store that includes:

- Key 🗝️
- Value 📄
- Created datetime ⏰
- Updated datetime 🔄

## UI/UX Design 🎨

Designed a web interface to:

- Input queries 💬
- View database manipulations 🛠️
- Analyze system performance 📊

## ⚙️ Implementation

Developed a platform where users can:

- Take sentences 📜
- Construct prompts ✍️
- Send them to the LLM 🤖
- Manipulate databases 🗂️
- Perform requested actions ✅
- Provide analytics 📈
  
### 🧪 Testing

Applied rigorous testing with various prompts and documented the success and failure of the system.

### 🔍 Auditing

- Monitored and tracked all changes made in the database to:
- Improve transparency 🪞
- Enhance understanding of data trends 📊
- Create intuitive visualizations 🎥

## ✨ Additional Features
- 📝 Log of Every Query Asked
- 📆 Day-wise Analytics
- 📊 Key Performance Indicators (KPIs):
    - Total count of Insertions, Deletions, and Updates
    - Percentage of Success and Failures
- 📈 Visualized Past 7 Days of Activities

## Steps to Run these Project:

1. Clone this repo.
2. Create virtual environment using python `venv` command.
3. Activate virtual environment.
4. Install all dependencies using `pip install -r requirements.txt`.
5. Go to `app` directory using `cd AI-agent-operating-backend-system/app`.
6. Run `uvicorn main:app --reload` to start your application.

## 👥 Collaborators

| Team Member Name | Email |
| ----- | ----- |
| Dev Patel | dap3@iu.edu |
| Dhruv Bhanderi | dbhander@iu.edu |
| Yash Vyas | yashvyas@iu.edu | 
| Dhwanit Pandya | dhpandya@iu.edu |
