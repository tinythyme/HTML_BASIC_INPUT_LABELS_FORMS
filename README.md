<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Sign Up Page</title>
  </head>
  <body>
    <h1>Course Sign Up Page</h1>
    <p>Please Note: First Name, Last Name, Password, and Email are required</p>
    <form method="get">
      <label for="firstname">First Name:</label>
      <input id="firstname" type="text" name="first name" placeholder="First Name"required>
      <label for="lastname">Last Name:</label>
      <input id="lastname" type="text" name="" placeholder="Last Name"><br><br>
      <label for="email">Email:</label>
      <input id="email" type="email" name="" placeholder="name@email.com" required>
      <label for="password">Password:</label>
      <input id="password" type="password" name="" placeholder="Password" required>
      <p>Are you over the age of 18?</p>
      <label for="yes">Yes:</label>
      <input id="yes"type="radio" name="age" value="">
      <label for="no">No:</label>
      <input id="no" type="radio" name="age" value="">
      <p>Do you have a Credit Card or PayPal?</p>
      <select name="payment method">
        <option value="Credit Card">Credit Card</option>
        <option value="PayPal">PayPal</option>
      </select>
    </form><br>
    <input type="submit" name="" value="Submit Feedback">
  </body>
</html>
