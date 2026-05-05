# Security-Issues-Tracker


# 📌 Overview
This project is a Power Apps Canvas App designed to track and manage technical issues.  
Data is stored in a SharePoint list, and the app leverages formulas and connectors to provide a dynamic, user-friendly experience.  


# 🚀 Features
 Issue List Panel 
  - Displays all logged issues with titles and short descriptions.  
  - Example: Phone battery issue, Laptop heating issue.  

  Issue Detail Form
  - Fields include:
    - Priority (Low, Medium, High)
    - Assigned To (connected via Office 365 Users connector to show organization members)
    - Issue Date
    - Remarks
    - Related Issue (link to another ticket)
    - Closing Date
    - Attachments (upload supporting files)

  Formulas & Logic 
  - Power Apps formulas used for validation, filtering, and dynamic behavior.  
  - Example: auto-populating dates, conditional formatting based on priority, etc.  

  Action Buttons 
  - Submit: Save or update issue details in SharePoint.  
  - Cancel: Discard changes.  


# 🛠️ Tech Stack
- Platform: Microsoft Power Apps (Canvas App)  
- Data Source: SharePoint List  
- Connector: Office 365 Users (for organizational directory)  
- Logic: Power Apps formulas  

---

# 📂 Project Structure
/project-root
│── /sharepoint-list   # Stores issue data
│── /canvas-app        # Power Apps UI and logic
│── README.md          # Documentation



#📖 Usage
1. Log an Issue
   - Enter issue title and description in the list panel.  

2. Manage Issue Details
   - Fill in priority, assignee (from Office 365 directory), and remarks.  
   - Attach files if necessary.  

3. Submit or Close  
   - Save updates with the Submit button (writes to SharePoint).  
   - Mark issue as resolved by setting a closing date.  

✅ Future Enhancements
- Role-based access control (admins vs users).  
- Automated notifications via Power Automate.  
- Dashboard with analytics (open vs closed issues).  
- Integration with Teams for collaboration.  

📜 License
This project is licensed under the MIT License.  
Feel free to use and modify it for your own needs.
