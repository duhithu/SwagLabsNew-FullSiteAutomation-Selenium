# Swag Labs Test Automation Project

This repository contains an automated testing suite developed for the "Swag Labs" web portal using Java, Selenium WebDriver, and TestNG. The objective of this project is to apply advanced software quality assurance methodologies by implementing end-to-end automation scripts to validate various user workflows in a simulated real-world e-commerce application.

---

## 🛠️ Technology Stack & Tools

* **Programming Language:** Java
* **Automation Tool:** Selenium WebDriver
* **Testing Framework:** TestNG
* **Build/IDE Environment:** IntelliJ IDEA Community Edition
* **Web Browser:** Google Chrome (Chrome Driver)
* **Reporting/Screenshots:** Apache Commons IO (`FileUtils` for taking error screenshots)

---

## 🧪 Automated Test Suite Coverage

The project covers a total of 9 critical test scenarios ranging from core authentication checks to complete transactional happy paths:

### 1. Authentication Scenarios (`SwagLabsNew.java`)
* **Valid Login:** Validates access using standard user credentials.
* **Invalid Username:** Ensures the system correctly rejects unrecognized usernames.
* **Invalid Password:** Ensures proper error notification for incorrect password attempts.
* **Empty Credentials:** Checks validation behavior when fields are left blank.
* **Locked Out User:** Assures specific restriction messages are handled for restricted users.

### 2. UI & Inventory Validation (`SwagLabsNew_VerifyTheProductPage.java`)
* Verifies successful redirection to the main inventory screen and ensures the presence of core header elements like the product banner.

### 3. Side Navigation Workflows (`SwagLabsnew_OpenLeftSideMenuAndCloseIt.java`)
* Focuses on element visibility and menu interactability by opening the primary burger drawer menu and then closing it via its cross indicator button.

### 4. Direct Cart Interactions (`SwagLabsNew_AddToCardAndRemove.java`)
* Directly tests button state toggles on the main products display page by interacting with the "Add to Cart" and "Remove" triggers.

### 5. Product Detailed Cards Validation (`SawgLabsNew_ProductCardTest.java`)
* Navigates into individual item focus pages to verify detail layouts (names, descriptions, image paths, and pricing data) along with returning to the store catalogue.

### 6. Cart Management Operations (`SwagLabsNew_AddToTheCardPageAndRemoveItInCart.java`)
* Evaluates adding items to the basket, loading the dedicated Cart Page, validating item string descriptors, currency markers (`$`), and executing explicit items deletion inside the cart wrapper.

### 7. Checkout Workflows (`SawgLabsNew_CheckOutWithFinal.java`)
* Directs standard delivery input forms submission and ensures mathematical precision checks on the financial calculation formula (Item Total + System Tax = Gross Total Price).

### 8. Transactional Cancellations (`SawgLabsNew_CheckOutWithCancel.java`)
* Completes initial checkout form operations but interacts with the 'Cancel' navigation button to ensure returning states reset correctly back to the core inventory window.

### 9. Complete End-to-End Happy Path (`SwagLabsNew_ThankYou.java`)
* Exercises the full e-commerce flow: authenticates the session, assigns an item to the cart, proceeds through standard receipt formatting, confirms accurate tax math, executes final processing, and asserts the successful appearance of the `"THANK YOU FOR YOUR ORDER"` header flag.

---

## 📁 Repository Structure

```text
├── src/
│   └── StandardSelenium/
│       ├── 1.SwagLabsNew-4logintest.java
│       ├── 2.SwagLabsNew_VerifyTheProductPage.java
│       ├── 3.SwagLabsnew_OpenLeftSideMenuAndCloseIt.java
│       ├── 4.SwagLabsNew_AddToCardAndRemove.java
│       ├── 5.SawgLabsNew_ProductCardTest.java
│       ├── 6.SwagLabsNew_AddToTheCardPageAndRemoveItInCart.java
│       ├── 7.SawgLabsNew_CheckOutWithFinal.java
│       ├── 8.SawgLabsNew_CheckOutWithCancel.java
│       └── 9.SwagLabsNew_ThankYou.java
└── README.md
