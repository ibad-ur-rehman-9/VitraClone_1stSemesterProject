## VitraClone_1stSemesterProject
A skeleton clone of [Vitra's](https://www.vitra.com/en-un/home?srsltid=AfmBOopCwC4sE4K9MLYkK555R8_y_3UOSR-pE-ZBBoHugYJcHNKPZCaQ) 2023 version, with a basic form with a SMTP-based email backend

# Tech Stack
1. HTML
2. JS (Vanilla)
3. CSS

# Features

1. Homepage (index.html) - A simplified clone of Vitra’s 2023 homepage (Header, Hero Section, Footer), leads to form.html
2. Feedback Form (form.html) - Takes input and sends it to a specified email address using SMTP.js
3. Thank You Page (thankyou.html) - Animated thank you after form is submitted successfully
4. style.css - All the CSS styling for the index.html

# SMTP Configuration:
Set up youe smtp server and token from elastic email, [Guide video - RISE COMPUTER SCIENCE EDUCATION](https://youtu.be/bRjpP34MHhk?t=452)

<pre> ```bash 
  Email.send({
  SecureToken: "YOUR_SECURE_TOKEN_HERE",
  To: "recipient@example.com",
  From: "sender@example.com",
  Subject: "Feedback Form",
  Body: body
});
  ``` </pre>
