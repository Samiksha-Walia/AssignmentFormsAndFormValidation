
# 🧾 React Form with Custom Validation – User Registration App

A fully functional **React form** built without any third-party libraries. The app provides field-level validation using regular expressions, dynamic error messages, disabled submission until valid, and post-submission redirection to a new route displaying all entered information.

> ⚠️ *This project is built for educational and practical learning purposes – showcasing pure React form handling and validation techniques.*



## ✅ Features

✔️ Input validation using regex (no external libraries)  
✔️ Error messages displayed below each invalid field  
✔️ Submit button disabled until all fields are valid  
✔️ Password show/hide toggle  
✔️ Country and City dropdowns (dependent logic ready)  
✔️ Redirects to new route with submitted data summary  
✔️ Clean and responsive layout  
✔️ Clear field-level state and validation logic



## 🧠 Fields with Validation

| Field          | Validation                                                                 |
|----------------|----------------------------------------------------------------------------|
| **First Name** | Required, letters only                                                     |
| **Last Name**  | Required, letters only                                                     |
| **Username**   | Required, alphanumeric (min 4 chars)                                       |
| **E-mail**     | Required, valid email format (e.g., user@example.com)                      |
| **Password**   | Required, min 6 characters, contains letters & numbers                     |
| **Phone No.**  | Required, Indian format: `+91 XXXXXXXXXX`                                  |
| **Country**    | Required, dropdown menu                                                    |
| **City**       | Required, dynamic based on country                                         |
| **PAN No.**    | Required, valid Indian PAN format (e.g., ABCDE1234F)                       |
| **Aadhar No.** | Required, exactly 12 digits                                                |



## 🛠 Tech Stack

| Layer         | Technology Used      |
|---------------|----------------------|
| **Frontend**  | React.js             |
| **Routing**   | React Router DOM     |
| **State Mgmt**| useState, useEffect  |



## 🚀 Getting Started

### Prerequisites

* Node.js (v16+)
* npm or yarn

### Installation Steps

```bash
# Clone the repository
git clone https://github.com/Samiksha-Walia/AssignmentFormsAndFormValidation.git

# Navigate to the project folder
cd AssignmentFormsAndFormValidation

# Install dependencies
npm install

# Run the local server
npm run dev
```

Visit `http://localhost:5173` to interact with the form.



## 🧪 Testing the App

1. 🖊️ Try submitting the form without entering anything — errors will be displayed.
2. ✍️ Fill all fields correctly to enable the **Submit** button.
3. 👁️ Toggle password visibility using the "Show/Hide" feature.
4. 📞 Enter a phone number with `+91` and 10 digits.
5. 📄 On successful form submission, you will be redirected to a new route showing the entered details.
6. 🌏 Dropdown for Country and City allows for scalable country-city mapping logic.




## 👩‍💻 Author

**Samiksha Walia**
[GitHub](https://github.com/Samiksha-Walia) • [LinkedIn](https://linkedin.com/in/samiksha-walia)



## ⭐️ Support This Project

If this helped you learn React form validation, please consider giving the repo a ⭐️.

> 📝 *Built without libraries to demonstrate how to handle form validation using core React and JavaScript.*

