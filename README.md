# HTML
Contact Page.html

<html>
    <head>
        <title>Contact us</title>
    </head>
    <style>
        h3{
                text-align:center;
          }
    </style>
    <body>
        <form action="/">
            <h3>CONTACT US</h3>
             First Name:
            <input type="text" name="full name" size="20" border="none"><br><br>
            last Name:
            <input type="text" name="last name" size="20" border="none"><br><br>
            country:
            <input type="text" name="country" border="none"><br><br>
            <label>Phone number:</label>
            <input type="tel" name="personal" id="personal" pattern="[0-9]{10}" title="Ten digit mobile number" border="none"><br><br>
            <label>Email:</label>
            <input type="text" name="email" border="none"><br><br>
            Message:
            <div>
            <textarea>message</textarea>
            <input type="submit"><br><br>
        </form>
    </body>
</html>
