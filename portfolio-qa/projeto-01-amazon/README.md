\# QA Portfolio — Amazon E-commerce Project

This repository contains a Quality Assurance portfolio project focused on manual and exploratory testing of a real production e-commerce platform (Amazon), covering the complete purchase flow.

The objective of this project is to demonstrate practical QA skills, analytical thinking, and professional test documentation based on real system behavior and inferred business rules.

\---

\#\# 📌 Project Overview

\- \*\*Application tested:\*\* Amazon (E-commerce platform)  
\- \*\*Environment:\*\* Production  
\- \*\*Role:\*\* QA Tester  
\- \*\*Test approach:\*\* Black-box testing  
\- \*\*Test focus:\*\* Purchase flow  
\- \*\*Test types:\*\* Manual, Functional, Exploratory  
\- \*\*Documentation languages:\*\* English (en-US) and Portuguese (pt-BR)

\---

\#\# 🧪 Scope of Testing

The following user flows were tested:

\- Product search and filtering  
\- Product details visualization  
\- Product variations selection (color, size, storage, etc.)  
\- Adding products to the cart  
\- Cart update and item management  
\- Subtotal calculation and informational messages  
\- Checkout access  
\- User authentication  
\- Delivery address selection  
\- Shipping option validation  
\- Payment method selection  
\- Product availability based on delivery address

\---

\#\# 🚫 Out of Scope

\- Real order completion  
\- Payment processing  
\- Order shipment  
\- Performance testing  
\- Security testing  
\- Automated test execution

\---

\#\# 🧪 Notable Test Observations

During checkout testing, an intermittent behavior was observed when transitioning from a guest cart to an authenticated session.

After login, a generic error page was displayed. Upon refreshing the page, the system recovered the session, but the cart state changed and items were moved to \*\*“Saved for later”\*\* due to delivery address and seller constraints.

This observation highlights session handling behavior and business rule validation in a real production environment.

This behavior was documented both as a Bug Report and as a Test Observation, demonstrating analytical thinking beyond pass/fail testing.

📸 Supporting evidence is available in the \`/evidence\` folder.

\---

\#\# 📄 Project Documentation

This project includes a complete QA documentation set based on real testing of the Amazon e-commerce checkout flow:

\- \*\*Functional Requirements (EN / PT-BR):\*\* Business rules inferred from system behavior  
\- \*\*Test Plan:\*\* Testing strategy, scope, and approach  
\- \*\*Test Scenarios:\*\* High-level scenarios derived from requirements  
\- \*\*Test Cases:\*\* Detailed manual test cases (Portuguese)  
\- \*\*Test Report:\*\* Execution summary and results  
\- \*\*Bug Report:\*\* Documented real system issue with evidence  
\- \*\*Test Observations:\*\* Relevant behaviors identified during exploratory testing  
\- \*\*Traceability Matrix:\*\* Relationship between requirements, scenarios, test cases, and defects  
\- \*\*Evidence:\*\* Screenshots supporting test execution and findings

All tests were executed in a production environment using a real user account, following a black-box testing approach.

\---

\#\# 📂 Repository Structure

\`\`\`text  
amazon-ecommerce-qa-portfolio/  
│  
├── README.md  
│  
├── functional-requirements/  
│   ├── functional-requirements-amazon.md  
│   └── requisitos-funcionais-amazon-pt.md  
│  
├── test-plan/  
│   └── test-plan-amazon.md  
│  
├── test-scenarios/  
│   ├── test-scenarios-amazon.md  
│   └── test-scenarios-amazon-pt.md  
│  
├── test-cases/  
│   ├── test-cases-amazon.xlsx  
│  
├── test-reports/  
│   ├── test-report-amazon.md  
│   └── test-report-amazon-pt.md  
│  
├── bug-reports/  
│   └── bug-report-amz-chk-001.md  
│  
├── test-observations/  
│   └── test-observation-amz-001.md  
│  
├── quality-metrics/  
│   └── traceability-matrix-amazon.md  
│  
└── evidence/  
    ├── checkout-error-after-login.png  
    ├── cart-items-moved-saved-for-later.png  
    └── checkout-address-restriction.png
