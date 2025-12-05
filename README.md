# 🚀 Project: Search Function API Testing with Postman

![Tool](https://img.shields.io/badge/Tool-Postman-orange)
![Type](https://img.shields.io/badge/Type-API%20Testing-blue)

## 1. Introduction
This project focuses on verifying the backend logic of the **Search Module** using **Postman**.
The goal is to ensure the API returns correct data, handles invalid parameters gracefully, and meets performance benchmarks.

* **Tester:** Luong Manh Hung
* **Module:** Search Functionality
* **Tools:** Postman, Swagger (if any)

## 2. Test Scope (Phạm vi kiểm thử)
I performed API testing for the following scenarios:
* ✅ **Verify Status Codes:** 200 (OK), 400 (Bad Request), 404 (Not Found), 500 (Server Error).
* ✅ **Response Validation:** Verify that the JSON response body contains relevant search results.
* ✅ **Performance:** Ensure API response time is under 500ms.
* ✅ **Query Parameters:** Test with valid keywords, empty keywords, and special characters.

## 3. Project Artifacts (Tài liệu dự án)
You can download and import the files below to review my work:

| File Name | Description | Format |
| :--- | :--- | :--- |
| **[📄 Test Report](./TestPlan_Search_Module.docx)** | Detailed report including test cases, evidence, and conclusion. | Word/PDF |
| **[📊 Search Test Cases](./TestCases_Search_Function.xlsx)** | Detailed test scenarios for Search logic. | XLSX |

## 4. Sample Test Case (Example)
**Scenario:** Search with a valid keyword "Laptop".

* **Endpoint:** `GET /api/v1/products/search?q=Laptop`
* **Expected Result:**
    * Status Code: `200 OK`
    * Response Time: `< 200ms`
    * Body: List of products containing "Laptop".

---
### 📬 Contact
* **GitHub:** [hungwick](https://github.com/hungwick)
* **Email:** luonghung6998@gmail.com
