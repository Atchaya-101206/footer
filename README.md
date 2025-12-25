<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        ody {
            margin: 0px;
            padding: 100px;
            font-family: Arial, sans-serif;
            background-color: #ffffff;
        }
        footer {
            background-color: #222;
            color: #ccc;
            padding: 40px 0 0;
        }

        .footer-container {
            display: flex;
            justify-content: space-around;
            padding: 0 40px;
        }

        .footer-box {
            width: 30%;
        }

        .footer-box h3 {
            color: #fff;
            margin-bottom: 15px;
        }

        .footer-box p,
        .footer-box li {
            font-size: 14px;
            /* line-height: 1.6; */
        }

        .footer-box ul {
            list-style: none;
            padding: 0;
        }

        .footer-box ul li {
            margin-bottom: 8px;
        }

        .footer-box ul li a {
            text-decoration: none;
            color: #ccc;
        }

        .footer-box ul li a:hover {
            color: #fff;
        }

        .social-links a {
            margin-right: 10px;
            color: #ccc;
            text-decoration: none;
        }

        .social-links a:hover {
            color: #fff;
        }

        .footer-bottom {
            background-color: #111;
            text-align: center;
            padding: 15px 0;
            margin-top: 30px;
            font-size: 14px;
            color: #aaa;
        }
    </style>
    <title>Footer Design</title>
    <link rel="stylesheet" href="./task5.css">
</head>
<body>

<footer>
    <div class="footer-container">

        <div class="footer-box">
            <h3>About Us</h3>
            <p>
                We build responsive and user-friendly web solutions for all
                platforms. Quality, simplicity, and speed are our core values.
            </p>
        </div>

        <div class="footer-box">
            <h3>Quick Links</h3>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Portfolio</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>


        <div class="footer-box">
            <h3>Contact</h3>
            <p>Email: info@example.com</p>
            <p>Phone: +91 9876543210</p>
           <p>Location: Chennai, India</p>

            <div class="social-links">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">LinkedIn</a>
            </div>
        </div>

    </div>

    <div class="footer-bottom">
        © 2025 YourCompany. All rights reserved.
    </div>
</footer>


</body>
</html>
