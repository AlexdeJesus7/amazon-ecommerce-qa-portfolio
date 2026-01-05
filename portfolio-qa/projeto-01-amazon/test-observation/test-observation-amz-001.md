\# Test Observation — TO-AMZ-001

\*\*Title:\*\* Intermittent checkout behavior after guest login    
\*\*Environment:\*\* Production (amazon.com)    
\*\*Date:\*\* 2026-01-02    
\*\*Observed by:\*\* Alex de Jesus  

\---

\#\# Observation  
During checkout execution, an intermittent error page was displayed after user authentication. After refreshing the page, the system recovered and automatically moved items to “Saved for later” due to address and seller constraints.

\---

\#\# Impact  
Low — no purchase failure or data loss observed.

\---

\#\# Conclusion  
This behavior was documented as a test observation. No functional defect was confirmed.