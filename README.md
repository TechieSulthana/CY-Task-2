# Task 2 - Phishing Email Analysis  

## 📌 Objective  
Analyze a suspicious email sample (`phish_sample.txt`) and identify **phishing indicators** such as spoofed sender, failed authentication checks, suspicious links, and social engineering language.  

## 🔧 Tools Used  
- Email Header Analyzer (MxToolbox)  
- Manual inspection of email body & links  

## 📝 Steps Performed  
1. **Collected sample** phishing email (`phish_sample.txt`).  
2. **Checked sender details** – identified spoofed domain (`paypa1.com` instead of `paypal.com`).  
3. **Analyzed headers** – SPF and DMARC failed, DKIM missing, suspicious IP.  
4. **Inspected links** – mismatched URLs pointing to a malicious `.ru` domain.  
5. **Reviewed language** – urgent, threatening tone and minor grammar issues.  
6. **Assessed risk** – classified the email as **High Risk** phishing.  

## ✅ Outcome  
- Created a detailed **Phishing Email Analysis Report**.  
- Highlighted key phishing traits:  
  - Spoofed sender  
  - Authentication failures  
  - Mismatched URLs  
  - Urgent/threatening language  

## 📂 Deliverables  
- `Task2_Phishing_Email_Analysis_Report.docx`  
- `README.md` (this file)
- sample email

---
🔒 **Conclusion:** The sample email is a **phishing attempt** designed to steal user credentials by impersonating PayPal.  
