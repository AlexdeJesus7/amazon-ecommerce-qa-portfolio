\# Functional Requirements – Amazon E-commerce Project

\#\# 1\. Purpose  
This document describes the functional requirements identified during the analysis and testing of the Amazon e-commerce purchase flow.    
The requirements were derived from real system behavior observed in the production environment.

\---

\#\# 2\. Scope  
This document covers the following flows:  
\- Product search  
\- Product details and variation selection  
\- Shopping cart  
\- Checkout (partial flow, without order completion)

\---

\#\# 3\. Functional Requirements

\#\#\# 3.1 Search

FR-01 — The system shall allow users to search for products using the search bar    
FR-02 — The system shall allow users to apply filters to search results    
FR-03 — The system shall allow users to select a product from the search results    
FR-04 — The system shall redirect users to the selected product detail page  

\---

\#\#\# 3.2 Product

FR-05 — The system shall display product details, including name, price, images, ratings, and availability    
FR-06 — The system shall allow users to select available product variations (color, size, storage, etc.)    
FR-07 — The system shall display alternative sellers for the same product when applicable    
FR-08 — The system shall display the product price per seller    
FR-09 — The system shall display shipping costs associated with each seller    
FR-10 — The system shall allow users to adjust product quantity before adding it to the cart    
FR-11 — The system shall allow users to add available products to the shopping cart  

\---

\#\#\# 3.3 Cart

FR-12 — The system shall allow access to the shopping cart through the cart icon    
FR-13 — The system shall redirect users to the cart page    
FR-14 — The system shall display all products added to the cart    
FR-15 — The system shall display the quantity of each product    
FR-16 — The system shall allow quantity adjustment within valid limits    
FR-17 — The system shall display the cart subtotal    
FR-18 — The system may display informational messages related to shipping eligibility    
FR-19 — The system shall allow users to proceed to checkout from the cart  

\---

\#\#\# 3.4 Checkout

FR-20 — The system shall require user authentication before accessing checkout    
FR-21 — The system shall allow users to select or add a delivery address    
FR-22 — The system shall validate delivery address compatibility with selected products    
FR-23 — The system shall allow users to select a payment method    
FR-24 — The system shall enforce mandatory selection of a shipping option    
FR-25 — The system shall allow users to proceed through checkout steps until order confirmation    
\> Note: actual order placement and payment processing are out of scope for this project.

\---

\#\# 4\. Notes  
\- Requirements were identified through black-box testing.  
\- No internal system documentation was available.  
\- Detailed behaviors are documented in:  
  \- Test Report  
  \- Bug Report  
  \- Test Observations

\---

\#\# 5\. Related Documents  
\- Test Plan  
\- Test Scenarios  
\- Test Cases  
\- Test Report  
\- Bug Report  
\- Test Observations