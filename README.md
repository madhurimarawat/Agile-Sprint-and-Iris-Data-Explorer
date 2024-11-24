# Agile-Sprint-and-Iris-Data-Explorer
Streamlit app that combines agile sprint planning with data visualization of the Iris dataset. It helps analyze task distribution and explore key data insights interactively.

**Streamlit App Snapshots:**

<a href="https://madhurima-agile-sprint-and-iris-data-explorer.streamlit.app/" target="_blank">
  <img src="https://github.com/user-attachments/assets/d8e5c040-7067-4b2c-b919-18056b05efb4" width="100%" title="App Snapshot 1" alt="Screenshot of Agile Sprint and Iris Data Explorer App - Snapshot 1">
</a>

<a href="https://madhurima-agile-sprint-and-iris-data-explorer.streamlit.app/" target="_blank">
  <img src="https://github.com/user-attachments/assets/aa33feb0-90ee-4185-979b-4649e58464be" width="100%" title="App Snapshot 2" alt="Screenshot of Agile Sprint and Iris Data Explorer App - Snapshot 2">
</a>

<a href="https://madhurima-agile-sprint-and-iris-data-explorer.streamlit.app/" target="_blank">
  <img src="https://github.com/user-attachments/assets/51d65b85-f273-45fd-8e23-4b24fb18e4af" width="100%" title="App Snapshot 3" alt="Screenshot of Agile Sprint and Iris Data Explorer App - Snapshot 3">
</a>

<a href="https://madhurima-agile-sprint-and-iris-data-explorer.streamlit.app/" target="_blank">
  <img src="https://github.com/user-attachments/assets/894404c9-6c75-4322-adbb-60d6c471e5d4" width="100%" title="App Snapshot 4" alt="Screenshot of Agile Sprint and Iris Data Explorer App - Snapshot 4">
</a>

<a href="https://madhurima-agile-sprint-and-iris-data-explorer.streamlit.app/" target="_blank">
  <img src="https://github.com/user-attachments/assets/100a9be8-5613-4455-a3e3-243bc0eb9a64" width="100%" title="App Snapshot 5" alt="Screenshot of Agile Sprint and Iris Data Explorer App - Snapshot 5">
</a>

---

## Directory Structure

```
📂 Agile-Sprint-and-Iris-Data-Explorer
├── 📁 Codes
│   ├── 📄 requirements.txt             # 📜 Contains necessary dependencies for running the Streamlit app.
│   ├── 📄 Streamlit_app.py             # 🚀 Main script for the Streamlit web app, enabling interactive Iris dataset visualization.
│   ├── 📄 Iris_Dataset_Analysis.py     # 📊 Python script for core analysis, preprocessing, and visualizing the Iris dataset.
│
├── 📁 Documentation Files
│   ├── 📄 Agile_Sprint_Planning.md     # 📋 Sprint planning documentation with timeline and completed tasks.
│   ├── 📄 Agile_Sprint_Planning.pdf    # 📄 Formatted PDF summarizing project outputs and features for sharing.
│
├── 📁 Output
│   ├── 📄 Experiment 8 Output.docx     # 📝 Word document detailing experiment results.
│   ├── 📄 Experiment 8 Output.pdf      # 📑 PDF version of the experiment results for easy distribution.
│
├── 📄 README.md                        # 📘 Project overview, setup instructions, and feature details.
├── 📄 LICENSE.md                       # 📜 License information for using and modifying the project.
```

---

## **Installation and Usage**

To run the Streamlit app, you need to install the required dependencies. You can install the necessary libraries by running the following command:

```bash
pip install -r requirements.txt
```

**Usage**

Once the dependencies are installed, you can start the Streamlit app by running:

```bash
streamlit run Streamlit_app.py
```

This will launch the application in your default web browser, where you can interact with the dataset and explore different visualizations.

---

## **Steps in the Project**

### **1. Project Overview: Agile Sprint Planning**

#### **Goal:**

- Conduct a simulated sprint planning session using Agile principles.
- Break down user stories into tasks, estimate their effort, and allocate them among team members (Alice, Bob, Charlie).
- Visualize and analyze sprint data using Streamlit.

---

### **2. Example Agile Sprint Planning Workflow**

**User Stories Example:**

Dataset and sprint task list tailored specifically to the described project, focusing on tasks like data collection, pipeline creation, deployment, and bug fixing.

---

### **Dataset Example for Agile Sprint Planning**

