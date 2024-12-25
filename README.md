# Ex09 Event Registration Web Application
# Date: 6-12-2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
HOME PAGE
<style>
.auth-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  color: rgba(0, 0, 0, 1);
  white-space: nowrap;
  text-align: center;
  margin: 0 auto;
  padding: 36px 55px 287px 25px;
  font: 36px Inter, sans-serif;
}

.logo-primary {
  aspect-ratio: 3.75;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.logo-secondary {
  aspect-ratio: 1.08;
  object-fit: contain;
  object-position: center;
  width: 235px;
  margin-top: 54px;
  max-width: 100%;
}

.auth-button {
  background-color: rgba(176, 227, 75, 1);
  width: 241px;
  max-width: 100%;
  font-weight: 600;
  padding: 27px 68px;
  margin-top: 60px;
  cursor: pointer;
  border: none;
  transition: transform 0.2s;
}

.auth-button:hover {
  transform: translateY(-2px);
}

.auth-button:focus {
  outline: 3px solid #000;
  outline-offset: 2px;
}

.auth-button--register {
  box-shadow: 2px 6px 4px rgba(0, 0, 0, 0.4);
  width: 257px;
  font-weight: 500;
  padding: 19px 43px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="auth-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/TEMP/d406e8cac35d158284d46bbcdcfb374767ed6ad57080a23950ac63b4d1d4ad96?placeholderIfAbsent=true&apiKey=1b212e89597745e98d9ae3ca537a2f19"
    class="logo-primary"
    alt="Primary company logo"
  />
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/TEMP/57252ddfeb3edb45c0a5f9020bf6d78fef5d4268fe42a3c67db35aeb70df5edc?placeholderIfAbsent=true&apiKey=1b212e89597745e98d9ae3ca537a2f19"
    class="logo-secondary"
    alt="Secondary company logo"
  />
  <button class="auth-button" tabindex="0">LOGIN</button>
  <button class="auth-button auth-button--register" tabindex="0">REGISTER</button>
</div>

page-2
<style>
  .sports-events-container {
    display: flex;
    max-width: 480px;
    width: 100%;
    flex-direction: column;
    overflow: hidden;
    color: #000;
    text-align: center;
    margin: 0 auto;
    padding: 72px 20px 298px;
    font: 400 36px Inter, sans-serif;
  }

  .sports-title {
    color: #27846B;
    text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
    font-weight: 800;
  }

  .event-row {
    display: flex;
    gap: 18px;
    align-self: flex-start;
    margin: 30px 0 0 29px;
  }

  .event-icon {
    aspect-ratio: 1.17;
    object-fit: contain;
    object-position: center;
    width: 35px;
    align-self: flex-start;
  }

  .event-name {
    flex-basis: auto;
    white-space: nowrap;
  }

  .relay-event {
    align-self: center;
    display: flex;
    margin-top: 35px;
    width: 100%;
    max-width: 314px;
    gap: 20px;
  }

  .relay-name {
    flex-grow: 1;
    flex-basis: auto;
    white-space: nowrap;
  }
</style>

<div class="sports-events-container">
  <div class="sports-title">SPORTS DAY EVENTS</div>
  
  <div class="event-row">
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/2da3fac40015a8017e2fa7d0a2188392ba4588606f30c8a6a9a4f3cb1e5137f2?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="Cricket icon" loading="lazy" />
    <div class="event-name">CRICKET</div>
  </div>

  <div class="event-row">
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/2da3fac40015a8017e2fa7d0a2188392ba4588606f30c8a6a9a4f3cb1e5137f2?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="Badminton icon" loading="lazy" />
    <div class="event-name">BADMINTON</div>
  </div>

  <div class="event-row">
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/2da3fac40015a8017e2fa7d0a2188392ba4588606f30c8a6a9a4f3cb1e5137f2?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="Volleyball icon" loading="lazy" />
    <div class="event-name">VOLLEY BALL</div>
  </div>

  <div class="relay-event">
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/2da3fac40015a8017e2fa7d0a2188392ba4588606f30c8a6a9a4f3cb1e5137f2?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="100 meters relay icon" loading="lazy" />
    <div class="relay-name">100mts-RELAY</div>
  </div>

  <div class="relay-event">
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/2da3fac40015a8017e2fa7d0a2188392ba4588606f30c8a6a9a4f3cb1e5137f2?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="200 meters relay icon" loading="lazy" />
    <div class="relay-name">200mts-RELAY</div>
  </div>

  <div class="relay-event">
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/2da3fac40015a8017e2fa7d0a2188392ba4588606f30c8a6a9a4f3cb1e5137f2?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="400 meters relay icon" loading="lazy" />
    <div class="relay-name">400mts-RELAY</div>
  </div>

  <div class="event-row">
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/2da3fac40015a8017e2fa7d0a2188392ba4588606f30c8a6a9a4f3cb1e5137f2?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="Football icon" loading="lazy" />
    <div class="event-name">FOOT BALL</div>
  </div>
</div>

page-3
<style>
.registration-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  color: #000;
  margin: 0 auto;
  padding: 37px 24px 119px;
  font: 400 24px Inter, sans-serif;
}

.registration-title {
  color: #F8F243;
  text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  font-size: 32px;
  font-weight: 800;
  text-align: center;
  border: 1px solid #000;
}

.input-field {
  background-color: #F5F5F5;
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  width: 328px;
  max-width: 100%;
  margin: 13px 0 0 20px;
  padding: 15px;
}

.input-group {
  display: flex;
  flex-direction: column;
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  position: relative;
  aspect-ratio: 6.255;
  width: 100%;
  gap: 20px;
  justify-content: space-between;
  margin: 25px 0 0 20px;
  padding: 16px 6px;
}

.input-wrapper {
  position: relative;
}

.register-number {
  display: flex;
  flex-direction: column;
  position: relative;
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  aspect-ratio: 6;
  width: 300px;
  max-width: 100%;
  margin: 22px 0 0 20px;
  padding: 22px 0 10px;
}

.department-field {
  background-color: #F5F5F5;
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  align-self: center;
  margin-top: 30px;
  width: 332px;
  max-width: 100%;
  padding: 16px 8px 10px;
}

.mobile-field {
  background-color: #F5F5F5;
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  width: 227px;
  max-width: 100%;
  margin: 109px 0 0 20px;
  padding: 19px 0 11px;
}

.email-field {
  background-color: #F5F5F5;
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  align-self: center;
  margin-top: 30px;
  width: 332px;
  max-width: 100%;
  padding: 14px;
}

.event-field {
  background-color: #F5F5F5;
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  align-self: center;
  margin-top: 22px;
  width: 328px;
  max-width: 100%;
  padding: 19px 4px 10px;
}

.submit-button {
  background-color: #13EFD2;
  align-self: center;
  margin-top: 74px;
  width: 204px;
  max-width: 100%;
  font-size: 36px;
  font-weight: 600;
  text-align: center;
  padding: 14px 15px;
  border: none;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<form class="registration-container" role="form">
  <h1 class="registration-title">EVENT REGISTRATION<br />FORM</h1>
  
  <label for="fullName" class="visually-hidden">Full Name</label>
  <input type="text" id="fullName" class="input-field" placeholder="FULL NAME" required aria-label="Full Name">
  
  <div class="input-group">
    <img src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/f07973e441cd2e76f801a455a8b794c1cf1fef1cb902f4bd77514c52e8b8edc4?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="" class="input-wrapper">
    <label for="gender" class="visually-hidden">Gender</label>
    <select id="gender" class="input-wrapper" required aria-label="Gender">
      <option value="">GENDER</option>
      <option value="male">Male</option>
      <option value="female">Female</option>
      <option value="other">Other</option>
    </select>
    
    <label for="age" class="visually-hidden">Age</label>
    <input type="number" id="age" class="input-wrapper" placeholder="AGE" required aria-label="Age">
  </div>
  
  <div class="register-number">
    <img src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/aed0de667029ba805051b9ffc562572db12fd6b12aff3ac62dc57afc19aa3bf8?apiKey=1b212e89597745e98d9ae3ca537a2f19&" alt="" class="input-wrapper">
    <label for="regNumber" class="visually-hidden">Register Number</label>
    <input type="text" id="regNumber" placeholder="REGISTER NUMBER" required aria-label="Register Number">
  </div>
  
  <label for="department" class="visually-hidden">Department and Branch</label>
  <select id="department" class="department-field" required aria-label="Department and Branch">
    <option value="">DEPARTMENT & BRANCH</option>
  </select>
  
  <label for="mobile" class="visually-hidden">Mobile Number</label>
  <input type="tel" id="mobile" class="mobile-field" placeholder="MOBILE NUMBER" required aria-label="Mobile Number">
  
  <label for="email" class="visually-hidden">Email ID</label>
  <input type="email" id="email" class="email-field" placeholder="EMAIL ID" required aria-label="Email ID">
  
  <label for="event" class="visually-hidden">Event to Register</label>
  <select id="event" class="event-field" required aria-label="Event to Register">
    <option value="">EVENT TO REGISTER</option>
  </select>
  
  <button type="submit" class="submit-button">REGISTER</button>
</form>

page-4
<style>
.thank-you-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  margin: 0 auto;
  padding: 34px 0 70px;
}

.header-logo {
  aspect-ratio: 4.37;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.thank-you-message {
  color: rgba(0, 0, 0, 1);
  text-align: center;
  margin-top: 98px;
  width: 274px;
  font: 600 36px Inter, sans-serif;
}

.contact-section {
  background-color: rgba(245, 245, 245, 1);
  display: flex;
  margin-top: 353px;
  width: 100%;
  max-width: 388px;
  flex-direction: column;
  padding: 22px 12px 8px;
}

.contact-info {
  color: rgba(0, 0, 0, 1);
  font: 600 24px Inter, sans-serif;
}

.contact-email {
  font-size: 15px;
}

.social-links {
  align-self: center;
  display: flex;
  margin-top: 26px;
  width: 191px;
  max-width: 100%;
  gap: 20px;
  justify-content: space-between;
}

.social-group {
  display: flex;
  gap: 16px;
}

.social-icon {
  aspect-ratio: 1.09;
  object-fit: contain;
  object-position: center;
  width: 50px;
}

.social-icon-square {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 46px;
}

.social-icon-rect {
  aspect-ratio: 1.07;
  object-fit: contain;
  object-position: center;
  width: 47px;
  align-self: start;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="thank-you-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/b5c556fc5d1bae9170b41b7cd749c7e05886be5b95b48f325ec0fcb50f683c58?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="header-logo"
    alt="Company logo"
  />
  <h1 class="thank-you-message">
    THANK YOU
    <br />
    FOR REGISTERING
  </h1>
  <div class="contact-section">
    <div class="contact-info">
      CONTACT US:
      <br />
      <br />
      <span class="contact-email">
        EMAIL ID: SAVEETHAENGINEEERINGCOLLEGE@GMAIL.COM
      </span>
    </div>
    <div class="social-links">
      <div class="social-group">
        <a href="#" tabindex="0">
          <img
            loading="lazy"
            src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/496fe9328d3fcfe2d3458c9512f7990aea600a1f8aa53e24010cb6a659a65b15?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
            class="social-icon"
            alt="Social media link"
          />
        </a>
        <a href="#" tabindex="0">
          <img
            loading="lazy"
            src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/b5db88a13cc686fbcd66f5738931305c8b51bcc696a68147cd3f4e98408318bd?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
            class="social-icon-square"
            alt="Social media link"
          />
        </a>
      </div>
      <a href="#" tabindex="0">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/6df35d9390afbf0442d04316732c3964594a57a2c90f3ae2cd7733e4354179cc?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
          class="social-icon-rect"
          alt="Social media link"
        />
      </a>
    </div>
  </div>
</div>
```
# OUTPUT:
![Screenshot (90)](https://github.com/user-attachments/assets/c5098724-dec1-4745-852f-9f37bb3fc6da)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

