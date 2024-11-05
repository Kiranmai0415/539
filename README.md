<!DOCTYPE html>
<html>
    <head>
        <title>user registration form</title>
    </head>
    <body>
        <h1>USER REGISTRATION FORM</h1>
        <form>
            <label for="Name">Name:</label>
            <input type="text" id="name" name="name" required> <br> <br>

            <label for="Email">Email:</label>
            <input type="email" id="email" name="email" required> <br> <br>

            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone" required> <br> <br>

            <label for="organization">Organization:</label>
            <input type="text" id="organization" name="organization"> <br> <br>

            <label for="attendee-type">attendee-type:</label>
            <select id="attendee-type" name="attendee-type">
            <option value="general">General</option>
            <option value="vip">VIP</option>
            <option value="speaker">SPEAKER</option>
        </select>
        <br> <br>
        <input type="submit"value="REGISTER">
        </form>
    </body>
</html>
