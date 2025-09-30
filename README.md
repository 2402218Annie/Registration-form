Registration form
My HTML and CSS registration form
<!DOCTYPE html>
<html>
    <head>
        <title>E-commerce Registration Form</title>
        <meta name="viewport" content="width=device-wdth, intial-scale=1.0">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>

        <div class="form-container">
            <h2>Register</h2>
            <form>
                <div class="form-group">
                    <label for="fullname">Full Name</label>
                    <input type="text" id="fllname" name="fullname" placeholder="Enter your full name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone" placeholder="Enter your phone" required>
                </div>
                <div class="form-group">
                    <label for="address">Address</label>
                    <textarea id="address" name="address" placeholder="Enter your adress" required></textarea>
                </div>
                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" name="password" placeholder="Create a password" required>
                </div>
                <div class="form-group">
                    <label for="confirm password">Confirm Password</label>
                    <input type="password" id="confirm password" name="confirm password" placeholder="Confirm your Password" required>
                </div>
                <button type="submit" class="btn">Create Account</button>
                <div class="login-link">
                    Already have an account? <a href="#">login</a>
                </div>
            </form>
        </div>
    </body>
</html>
[Uploading registration.html…]()
