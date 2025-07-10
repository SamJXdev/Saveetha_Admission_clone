# Saveetha_Admission_clone
## Date:

## Objective:
To design a landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS. This activity reinforces skills in layout design, form creation, user input handling, responsive structure, and visual styling based on a real-world example.

## Tasks:
#### 1. Analyze the Landing Page Layout:
Observe the split-screen layout with a promotional section on the left and a form on the right.

Note the use of background images, text styling, and branding elements.

#### 2. Create the HTML Structure:
Use semantic tags like ```<section>, <header>, <form>, and <footer>``` to organize content.

Structure the form with input fields such as name, email, phone, password, city, state, course, specialization, captcha, and checkbox.

#### 3. Add Form Functionality:
Include appropriate input types (text, email, tel, password, select, etc.) with placeholders and labels.

Use the <button> element for the "APPLY NOW" action.

#### 4. Apply CSS Styling:
Implement a split layout using flexbox or grid.

Style the form elements with padding, shadows, background colors, and rounded borders.

Include hover effects and button transitions to match the original look.

#### 5. Incorporate Images and Branding:
Add the institution logo and use matching fonts and colors.

Place a background image or blurred overlay behind the form content if needed.

#### 6. Ensure Responsiveness:
Make sure the page adapts to different screen sizes using media queries.

Maintain readability and layout integrity on both desktop and mobile.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Saveetha Engineering College - Admissions 2025</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="right-section">
      
      <form class="form-box">
        <h2>Admissions Open 2025</h2>
        <input type="text" placeholder="Enter Name *" required>
        <input type="email" placeholder="Enter Email Address *" required>
        <div class="mobile-row">
          <select class="country-code">
            <option>+91</option>
            <option>+66</option>
            <option>+78</option>
            <option>+89</option>
            <option>+12</option>
            <option>+11</option>
          </select>
          <input type="tel" placeholder="Enter Mobile Number *" required>
        </div>
        <input type="password" placeholder="Any Password of Your Choice *" required>

        <div class="row">
          <input type="text" placeholder="State *" required>
          <input type="text" placeholder="City *" required>
        </div>

        <div class="row">
          <input type="text" placeholder="Course *" required>
          <input type="text" placeholder="Specialization *" required>
        </div>

        <div class="captcha">
          <img src="https://dummyimage.com/60x30/cccccc/000000&text=49c96" alt="captcha">
          <input type="text" placeholder="Enter text as shown" required>
        </div>

        <label class="consent">
          <input type="checkbox" required>
          I authorise Saveetha Engineering College & its representatives to contact me with updates and notifications.
        </label>

        <button type="submit" class="submit-btn">APPLY NOW ➤</button>

        <p class="login-link">Already have an Account? <a href="#">Login</a><br><a href="#">Resend Verification Email</a></p>
      </form>
    </div>
  </div>
</body>
</html>
```
## CSS Code:
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
    background-image: url(bg.jpg);
    object-fit: cover;
}

.left-section {
  flex: 1;
  
  padding: 40px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: white;
  
}

.logo {
  width: 750px;
  margin-top: 10px;
  border-radius: 10px;;
}

.tnea-code {
  margin-top: 10px;
  font-size: 20px;
  color: white;
}

.left-section h1 {
  font-size: 40px;
  margin-top: 40px;
  color: yellow;
}

.subtitle, .skills {
  font-size: 22px;
  margin-top: 10px;
}

.apply-btn {
  background: yellow;
  color: black;
  padding: 10px 20px;
  border: none;
  font-weight: bold;
  margin-top: 30px;
  cursor: pointer;
}

.right-section {
  flex: 1;
  position: relative;
  overflow: hidden;
  opacity:0.8
}

.background-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  z-index: 0;
  top: 0;
  left: 0;
}

.form-box {
  position: relative;
  z-index: 1;
  background: rgba(255, 255, 255, 0.95);
  padding: 30px;
  margin: 40px;
  border-radius: 10px;
  color: black;
  max-width: 400px;
  margin-left: auto;
}

.form-box h2 {
  text-align: center;
  margin-bottom: 20px;
}

input[type="text"], input[type="email"], input[type="tel"], input[type="password"] {
  width: 100%;
  padding: 10px;
  margin: 8px 0;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.mobile-row {
  display: flex;
  gap: 5px;
}

.country-code {
  width: 25%;
  padding: 10px;
}

.row {
  display: flex;
  gap: 10px;
}

.row input {
  flex: 1;
}

.captcha {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 10px 0;
}

.consent {
  font-size: 12px;
  margin: 15px 0;
  display: block;
}

.submit-btn {
  width: 100%;
  padding: 12px;
  background: #d89f3d;
  border: none;
  color: white;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
}

.login-link {
  font-size: 12px;
  text-align: center;
  margin-top: 10px;
}

.login-link a {
  color: #000;
  text-decoration: underline;
}
```

## Live web page:
https://samjxdev.github.io/Saveetha_Admission_clone/
## Output:
![image](https://github.com/user-attachments/assets/e69ecab7-b658-4ac1-bc34-d2790e26ad43)


## Result:
A landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS is designed successfully.
