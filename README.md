# AWS-Amplify-Project
PowerOfMath
# Power of Math App

A simple AWS-powered web application that performs math operations using **AWS Lambda, API Gateway, DynamoDB, and Amplify**.

🔗 **Live Demo:** [https://dev.d1r5zc38mwbss3.amplifyapp.com/](https://dev.d1r5zc38mwbss3.amplifyapp.com/)

---

## 🚀 What I Learned / Steps I Took

1. **Frontend with AWS Amplify**
   - Created a basic `index.html` file using **Notepad++** with a simple HTML structure.
   - Used **AWS Amplify** to host and deploy the static site.

2. **Backend with AWS Lambda**
   - Built a Lambda function to handle a **math calculation** (power/exponent).
   - Connected the function to **API Gateway** so it could be invoked via HTTP requests.

3. **API Gateway + CORS**
   - Configured **API Gateway** to call the Lambda function.
   - Enabled **CORS** so the frontend could communicate with the backend without browser errors.

4. **Database with DynamoDB**
   - Used **Amazon DynamoDB** to store operation results.
   - Updated Lambda’s IAM role to allow **`dynamodb:PutItem`** access.

5. **Integration**
   - Connected Amplify (frontend) → API Gateway (API) → Lambda (logic) → DynamoDB (storage).
   - Tested the full workflow successfully.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, AWS Amplify
- **Backend:** AWS Lambda (Python)
- **API Management:** Amazon API Gateway
- **Database:** Amazon DynamoDB

---

## 📌 Notes
- This project was built entirely in the **AWS Console**.  
- Goal: practice **cloud integration**, not just coding.  
- Challenges I solved:
  - Debugged missing **CORS** configuration.
  - Fixed **IAM role permissions** for DynamoDB.
  - Corrected file naming issues in Amplify to avoid `404` errors.

---

## 📚 Next Steps
- Improve frontend (add CSS & JS for interactivity).  
- Add more math functions (addition, subtraction, etc.).  
- Automate deployments using **GitHub → Amplify CI/CD pipeline**.
