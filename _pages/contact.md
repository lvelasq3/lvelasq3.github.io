---
layout: splash
title: "Contact"
permalink: /contact/
author_profile: false
header:
  overlay_image: bridge.jpg
  overlay_filter: 0.15
---

<style>
.page__hero,
.page__hero--overlay,
.page__title {
  display: none;
}

#main {
  max-width: none;
  padding: 0;
  margin: 0;
}

.contact-page {
  min-height: calc(100vh - 70px);
  background-image: url("/images/bridge.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 5rem 1.5rem;
}

.contact-card {
  width: 100%;
  max-width: 680px;
  background: rgba(255, 255, 255, 0.97);
  border-radius: 18px;
  padding: 3rem;
  text-align: center;
  box-shadow: 0 18px 45px rgba(0, 0, 0, 0.25);
  color: #222 !important;
}

.contact-card h1 {
  margin: 0;
  font-size: 2.8rem;
  font-weight: 300;
  letter-spacing: 0.02em;
  color: #111 !important;
}

.contact-line {
  width: 55px;
  height: 3px;
  background: #4d7c3f;
  margin: 1.2rem auto 1.5rem;
}

.contact-card p {
  margin-bottom: 2rem;
  color: #444 !important;
}

.contact-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}

.contact-card input,
.contact-card textarea {
  width: 100%;
  padding: 0.9rem 1rem;
  margin-bottom: 1rem;
  border: 1px solid #d0d0d0;
  border-radius: 7px;
  font-size: 1rem;
  background-color: #ffffff !important;
  color: #222 !important;
  -webkit-text-fill-color: #222 !important;
  box-sizing: border-box;
}

.contact-card input::placeholder,
.contact-card textarea::placeholder {
  color: #777 !important;
  opacity: 1 !important;
  -webkit-text-fill-color: #777 !important;
}

.contact-card input:focus,
.contact-card textarea:focus {
  color: #222 !important;
  -webkit-text-fill-color: #222 !important;
  background-color: #ffffff !important;
  outline: none;
  border-color: #4d7c3f;
  box-shadow: 0 0 0 3px rgba(77, 124, 63, 0.15);
}

.contact-card textarea {
  min-height: 190px;
  resize: vertical;
}

.contact-card button {
  width: 100%;
  padding: 1rem;
  background: #4d7c3f;
  color: #ffffff !important;
  -webkit-text-fill-color: #ffffff !important;
  border: none;
  border-radius: 7px;
  font-size: 1.1rem;
  cursor: pointer;
  transition: background 0.2s ease;
}

.contact-card button:hover {
  background: #3f6934;
}

.contact-note {
  margin-top: 1.2rem;
  font-size: 0.85rem;
  color: #666 !important;
}

@media (max-width: 700px) {
  .contact-card {
    padding: 2rem;
  }

  .contact-row {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="contact-page">
  <div class="contact-card">

    <h1>Contact</h1>
    <div class="contact-line"></div>

    <p>
      I'd love to hear from you. Please fill out the form below and I will get back to you as soon as possible.
    </p>

    <form action="https://formspree.io/f/xrevnnre" method="POST">

      <div class="contact-row">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
      </div>

      <input type="text" name="subject" placeholder="Subject">

      <textarea name="message" placeholder="Your Message" required></textarea>

      <button type="submit">Send Message</button>

    </form>

    <div class="contact-note">
      Your information is private and will never be shared.
    </div>

  </div>
</div>
