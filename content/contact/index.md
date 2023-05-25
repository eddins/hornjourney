---
title: "Contact Form"
---
<form 
  name="contact" 
  method="POST" 
  data-netlify="true"
  netlify-honeypot="bot-field" >
  <input 
    type="hidden" 
    name="subject" 
    value="Contact form submission from hornjourney.com" />
  <p><label>Your Name: <input type="text" name="name" /></label>
  </p>
  <p><label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p class="gpb">
    <label>
      Don't fill this out if you're human: <input name="bot-field" />
    </label>
  </p>
  <p><label>Message: <textarea cols="40" rows="8" name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