| Story ID | Description                                       | Priority | Effort | Assigned To |
| -------- | ------------------------------------------------- | -------- | ------ | ----------- |
| 1        | Collect dataset and clean for processing.         | Medium   | 4      | Alice       |
| 2        | Create a pipeline for visualizing sprint data.    | High     | 6      | Bob         |
| 3        | Deploy Streamlit app to cloud hosting.            | High     | 8      | Charlie     |
| 4        | Fix app crash caused by missing input validation. | High     | 9      | Alice       |
| 5        | Implement effort estimation slider for tasks.     | Medium   | 5      | Bob         |
| 6        | Add team assignment logic for user stories.       | Low      | 3      | Charlie     |

---

### **Steps for Task Breakdown and Assignment**

1. **Task Identification**: Break the project into actionable tasks (e.g., collect data, fix bugs, deploy app).
2. **Effort Estimation**: Use points to estimate the effort needed for each task (1 = low, 10 = high).
3. **Prioritization**: Assign priority levels (High, Medium, Low) based on project needs.
4. **Team Assignment**: Allocate tasks evenly among team members to balance workload.

---

### **Generated Sprint Plan**

| **Task**                            | **Points (Effort)** | **Priority** | **Assigned To** |
| ----------------------------------- | ------------------- | ------------ | --------------- |
| Data collection and preprocessing   | 4                   | Medium       | Alice           |
| Build sprint visualization pipeline | 6                   | High         | Bob             |
| Deploy app to Streamlit cloud       | 8                   | High         | Charlie         |
| Fix crash on invalid user input     | 9                   | High         | Alice           |
| Add effort slider for estimation    | 5                   | Medium       | Bob             |
| Add team assignment functionality   | 3                   | Low          | Charlie         |

---

### **Sprint Summary**

- **Total Effort**: 35 points.
- **Average Effort per Team Member**:
  - Alice: 13 points.
  - Bob: 11 points.
  - Charlie: 11 points.

---

### **Effort Distribution Visualization**

- A bar chart showing points distributed across Alice, Bob, and Charlie.
- Ensures balance and highlights potential overloads.

This setup uses Agile principles to organize, estimate, and allocate tasks efficiently, making the project manageable and transparent.

---

### **4. Code for Agile Sprint Planning Simulation**

The integration of the Agile Sprint Planning and dataset visualization in Streamlit includes:

1. **Effort Estimation**: 
   - Use the **slider** widget to estimate effort for each user story (range: 1–10). Effort is based on complexity and priority.
   
2. **Task Allocation**: 
   - Assign stories to team members using the **dropdown menu**. The system ensures that tasks are distributed evenly among Alice, Bob, and Charlie.

3. **Visualization**:
   - **Bar chart** showing effort distribution among team members, helping to identify if workloads are balanced.

---

### **5. Explanation of Agile Sprint Process**

| **Step**                  | **Code/Action**                                                                          | **Output**                                      |
| ------------------------- | ---------------------------------------------------------------------------------------- | ----------------------------------------------- |
| **Console Analysis**      | Simple Python script to analyze Iris dataset with `pandas` and visualize with `seaborn`. | Dataset overview, summary statistics, pair plot |
| **Streamlit Integration** | Modified script to display dataset, stats, and plot interactively in Streamlit.          | Interactive Streamlit app                       |
| **Deployment**            | Set up GitHub repo, add `requirements.txt`, deploy to Streamlit Cloud.                   | Deployed app link                               |

---

### **6. Deployment Pipeline**

#### Steps:

1. **Set Up GitHub Repository**: Push code and sample datasets to GitHub.

2. **Create `requirements.txt`**:

   ```
   streamlit
   pandas
   matplotlib
   ```

3. **Deploy on Streamlit Cloud**:
   - Log in to [Streamlit Cloud](https://streamlit.io/).
   - Link GitHub repository and deploy the app.
  
---

## Thanks for Visiting 😄

- Drop a 🌟 if you find this repository useful.<br><br>
- If you have any doubts or suggestions, feel free to reach me.<br><br>
📫 How to reach me:  &nbsp; [![Linkedin Badge](https://img.shields.io/badge/-madhurima-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/madhurima-rawat/) &nbsp; &nbsp;
<a href ="mailto:rawatmadhurima@gmail.com"><img src="https://github.com/madhurimarawat/Machine-Learning-Using-Python/assets/105432776/b6a0873a-e961-42c0-8fbf-ab65828c961a" height=35 width=30 title="Mail Illustration" alt="Mail Illustration📫" > </a><br><br>
- **Contribute and Discuss:** Feel free to open <a href= "https://github.com/madhurimarawat/Agile-Sprint-and-Iris-Data-Explorer/issues">issues 🐛</a>, submit <a href = "https://github.com/madhurimarawat/Agile-Sprint-and-Iris-Data-Explorer/pulls">pull requests 🛠️</a>, or start <a href = "https://github.com/madhurimarawat/Agile-Sprint-and-Iris-Data-Explorer/discussions">discussions 💬</a> to help improve this repository!
