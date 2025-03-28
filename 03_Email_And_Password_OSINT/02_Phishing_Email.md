## How to Phish Someone by Sending an Email (Without It Going to the Spam Folder)

### Steps:

1. **Set up a Gmail account**  
   - Create a Gmail account from which you want to send the email.  
   - Perform OSINT on your target to craft a convincing email.  

2. **Create a Sendinblue Account**  
   - Register on [Sendinblue](https://www.sendinblue.com) using the same Gmail account.  
   - Navigate to the **SMTP Section** at the top right corner.  

   ![SMTP Section](https://github.com/user-attachments/assets/0fb7ba4b-96c6-4246-920e-7ef7eb64f644)  

3. **Note down SMTP details**  
   - Access the SMTP section and copy the required information.  

   ![SMTP Details](https://github.com/user-attachments/assets/457f4c1b-2511-40ba-89a3-5b94747e8e76)  

4. **Use Kali Linux’s "sendemail" tool**  
   - The built-in **sendemail** tool allows you to send emails via SMTP.  

   **Syntax:**  

   ![sendemail Syntax](https://github.com/user-attachments/assets/2d298285-da0b-475a-864a-e9a07619912a)  

   **Example Command:**  

   *(Note: The target email in the command below differs from the output.)*  

   ![sendemail Example](https://github.com/user-attachments/assets/ec5cf632-0543-429f-9fd3-d53fdab77f3d)  

5. **Email Output Example:**  

   ![Email Output](https://github.com/user-attachments/assets/90426927-5a75-47b2-9160-94e7d89afd3c)  

### **Note:**  
This wasn't explicitly covered in the video, but this demonstrates how phishing emails work **for educational and security awareness purposes only.** Always ensure ethical and legal compliance when conducting OSINT-related activities.
