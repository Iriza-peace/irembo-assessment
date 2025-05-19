<<<<<<< HEAD
"This is irembo assessment "
=======

## **Test Coverage** 📌
git
This project has been tested using **Postman** to verify the API functionality and ensure that the email service works correctly.  

### ** API Endpoint Testing**  
**POST `/api/v1/registerDetails`**  

- **Valid Request**:  
  - Sent a properly formatted JSON payload.  
  - Verified that the response status is `200 OK`.  
  - Checked the email inbox to confirm receipt.
    
- **Invalid Request**:  
  - Tested missing request body.  
  - Ensured the API returns `400 Bad Request` for incomplete data. (ex: invalid email)
      
- **Error Handling**:  
  - Simulated an incorrect email service configuration.  
  - Verified that the API returns a `500 Internal Server Error`.  

### **2️⃣ End-to-End Testing Using Postman**  

- **Form Submission Simulation**:  
  - Sent API requests with real-world test data.  
  - Confirmed that the email is correctly formatted and received.  

### **Tools Used** 🛠️  
✅ **Postman** for manual API testing.  

Frontend Testing

1 Form Submission Testing 📝
✅ Test Case 1: Valid Submission

Filled out all required fields correctly.
Clicked the submit button.
Verified that the request was sent to the API.
Checked if a success message appeared.
Confirmed that the email was received in the provided inbox.
✅ Test Case 2: Invalid Submission

Left some required fields empty and tried to submit.
Ensured that validation messages appeared.
Checked that no request was sent to the backend.
✅ Test Case 3: API Failure Handling

Simulated a server error (e.g., turned off the backend).
Submitted the form and verified that the UI displayed an appropriate error message.
2️⃣ UI & Responsiveness Testing 📱💻
✅ Tested the layout on different screen sizes.
✅ Ensured that the form remained functional on mobile devices.

Tools Used 🛠️
✅ Browser Developer Tools for manual frontend debugging.



>>>>>>> d57ca2712575af58428b17b674cde727500302f9
