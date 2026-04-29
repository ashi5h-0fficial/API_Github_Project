# 🚀 GitHub API Testing Project

![GitHub](https://img.shields.io/badge/API-GitHub-blue?logo=github)
![Testing](https://img.shields.io/badge/Testing-Automation-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

This project contains **API test cases for GitHub APIs**, designed to validate various functionalities such as repository management, user data retrieval, and authentication.

The goal of this project is to ensure:
- ✅ API reliability  
- ✅ Data accuracy  
- ✅ Proper response handling  
- ✅ Status code validation  

---

## 🧑‍💻 Author

**Ashish Soni**

---

## 🛠️ Tech Stack

- Java  
- Selenium (if integrated)  
- REST Assured  
- TestNG / JUnit  
- Maven  
- Postman (for initial testing)  

---

## 📂 Project Structure

```
📁 GitHub-API-Testing
 ┣ 📂 src
 ┃ ┣ 📂 test
 ┃ ┃ ┗ 📜 TestCases.java
 ┃ ┣ 📂 main
 ┃ ┃ ┗ 📜 Utilities.java
 ┣ 📂 test-data
 ┃ ┗ 📜 testData.xlsx / csv
 ┣ 📜 pom.xml
 ┣ 📜 README.md
```

---

## 🔍 Test Scenarios Covered

- 🔐 Authentication validation  
- 📦 Repository creation & deletion  
- 👤 User profile API testing  
- 📄 Response schema validation  
- ⏱️ Response time checks  
- ❌ Negative test scenarios  

---

## ▶️ How to Run

1. Clone the repository:
```
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to project folder:
```
cd your-repo-name
```

3. Run tests using Maven:
```
mvn clean test
```

---

## 📊 Sample API Request

```
GET https://api.github.com/users/{username}
```

### ✔️ Expected Response:
- Status Code: `200 OK`
- Valid JSON body
- Correct user details

---

## 📸 Sample Output

```
Status Code: 200
Response Time: < 2s
Validation: PASSED ✅
```

---

## 📈 Future Enhancements

- 🔄 CI/CD integration (GitHub Actions)
- 📊 Reporting (Extent Reports / Allure)
- 🔐 Token-based secure authentication handling
- 🧪 Data-driven testing improvements

---

## 🤝 Contribution

Contributions are welcome!  
Feel free to fork this repo and raise a pull request.

---

## ⭐ Support

If you like this project, don’t forget to **star ⭐ the repository**!
