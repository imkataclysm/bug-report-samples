# 🐞 Bug Report – Login Button Unresponsive

**Title:**  
Login button does not respond when clicked on Firefox browser

**Build Version:**  
v1.2.5

**Platform:**  
Web – Firefox 124.0 (Windows 10)

**Location:**  
Login Page (`/login`)

**Steps to Reproduce:**  
- Open the application in Firefox
- Navigate to the login page
- Enter a valid username and password
- Click the "Login" button  

**Expected Result:**  
User should be logged in and redirected to the dashboard  

**Actual Result:**  
Nothing happens when clicking the login button. No error message or loading indicator.  

**Additional Notes:**  
- Works fine in Chrome and Edge  
- No errors in the browser console  
- Happens consistently in Firefox

---

# Bug Report – Signup Allows Invalid Email

**Title:**  
Signup form accepts invalid email format without error

**Build Version:**  
v1.2.5

**Platform:**  
Web – Chrome 122.0 (macOS Ventura)

**Location:**  
Signup Page (`/signup`)

**Steps to Reproduce:**  
- Go to the signup page
- Enter `test@` in the email field
- Fill in the rest of the fields correctly
- Click "Create Account"  

**Expected Result:**  
Form should reject invalid email format and show an error message  

**Actual Result:**  
Form submits successfully, no validation error is shown  

**Additional Notes:**  
- `test@` is not a valid email  
- Could cause issues in user management system

---

# Bug Report – Mobile Menu Overlaps Content

**Title:**  
Mobile navigation menu overlaps page content and cannot be closed

**Build Version:**  
v1.2.5

**Platform:**  
Mobile – iPhone 13, iOS 17.3, Safari

**Location:**  
Any page with mobile navigation

**Steps to Reproduce:**  
- Open the website on iPhone Safari
- Tap the hamburger menu to open the mobile nav
- Try scrolling or tapping outside the menu  

**Expected Result:**  
Menu should close when tapping outside, and content should be usable  

**Actual Result:**  
Menu stays open and overlays the entire page. Content is blocked.  

**Additional Notes:**  
- No close button visible  
- User must refresh to regain access to page  
- Occurs on all pages with mobile nav
