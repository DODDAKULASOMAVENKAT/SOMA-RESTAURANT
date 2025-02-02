# Description:
Developed a web-based Student & Staff Management System to efficiently manage student and staff login functionalities, dynamically generate student details, and provide staff with controlled access to student information.
# *Frontend:*  
- *HTML* – Used to structure the web pages (Login Page, Student Dashboard, and Staff Dashboard).  
- *CSS* – Used for styling, including table designs, dark mode functionality, and layout customization.  
- *JavaScript* – Used for:  
  - Handling login authentication for students and staff.  
  - Storing and retrieving user data via localStorage.  
  - Dynamically generating student details such as CGPA, attendance, and email.  
  - Implementing the dark mode toggle.  

# *Data Handling (Without Backend Database):*  
- *JavaScript Local Storage* – Used to temporarily store student and staff login details.  
- *Random Data Generation* – Used for:  
  - Assigning random student names from a predefined list.  
  - Generating random CGPA and attendance percentages.  
  - Creating a timetable based on the selected branch.  

# *Features Implemented Using These Technologies:*  
✅ *Student Login:* Displays only the logged-in student's details.  
✅ *Staff Login:* Allows staff to view a list of students from their branch.  
✅ *Staff Dashboard:* Lists students with a "Click Here" button to view details.  
✅ *Dark Mode Toggle:* Saves user preference across sessions.  
✅ *Dynamic Data Generation:* Creates student details (CGPA, email, attendance, timetable) at runtime.  

Since the project does not use a backend (Python, Flask, or a database), all data is managed locally using JavaScript.
