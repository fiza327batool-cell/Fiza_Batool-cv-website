FIZA BATOOL — CV WEBSITE
========================
 given prompt to Ai:
 1. present your cv in a sigle page website /(SPA) website(scroll allowed)(verticall scroll )  
  
# give me prompt for google stich . im the stdent of cs and also im giving my resume so give me prompt according to this. first one is my documents and certificate and socond one is my resume so give me prompt according to my info so i can paste on google steitch and it  will give me designs according to given info

CONTENTS
- index.html: single-page portfolio website (HTML, styling, and interactions)
- documents/Fiza-Batool-CV.pdf: your actual resume PDF
- documents/Fiza-Batool-Documents-and-Certificates.pdf: your uploaded documents PDF
- script.js: reference copy of the EmailJS configuration values

OPEN LOCALLY WITH XAMPP
1. Copy the whole Fiza_Batool_CV_Website folder to C:\xampp\htdocs\Resume.web (or rename the folder as you prefer).
2. Start Apache in XAMPP Control Panel.
3. Open http://localhost/Resume.web/ in Chrome.
4. Test Download CV, View CV, View Documents, and Download PDF. The PDF files are included in documents/.

EMAIL FORM SETUP (REQUIRED FOR REAL EMAIL SENDING)
The contact form uses EmailJS. A static website cannot securely send email by itself. To enable sending:
1. Create an account at https://www.emailjs.com/ and connect an email service.
2. Create an EmailJS template with these variables: user_name, user_email, subject, message.
3. Set the template's recipient/to email to fiza326batool@gmail.com. Set Reply-To to {{user_email}} if the service/template supports it.
4. Copy your EmailJS Public Key, Service ID, and Template ID.
5. Open index.html and find EMAILJS_PUBLIC_KEY, EMAILJS_SERVICE_ID, EMAILJS_TEMPLATE_ID near the bottom. Replace each YOUR_EMAILJS_... placeholder with the actual value.
6. Save and test using a message from your own email address. Check your inbox and spam folder.

The form intentionally reports that it is not configured until those values are supplied. This avoids falsely telling visitors their message was sent. Do not place EmailJS private/secret keys in this public frontend.