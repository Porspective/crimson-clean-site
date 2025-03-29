# crimson-clean-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Crimson Clean Co.</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #b11226;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    .container {
      max-width: 600px;
      margin: 2rem auto;
      padding: 2rem;
      border: 1px solid #ccc;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #b11226;
    }
    label {
      display: block;
      margin-top: 1rem;
    }
    input, textarea {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      margin-top: 1.5rem;
      background-color: #b11226;
      color: white;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    button:hover {
      background-color: #93101f;
    }
    footer {
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
      background-color: #f4f4f4;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Crimson Clean Co.</h1>
    <p>OU Student-Run Pressure Washing Services</p>
  </header>

  <div class="container">
    <h2>Request a Quote</h2>
    <form action="https://formspree.io/f/mdkellwd" method="POST">
      <input type="hidden" name="_replyto" value="crimsoncleancompany@gmail.com">

      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="address">Service Address</label>
      <textarea id="address" name="address" rows="3" required></textarea>

      <label for="details">Additional Details</label>
      <textarea id="details" name="details" rows="4"></textarea>

      <button type="submit">Send Request</button>
    </form>
  </div>

  <footer>
    &copy; 2025 Crimson Clean Co. | OU Student-Run | All rights reserved
  </footer>
</body>
</html>
