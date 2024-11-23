## Email Sequence Builder - README

This project is a web application designed for building and scheduling automated email marketing sequences using a visual interface. 

### Technologies Used

* **Frontend:** React, React Flow library
* **Backend:** Node.js, Express.js, MongoDB (MERN Stack)
* **Scheduling:** Agenda
* **Email Sending:** Nodemailer

### Functionalities

* **Visual Flowchart:** Users can create email sequences using a drag-and-drop interface with nodes for:
    * **Cold Email:** Define email content for sending cold outreach emails.
    * **Wait/Delay:** Schedule delays between emails in the sequence.
    * **Lead Source:** Capture information on where the lead originated (optional).
* **Scheduling:** Saving the flowchart automatically schedules emails based on wait time defined in "Wait/Delay" nodes.
* **API:** A backend API allows scheduling individual emails with defined content, subject, and recipient.

### Bonus Features (Not Implemented Yet)

* **Authentication:** User login and access control for secure usage.
* **Unit Tests:** Automated tests to ensure code functionality.
* **Documentation:** Comprehensive documentation for developers and users.
* **Deployment:** Deployment script and instructions for hosting on free platforms.

### Evaluation Criteria

This project will be evaluated based on the following criteria:

* **Functionality:** Meets all outlined functionalities, including API access.
* **Code Quality:** Clean, well-commented, and modular codebase.
* **User Experience:** Intuitive and user-friendly interface with clear instructions.
* **Scalability:** Architecture and database design consider future growth.

### Getting Started

1. Clone this repository: `git clone https://github.com/<your-username>/email-sequence-builder.git`
2. Install dependencies: `npm install`
3. Configure database and email service credentials (see configuration files).
4. Run the application: `npm start`

**Note:** This project is currently under development. The bonus features mentioned above are not yet implemented. 

### Resources

* React Flow: [https://reactflow.dev/learn](https://reactflow.dev/learn)
* Agenda: [https://github.com/agenda/agenda](https://github.com/agenda/agenda)
* Nodemailer: [https://www.nodemailer.com/](https://www.nodemailer.com/)
* Example Application (SalesBlink): [https://run.salesblink.io/signup](https://run.salesblink.io/signup)

### Contributing

We encourage contributions to this project. Feel free to fork the repository and submit pull requests for improvements.