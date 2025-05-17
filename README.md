

---

````markdown
# Hostel Management System

This is a web-based system designed to simplify hostel management. It helps hostel staff and students manage everything from room allocations to complaints, leaves, daily cleaning updates, and security logs. It also allows communication with parents using SMS.

The system is built using Node.js, Express, MongoDB, HTML, CSS, and JavaScript. It supports role-based access for Chief Warden, Warden, Students, and Security Staff.

---

## Main Features

### Chief Warden
- Assigns blocks and rooms to each warden.

### Warden
- Allocates rooms to students in the assigned blocks.
- Approves or rejects leave requests submitted by students.
- Views and resolves complaints sent by students.
- Sends updates to parents using the Twilio SMS API.
- Monitors security logs of who is going out and coming in.

### Student
- Can view room details.
- Submit complaints to the assigned warden.
- Apply for leave.
- Report whether their room was cleaned today.

### Security
- Maintains entry and exit records of students, staff, and visitors.
- Logs name, reason for leaving, time out, and expected return time.

---

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js with Express  
- **Database**: MongoDB  
- **SMS Communication**: Twilio API  

---

## Folder Structure

- `public/` – Frontend files (CSS, JS, images)  
- `routes/` – Defines all backend routes  
- `models/` – Mongoose schemas for database collections  
- `views/` – HTML or EJS templates (if used)  
- `.env` – Contains environment variables (not included in repo)  
- `server.js` – Main backend server file  
- `package.json` – Lists project dependencies and info  

---

## How to Run the Project

**1. Clone the Repository**
```bash
git clone https://github.com/Kouser3485/HOSTELMan.git
cd HOSTELMan
````

**2. Install Required Packages**

```bash
npm install
```

**3. Set Up Environment Variables**

Create a file named `.env` in the root folder and add your credentials:

```env
MONGODB_URI=your_mongodb_connection_string
TWILIO_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
```

**4. Run the Application**

```bash
node server.js
```

**5. Open in Browser**

Go to this URL to view the app:

```
http://localhost:3000
```

---

## About This Project

This project was built to manage hostel operations efficiently in real-time. It covers everything from assigning rooms to students, managing complaints and leaves, and maintaining logs for security. It also ensures parents can be kept in the loop through automated messages.

---

