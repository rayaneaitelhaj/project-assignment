# Phase 3 – Further Development

## Objective

In this phase, I implemented a user input form with basic validation and a responsive layout. These improvements make the UI more usable and ready for real users.

---

## 1. Input Validation

I created a form with three fields: name, email, and phone. I added HTML validation using `required`, `type="email"`, and a regex pattern for the phone number. I also added JavaScript to show a custom alert if the email does not contain `@`.

### Example Code:

```html
<form id="userForm">
  <input type="text" id="name" placeholder="Your Name" required>
  <input type="email" id="email" placeholder="Your Email" required>
  <input type="tel" id="phone" placeholder="Phone Number" pattern="[0-9]{10}" title="Enter 10-digit number">
  <button type="submit">Submit</button>
</form>
