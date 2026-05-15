# Student Enrollment Form using JsonPowerDB

A responsive Student Enrollment Form built using HTML, CSS, JavaScript, jQuery, and JsonPowerDB (JPDB).
This project performs real-time database operations such as Save, Update, Fetch, and Reset using JPDB APIs.

---

## 🚀 Features

* Check whether Student Roll Number already exists
* Save new student records into JsonPowerDB
* Update existing student records
* Reset form instantly
* Dynamic field enable/disable functionality
* Input validation for all fields
* Responsive and clean UI

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* jQuery
* JsonPowerDB (JPDB)

---

## 📂 Database Details

* **Database Name:** SCHOOL-DB
* **Relation/Table Name:** STUDENT-TABLE
* **Primary Key:** Roll-No

---

## 📋 Input Fields

* Roll No
* Full Name
* Class
* Birth Date
* Address
* Enrollment Date

---

## ⚡ Functional Flow

### 1. Initial State

* Only Roll No field is enabled
* Save and Update buttons are disabled

### 2. Submit Roll Number

* If Roll No does not exist:

  * Empty form opens
  * Save button enabled
* If Roll No already exists:

  * Existing student data loads automatically
  * Update button enabled

### 3. Save Record

* Stores new student data into JsonPowerDB

### 4. Update Record

* Updates existing student data in JsonPowerDB

### 5. Reset Form

* Clears all fields
* Returns form to initial state

---

## 📸 Project Preview
<h2>Inital Page</h2>
<h5>Enter Roll Number (Primary Key)</h5>
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/02ec2a6d-63fd-43f0-987e-56eaf20a9e0b" />

<h2>Student Exists</h2>
<h5>All the Student Information has been put into the respective fields</h5>
<h5>You can either just View or Update the details</h5>
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/cb962927-31f7-4db1-b496-349500a0bfd8" />

<h4>After Updatation</h4>
<img width="937" height="502" alt="image" src="https://github.com/user-attachments/assets/be06aace-6505-4e9c-bd3b-22667a4dcaea" />


<h2>If Student don't Exists</h2>
<h5>Then it's a new entry and the following Student's data is inserted into the DataBase</h5>
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/d4b756d9-5a58-41ff-832c-3f5761d53905" />
<h5>Now you can enter the details</h5>
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/438bbb72-fdf4-4cf8-bada-8467291ac377" />

<h2>JsonPowerDB</h2>
<img width="952" height="459" alt="image" src="https://github.com/user-attachments/assets/1ef590d4-f617-4115-a6eb-f5dcec5912a4" />

<h4>After Updating Divya's Details</h4>
<img width="955" height="422" alt="image" src="https://github.com/user-attachments/assets/81986bc4-bb4a-4b20-8d12-38d2c9f3030c" />

---

## 🔗 JsonPowerDB APIs Used

* GET_BY_KEY
* PUT
* SET (UPDATE)

---

## 🧠 Learning Outcomes

Through this project, I learned:

* CRUD operations using JsonPowerDB
* AJAX request handling
* Dynamic form handling
* jQuery DOM manipulation
* API integration
* Database interaction using REST APIs

---

## ▶️ How to Run

1. Clone the repository
2. Open the project folder
3. Run using Live Server or open `index.html`
4. Ensure internet connection for JPDB API access

---

## 👨‍💻 Author

Deepesh Nehra

B.Tech CSE (AI & ML)
<br>
Full Stack Developer
