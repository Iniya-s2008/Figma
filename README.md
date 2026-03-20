# Ex08 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
SLIDE 1:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saveetha Engineering College</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff66cc, #6600cc, #0099ff);
      color: white;
      text-align: center;
    }

    .container {
      padding: 20px;
    }

    header h1 {
      margin: 0;
      font-size: 28px;
      font-weight: bold;
    }

    .subtext {
      margin: 10px 0;
      font-size: 14px;
      line-height: 1.5;
    }

    .emblem {
      margin: 30px 0;
      background: rgba(255,255,255,0.1);
      padding: 15px;
      border-radius: 10px;
    }

    .emblem h2 {
      margin: 0;
      font-size: 20px;
    }

    .emblem p {
      margin: 5px 0 0;
      font-size: 14px;
    }

    .buttons {
      margin: 30px 0;
    }

    .btn {
      background: #ffcc00;
      color: #000;
      border: none;
      padding: 12px 24px;
      margin: 10px;
      font-size: 16px;
      font-weight: bold;
      border-radius: 6px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #ffaa00;
    }

    .runners {
      display: flex;
      justify-content: center;
      margin-top: 40px;
    }

    .runner {
      width: 50px;
      height: 80px;
      margin: 0 10px;
      border-radius: 10px;
    }

    .r1 { background: orange; }
    .r2 { background: yellow; }
    .r3 { background: red; }
    .r4 { background: #ff6600; }

    .cityscape {
      margin-top: 20px;
      height: 80px;
      background: linear-gradient(to top, #004d00, transparent);
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <header>
      <h1>SAVEETHA ENGINEERING COLLEGE</h1>
      <p class="subtext">AUTONOMOUS<br> AFFILIATED TO ANNA UNIVERSITY<br> TNEA CODE 1216</p>
    </header>

    <!-- Emblem -->
    <div class="emblem">
      <h2>SAVEETHA ENGINEERING COLLEGE</h2>
      <p>BE THE BEST</p>
    </div>

    <!-- Buttons -->
    <div class="buttons">
      <button class="btn">LOGIN</button>
      <button class="btn">REGISTER</button>
    </div>

    <!-- Runner silhouettes -->
    <div class="runners">
      <div class="runner r1"></div>
      <div class="runner r2"></div>
      <div class="runner r3"></div>
      <div class="runner r4"></div>
    </div>

    <!-- Cityscape -->
    <div class="cityscape"></div>
  </div>
</body>
</html>
```
SLIDE 2:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sports Day Event</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: white;
      text-align: center;
    }

    .container {
      padding: 40px 20px;
    }

    h1 {
      font-size: 40px;
      margin-bottom: 30px;
      text-transform: uppercase;
      font-weight: bold;
      letter-spacing: 2px;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.5);
    }

    ul {
      list-style: none;
      padding: 0;
      font-size: 20px;
      line-height: 2;
    }

    ul li::before {
      content: "★ ";
      color: #ffcc00;
      font-weight: bold;
    }

    /* Silhouettes background effect */
    .silhouettes {
      margin-top: 40px;
      height: 200px;
      background: url('https://upload.wikimedia.org/wikipedia/commons/4/4f/Sports_silhouettes.png') no-repeat center;
      background-size: contain;
      opacity: 0.3;
    }

    /* Glow effect */
    .glow {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle at center, rgba(255,255,255,0.2), transparent 70%);
      pointer-events: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>SPORTS DAY EVENT</h1>
    <ul>
      <li>KHO KHO</li>
      <li>BASKETBALL</li>
      <li>4x100 RELAY</li>
      <li>100M RUNNING</li>
      <li>BADMINTON</li>
      <li>200M RUNNING</li>
    </ul>
    <div class="silhouettes"></div>
  </div>
  <div class="glow"></div>
</body>
</html>
```
SLIDE 3:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Event Registration Form</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff66cc, #6600cc, #0099ff);
      color: white;
      text-align: center;
    }

    .container {
      max-width: 600px;
      margin: 40px auto;
      background: rgba(0,0,0,0.5);
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0,0,0,0.6);
    }

    h1 {
      margin: 0;
      font-size: 32px;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    h2 {
      margin: 10px 0 20px;
      font-size: 20px;
      font-weight: normal;
      color: #ffcc00;
    }

    form {
      text-align: left;
    }

    label {
      display: block;
      margin: 10px 0 5px;
      font-weight: bold;
    }

    input, select {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 6px;
      margin-bottom: 15px;
      font-size: 14px;
    }

    input:focus, select:focus {
      outline: none;
      box-shadow: 0 0 8px #ffcc00;
    }

    .btn {
      display: block;
      width: 100%;
      background: #ffcc00;
      color: #000;
      border: none;
      padding: 12px;
      font-size: 16px;
      font-weight: bold;
      border-radius: 6px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #ffaa00;
    }

    /* Decorative runners background */
    .runners {
      margin-top: 30px;
      height: 120px;
      background: url('https://upload.wikimedia.org/wikipedia/commons/7/7e/Running_silhouette.png') no-repeat center;
      background-size: contain;
      opacity: 0.3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>EVENT REGISTRATION FORM</h1>
    <h2>FILL THE DETAILS</h2>
    <form>
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" required>

      <label for="gender">Gender</label>
      <select id="gender" name="gender" required>
        <option value="">Select</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>

      <label for="age">Age</label>
      <input type="number" id="age" name="age" required>

      <label for="regno">Register Number</label>
      <input type="text" id="regno" name="regno" required>

      <label for="dept">Department</label>
      <input type="text" id="dept" name="dept" required>

      <label for="mobile">Mobile Number</label>
      <input type="tel" id="mobile" name="mobile" required>

      <label for="email">Email ID</label>
      <input type="email" id="email" name="email" required>

      <label for="event">Event to Register</label>
      <input type="text" id="event" name="event" required>

      <button type="submit" class="btn">Submit</button>
    </form>
    <div class="runners"></div>
  </div>
</body>
</html>
```
SLIDE 4:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sports Event Banner</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #6a0dad, #ff6600);
      color: white;
      text-align: center;
    }

    .container {
      padding: 40px 20px;
    }

    h1 {
      font-size: 32px;
      margin: 0;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 2px;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.5);
    }

    .subtext {
      margin: 10px 0 30px;
      font-size: 16px;
      line-height: 1.5;
    }

    .thankyou {
      font-size: 24px;
      font-weight: bold;
      margin: 30px 0 10px;
      color: #ffcc00;
    }

    .message {
      font-size: 18px;
      margin-bottom: 30px;
    }

    .contact {
      font-size: 16px;
      line-height: 1.8;
      background: rgba(0,0,0,0.4);
      display: inline-block;
      padding: 15px 25px;
      border-radius: 10px;
    }

    /* Decorative runners background */
    .runners {
      margin-top: 40px;
      height: 150px;
      background: url('https://upload.wikimedia.org/wikipedia/commons/7/7e/Running_silhouette.png') no-repeat center;
      background-size: contain;
      opacity: 0.3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>SAVEETHA ENGINEERING COLLEGE</h1>
    <p class="subtext">AUTONOMOUS<br> AFFILIATED TO ANNA UNIVERSITY<br> TNEA CODE 1216</p>

    <p class="thankyou">THANK YOU</p>
    <p class="message">WE ARE ALL EAGERLY WAITING FOR YOUR PARTICIPATION IN THE SPORTS EVENT</p>

    <div class="contact">
      <p><strong>CONTACT US</strong></p>
      <p>Email: inv12008@gmail.com</p>
      <p>Phone: 9173908587</p>
    </div>

    <div class="runners"></div>
  </div>
</body>
</html>
```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/c202e24b-a331-4e0a-a390-a18d74d9bbf2" />



## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
