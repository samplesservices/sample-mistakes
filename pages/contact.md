---
layout: single
title: "Contact Us"
permalink: /contact/
classes: wide
---

## Get in touch

<div class="contact-form">
  <form action="https://formspree.io/f/yourformid" method="POST">
    <label for="name">Name</label><br/>
    <input type="text" id="name" name="name" required><br/><br/>

    <label for="email">Email</label><br/>
    <input type="email" id="email" name="_replyto" required><br/><br/>

    <label for="message">Message</label><br/>
    <textarea id="message" name="message" rows="5" required></textarea><br/><br/>

    <input type="submit" value="Send Message">
  </form>
</div>

<style>
.contact-form {
  max-width: 600px;
  margin: auto;
}
input[type="text"],
input[type="email"],
textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #aaa;
  border-radius: 4px;
}
input[type="submit"] {
  background-color: #000;
  color: #fff;
  padding: 10px 15px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
input[type="submit"]:hover {
  background-color: #333;
}
</style>
