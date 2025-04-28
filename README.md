# Manual-Testing-on-Daraz
# Daraz Website Test Cases Documentation

This repository contains comprehensive test case documentation for the Daraz e-commerce platform. The Excel file covers functional, UI, and usability testing scenarios across various pages and features of the website.

## 📁 Excel File Structure

### Sheets Overview
| Sheet Name             | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Test Case**          | Template for test cases (mostly empty rows).                                |
| **Home Page**          | Tests for homepage elements (layout, responsiveness, navigation, banners). |
| **Sign Up Page**       | UI, performance, and validation tests for user registration.               |
| **Search**             | Functional tests for search bar behavior and results.                      |
| **Catagory** (Category)| Cart management tests (add/remove items, quantity, coupons, checkout).     |
| **Cart**               | UI and functional tests for cart operations.                               |
| **Payment**            | Payment method validations (Credit Card, bKash, COD, EMI).                 |
| **Daraz Login**        | Login scenarios (valid/invalid credentials, OTP, social login).            |
| **Daraz Reset Login**  | Password reset and OTP verification workflows.                             |
| **Daraz Profile**      | Profile editing, address book, vouchers, orders, and cancellations.        |
| **Bug Report**         | *(Empty)* Placeholder for tracking reported defects.                       |
| **req analysis**       | Q&A clarifying requirements (e.g., "Add to Cart" button behavior).         |

---

## 📝 Key Columns in Test Case Sheets
- **Test ID**: Unique identifier for each test case.
- **Test Scenario**: Description of the functionality being tested.
- **Priority**: Criticality level (P1/P2/P3 or High/Medium/Low).
- **Browser**: Supported browsers (Chrome, Firefox, etc.).
- **Prerequisites**: Conditions required before executing the test.
- **Test Steps**: Step-by-step actions to perform.
- **Test Data**: Input values or mock data for testing.
- **Expected Result**: Anticipated outcome.
- **Actual Result**: *(To be filled during execution)*.
- **Status**: Passed/Failed/Pending.
- **Defects**: Linked defect IDs (if any).
- **Ticket ID**: Associated Jira/Trello tickets.

---

## 🛠️ Requirements Clarification (from `req analysis`)
| Question                                                                 | Answer                                                                       |
|--------------------------------------------------------------------------|------------------------------------------------------------------------------|
| Where should the "Add to Cart" button appear?                           | On the product list page and product details page.                          |
| What is the activity journey after adding to cart?                      | Show a modal with cart details and redirect to the cart page.               |
| How to handle "Exceed Quantity" scenarios?                              | Display a modal with the message: "Exceed quantity".                        |
| Behavior for out-of-stock items?                                        | Hide or disable the "Add to Cart" button.                                   |

---

## 🚀 Usage Instructions
1. **Navigate Sheets**: Use the sheet tabs to access test cases for specific features.
2. **Update Status**: Mark tests as `Passed`/`Failed` in the **Status** column during execution.
3. **Report Defects**: Log defects in the **Bug Report** sheet with details (not yet populated).
4. **Track Progress**: Filter by **Priority** or **Status** to monitor testing progress.

---

## 👥 Contributing
1. Fork the repository.
2. Add new test cases or update existing ones in the relevant sheet.
3. Ensure all columns are filled accurately.
4. Submit a pull request for review.

---
