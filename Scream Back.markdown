---
layout: page
title: Scream Back
permalink: /contact/
---

<p>If you'd like to reach out, please fill out the form below:</p>

<form action="https://formspree.io" method="POST">
  <div class="form-group">
    <label for="name">Your Name</label>
    <input type="text" id="name" name="name" required />
  </div>

  <div class="form-group">
    <label for="mailto">Your Email</label>
    <input type="email" id="email" name="email" required />
  </div>

  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" required></textarea>
  </div>

  <button type="submit">Send Message</button>
</form>