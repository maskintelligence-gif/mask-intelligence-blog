---
title: "Contact"
permalink: /contact/
layout: single
header:
  overlay_image: /assets/images/contact-bg.jpg
  overlay_filter: rgba(0, 0, 0, 0.7)
---

## Direct Contact Information

### **Email**
[EMAIL US](mailto:maskintelligence@gmail.com)

### **Phone / SMS / WhatsApp**
[CALL US](tel:+256791715573)

**Click to call or send message**

### **Quick Contact Form**
*Opens your email client pre-filled*

<form onsubmit="event.preventDefault(); sendEmail();">
  <input type="text" id="contact_name" placeholder="Your Name" required>
  <input type="email" id="contact_email" placeholder="Your Email" required>
  <textarea id="contact_msg" placeholder="Your Message" rows="4" required></textarea>
  <button type="submit">Send Email</button>
</form>

<script>
function sendEmail() {
  const name = document.getElementById('contact_name').value;
  const email = document.getElementById('contact_email').value;
  const msg = document.getElementById('contact_msg').value;
  
  const mailto = `mailto:maskintelligence@gmail.com?subject=Contact from ${name}&body=From: ${name} (${email})%0D%0A%0D%0A${msg}`;
  window.location.href = mailto;
}
</script>
