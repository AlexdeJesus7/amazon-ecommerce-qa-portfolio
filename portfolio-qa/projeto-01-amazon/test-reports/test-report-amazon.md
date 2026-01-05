\# Test Report — Amazon E-commerce

\*\*Project:\*\* Amazon E-commerce – Purchase Flow    
\*\*Version:\*\* 1.0    
\*\*Date:\*\* 01/02/2026    
\*\*QA Engineer:\*\* Alex de Jesus    
\*\*Environment:\*\* Production (amazon.com)    
\*\*Test Type:\*\* Manual | Functional | Exploratory Testing  

\---

\#\# 1\. Objective

This Test Report aims to present the results of the testing cycle performed on the main Amazon e-commerce flows, focusing on functional behavior, business rules validation, and user experience during the purchase process.

The tests were executed simulating real end-user behavior.

\---

\#\# 2\. Test Scope

\#\#\# 2.1 Tested Features

\- Product search    
\- Product details visualization    
\- Product variation selection (color, memory, etc.)    
\- Add products to cart    
\- Update and remove cart items    
\- Subtotal and informational messages    
\- Checkout access    
\- User authentication    
\- Delivery address selection    
\- Payment method selection    
\- Mandatory shipping method selection    
\- Address-based delivery availability validation  

\#\#\# 2.2 Out of Scope

\- Actual purchase completion    
\- Payment processing    
\- Order shipment    
\- Performance testing    
\- Security testing    
\- Automated testing  

\---

\#\# 3\. Test Environment

| Item | Description |  
|----|----|  
| Platform | Web |  
| Browser | Google Chrome |  
| Operating System | Windows |  
| Environment | Production |  
| Account | Real user |  
| Location | Brazil and United States |

\---

\#\# 4\. Test Strategy

Tests were executed manually and exploratorily based on predefined functional scenarios.

Approaches applied:

\- Happy Path testing    
\- Business rules validation    
\- Negative testing based on system behavior    
\- Conditional testing (login, address, availability, variations)  

Expected results were refined according to real system behavior during execution.

\---

\#\# 5\. Execution Summary

| Flow | Executed Test Cases |  
|----|----|  
| Search | 5 |  
| Product | 4 |  
| Cart | 4 |  
| Checkout | 4 |  
| \*\*Total\*\* | \*\*17\*\* |

\*\*Overall Status:\*\*    
\- ✔ Passed: 17    
\- ❌ Failed: 0  

\*\*Note:\*\* Some negative test cases were adjusted after identifying preventive controls implemented by the platform.

\---

\#\# 6\. Test Evidence

Visual evidence (screenshots) was collected during test execution, including:

\- Address incompatibility messages    
\- Automatic adjustment of unavailable variations    
\- Items moved to “Saved for later”    
\- Mandatory validations during checkout    
\- Amazon Prime offer prior to checkout continuation  

\---

\#\# 7\. Test Notes

\- Invalid variation combinations are automatically prevented.    
\- Cart quantity cannot be manually typed.    
\- Minimum quantity removes the item from the cart.    
\- Shipping and taxes are displayed only at checkout.    
\- Checkout access requires user authentication.    
\- Address changes may make products unavailable.    
\- Checkout requires mandatory payment and shipping selection.

\---

\#\# 8\. Bugs Identified

No critical functional defects were identified during this test cycle.

An intermittent behavior was observed during the checkout process when transitioning from a guest session to an authenticated session. A generic error page was displayed once after login. Upon refresh, the system recovered and applied business rules, moving items to “Saved for later”.

This behavior was documented as a test observation.

\---

\#\# 9\. Identified Risks

\- Users may be confused when items move to “Saved for later”.    
\- Incorrect expectations regarding final prices before checkout.    
\- Automatic variation changes may go unnoticed by some users.

\---

\#\# 10\. Conclusion

The system demonstrated stable and consistent behavior throughout the testing cycle.    
Critical purchase flow functionalities were successfully validated with no functional defects.

This project provided an in-depth understanding of large-scale e-commerce business rules.