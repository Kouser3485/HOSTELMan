
---

```markdown
# Hostel Management System

This is a complete web-based hostel management system that helps manage daily operations in a student hostel. It supports role-based access for Chief Warden, Wardens, Students, and Security Staff.

The system allows easy room and block allocations, student complaint handling, leave approvals, security tracking, and direct communication with parents. It is built using Node.js, Express, MongoDB for the backend, and HTML, CSS, and JavaScript for the frontend.

## Key Features

### Chief Warden
- Assigns hostel blocks and rooms to different wardens.

### Warden
- Allocates rooms to students.
- Approves or rejects student leave requests.
- Views and resolves complaints submitted by students.
- Sends SMS updates to parents using Twilio API.
- Keeps track of student and staff entry/exit through the security log.

### Student
- Views assigned room details.
- Submits complaints to the warden.
- Applies for leave.
- Reports whether their room has been cleaned on a given day.

### Security
- Maintains a logbook of students, staff, and visitors going in and out.
- Records details like name, reason for going out, time left, and expected return time.

## Technology Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js with Express.js  
- **Database**: MongoDB  
- **APIs Used**: Twilio API for sending SMS messages to parents

## Project Structure

```

HOSTELMan/
├── public/             # Frontend assets like CSS and JS
├── routes/             # Route handlers
├── models/             # Database schemas
├── views/              # HTML/EJS templates (if used)
├── .env                # Environment configuration
├── server.js           # Main server file
├── package.json        # Project and dependency details

```

## How to Run the Project

1. **Clone the Repository**
```

git clone [https://github.com/Kouser3485/HOSTELMan.git](https://github.com/Kouser3485/HOSTELMan.git)
cd HOSTELMan

```

2. **Install Required Packages**
```

npm install

```

3. **Set Up Environment Variables**

Create a `.env` file in the root folder with the following content:
```

MONGODB\_URI=your\_mongodb\_connection\_string
TWILIO\_SID=your\_twilio\_sid
TWILIO\_AUTH\_TOKEN=your\_twilio\_auth\_token

```

4. **Start the Server**
```

npm start

```

5. **Access the App in Your Browser**

Visit:
```

[http://localhost:3000](http://localhost:3000)

```

## About the Project

This project was developed to digitally manage and simplify various tasks in a student hostel. From handling rooms and complaints to tracking leave and communicating with parents, the system is designed to make hostel operations smooth and efficient.

## License

This project is open-source and released under the [MIT License](LICENSE).

## GitHub Repository

[https://github.com/Kouser3485/HOSTELMan](https://github.com/Kouser3485/HOSTELMan)
```

---
