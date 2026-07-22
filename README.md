# Swag Labs Test Automation Project

## 📌 Overview

This repository contains an automated testing suite developed for the **Swag Labs** web application using **Java**, **Selenium WebDriver**, and **TestNG**.

The objective of this project is to apply software quality assurance and test automation practices by implementing end-to-end automated test cases that validate critical user workflows in a real-world e-commerce environment.

---

## 🛠️ Technology Stack

| Technology                         | Purpose                            |
| ---------------------------------- | ---------------------------------- |
| ☕ Java                             | Programming Language               |
| 🤖 Selenium WebDriver              | Web Automation                     |
| 🧪 TestNG                          | Test Framework                     |
| 💻 IntelliJ IDEA Community Edition | Development Environment            |
| 🌐 Google Chrome                   | Test Browser                       |
| 📸 Apache Commons IO               | Screenshot Capture & File Handling |

---

## 🚀 Automated Test Coverage

### 🔐 1. Authentication Scenarios

**File:** `SwagLabsNew.java`

✅ Valid Login
✅ Invalid Username Validation
✅ Invalid Password Validation
✅ Empty Credentials Validation
✅ Locked-Out User Validation

---

### 🛍️ 2. Product Page Verification

**File:** `SwagLabsNew_VerifyTheProductPage.java`

✅ Successful redirection to Inventory Page
✅ Product banner validation
✅ Header element verification

---

### ☰ 3. Side Navigation Menu Testing

**File:** `SwagLabsnew_OpenLeftSideMenuAndCloseIt.java`

✅ Open Burger Menu
✅ Verify Menu Visibility
✅ Close Menu Functionality

---

### 🛒 4. Add to Cart & Remove Actions

**File:** `SwagLabsNew_AddToCardAndRemove.java`

✅ Add Product to Cart
✅ Remove Product from Cart
✅ Button State Validation

---

### 📦 5. Product Details Validation

**File:** `SawgLabsNew_ProductCardTest.java`

✅ Open Product Details Page
✅ Verify Product Name
✅ Verify Description
✅ Verify Product Image
✅ Verify Pricing Information
✅ Navigate Back to Inventory

---

### 🛍️ 6. Cart Management Operations

**File:** `SwagLabsNew_AddToTheCardPageAndRemoveItInCart.java`

✅ Add Item to Cart
✅ Open Cart Page
✅ Verify Product Details
✅ Verify Currency Symbol ($)
✅ Remove Item from Cart

---

### 💳 7. Checkout Workflow

**File:** `SawgLabsNew_CheckOutWithFinal.java`

✅ Complete Checkout Form
✅ Verify Item Total
✅ Verify Tax Calculation
✅ Validate Final Total Formula

**Formula Checked:**

Item Total + Tax = Total Price

---

### ❌ 8. Checkout Cancellation

**File:** `SawgLabsNew_CheckOutWithCancel.java`

✅ Start Checkout Process
✅ Cancel Checkout
✅ Verify Return to Inventory Page

---

### 🎉 9. Complete End-to-End Purchase Flow

**File:** `SwagLabsNew_ThankYou.java`

✅ User Login
✅ Add Product to Cart
✅ Checkout Process
✅ Tax & Total Validation
✅ Order Completion
✅ Verify **"THANK YOU FOR YOUR ORDER"** Message

---

## 📁 Project Structure

```text
📦 SwagLabs-Test-Automation
│
├── 📂 src
│   └── 📂 StandardSelenium
│       ├── 1️⃣ SwagLabsNew-4logintest.java
│       ├── 2️⃣ SwagLabsNew_VerifyTheProductPage.java
│       ├── 3️⃣ SwagLabsnew_OpenLeftSideMenuAndCloseIt.java
│       ├── 4️⃣ SwagLabsNew_AddToCardAndRemove.java
│       ├── 5️⃣ SawgLabsNew_ProductCardTest.java
│       ├── 6️⃣ SwagLabsNew_AddToTheCardPageAndRemoveItInCart.java
│       ├── 7️⃣ SawgLabsNew_CheckOutWithFinal.java
│       ├── 8️⃣ SawgLabsNew_CheckOutWithCancel.java
│       └── 9️⃣ SwagLabsNew_ThankYou.java
│
└── 📄 README.md
```

---

## ▶️ How to Run

### Prerequisites

* ☕ Java JDK 8 or higher
* 🌐 Google Chrome
* 🚗 ChromeDriver
* 💻 IntelliJ IDEA
* 🧪 TestNG

### Steps

1. Clone the repository

```bash
git clone <repository-url>
```

2. Open the project in IntelliJ IDEA.

3. Configure ChromeDriver.

4. Install project dependencies.

5. Run the desired TestNG test class.

---

## 📊 Test Features

✨ Automated UI Testing
✨ Functional Validation
✨ End-to-End Workflow Testing
✨ Checkout Calculation Verification
✨ Error Handling Validation
✨ Screenshot Support for Failures
✨ Cross-Page Navigation Testing

---

## 🎯 Project Outcome

This automation suite successfully validates critical Swag Labs functionalities including:

* 🔐 User Authentication
* 🛍️ Product Browsing
* 🛒 Cart Management
* 💳 Checkout Processing
* 🎉 Order Completion

The project demonstrates practical implementation of Selenium WebDriver automation using TestNG and follows structured software testing practices for web applications.

---

https://github.com/duhithu
