\# Bug Report — AMZ-CHK-001

\*\*Title:\*\* Intermittent error page displayed after login during checkout with guest cart    
\*\*Project:\*\* Amazon E-commerce    
\*\*Environment:\*\* Production (amazon.com)    
\*\*Severity:\*\* Medium    
\*\*Priority:\*\* Low    
\*\*Status:\*\* Open (Observation)    
\*\*Reported by:\*\* Alex de Jesus    
\*\*Date:\*\* 2026-01-02  

\---

\#\# Description  
When attempting to proceed to checkout with products added to the cart as a guest user, the system redirects to the login page. After successful authentication, an intermittent generic error page ("Sorry, something went wrong") is displayed. Upon refreshing the page, the system recovers the session, but the cart state is altered.

\---

\#\# Preconditions  
\- User not logged in    
\- Products added to cart as guest    
\- Products subject to delivery address restrictions  

\---

\#\# Steps to Reproduce  
1\. Access amazon.com without being logged in    
2\. Add products to the cart    
3\. Go to Cart    
4\. Click \*\*Proceed to checkout\*\*    
5\. Login with valid credentials  

\---

\#\# Expected Result  
\- User redirected to checkout    
\- Cart items preserved    
\- No error page displayed  

\---

\#\# Actual Result  
\- Generic error page displayed after login    
\- Cart becomes empty after refresh    
\- Items moved to \*\*Saved for later\*\*  

\---

\#\# Evidence  
\- Error page after login    
\- Cart empty with items moved to Saved for later  

\---

\#\# Notes  
\- Issue is intermittent    
\- No permanent functional impact    
\- Possibly related to session synchronization

