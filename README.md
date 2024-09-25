<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Footer</title>
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@3.3.7/dist/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

    <!-- Latest compiled and minified JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@3.3.7/dist/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
</head>
<body>
    <style>
        .footer-container {
            background-color: #0e2a3f; 
            color: white;
            padding: 20px;
        }

        .footer-container .footer-logo {
            width: auto;
            height: 100px;
        }

        .footer-container .footer-heading {
            font-size: 12px;
            text-transform: uppercase;
            font-weight: 600;
            color: green;
        }

        h4 {
            font-size: 18px;
            font-weight: 800;
            color: white;
        }

        .icon-container {
            margin: 70px 0;
        }

        .icon-container ul {
            list-style: none;
            padding: 0;
            display: flex;
            align-items: center;
            
        }

        .icon-container ul li {
            margin: 0 5px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 35px;
            height: 35px;
        }

        .icon-container ul li:first-child {
            margin-left: 0;
        }

        .icon-container ul li:last-child {
            margin-right: 0;
        }

        .icon-container ul li img {
            width: 100%;
            height: 100%;
            border-radius: 3px;
        }   

        .footer-container .form-label {
            color: white;
            font-size: 20px;
            font-weight: 700;
            margin: 0px 0 20px;
        }

        .footer-container form .signup {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .footer-container form input {
            width: 65%;
            height: 40px;
            padding: 0 10px;
            border: none !important;
            outline: none !important;
            border-radius: 2px;
        }

        .footer-container form button {
            width: 35%;
            height: 40px;
            background-color: blue;
            color: white;
            border: none !important;
            outline: none !important;
            text-align: center;
            border-radius: 2px;
            cursor: pointer;
            margin-left: 10px;
        }

        .form-container input[type="checkbox"] {
            width: 13px;
            height: 13px;
            margin:  0 10px;
            margin-left: 0;
        }

        .form-container {
            width: 100%;
        }

        .form-container .checkbox-container {
            display: flex;
            align-items: center;
        }

        .form-container .checkbox-container p {
            margin: 0;
        }

        .footer-text li {
            list-style: none;
            margin: 15px 0;
        }

        .footer-text ul {
            padding: 0;
        }

        .checkbox-container {
            padding: 10px 0;
        }

        .checkbox-container label {
            margin-bottom: 0;
            font-size: 12px;
            font-weight: normal;
        }

        .footer-paragraph {
            padding: 0 15px;
            margin-top: 20px;
        }
    </style>
    <div class="container-fluid footer-container">
        <div class="row">
            <div class="col-md-6">
                <div class="row">
                    <div class="col-xl-8 col-lg-8 col-12">
                        <img src="https://via.placeholder.com/150" alt="logo" class="footer-logo">
                        <h2>Maximize your travel</h2>
                        <div class="icon-container">
                            <ul>
                                <li>
                                    <a href="#">
                                        <img src="https://via.placeholder.com/50" alt="facebook">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img src="https://via.placeholder.com/50" alt="facebook">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img src="https://via.placeholder.com/50" alt="facebook">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img src="https://via.placeholder.com/50" alt="facebook">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img src="https://via.placeholder.com/50" alt="facebook">
                                    </a>
                                </li>
                            </ul>
                        </div>
                        <div class="form-container">
                            <p class="form-label">Sign up for our daily newsletter for the latest news, deals and tips.</p>
                            <div>
                                <form>
                                    <div class="signup">
                                        <input type="text">
                                        <button>Sign up</button>
                                    </div>
                                    <div class="checkbox-container">
                                        <input type="checkbox">
                                        <label for="checkbox">I would like to subscribe to the Points Gug newsletters and special email promotions. The Points Guy will not share or sell your email. save PRIVACY POLICY.</label>
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="row">
                    <div class="col-sm-4 footer-text">
                        <h5 class="footer-heading">Some text</h5>
                        <ul>
                            <li>About us</li>
                            <li>TPG gives back</li>
                            <li>Careers</li>
                            <li>Contact us</li>
                            <li>Site map</li>
                            <li>Newsletters</li>
                        </ul>
                    </div>
                    <div class="col-sm-4 footer-text">
                        <h5 class="footer-heading">Legal</h5>
                        <ul>
                            <li>Do Not Sell or Share My Personal Information</li>
                            <li>Privacy Policy</li>
                            <li>Terms of use</li>
                            <li>Cookie settings</li>
                            <li>Consumer Health Data Privacy Policy</li>
                        </ul>
                    </div>
                    </div>
                    <div class="row">
                    <div class="col-12 footer-paragraph">
                        <h5 class="footer-heading">our commitment</h5>
                        <div class="" >
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor facere dolorum nulla numquam aperiam voluptates repellendus non praesentium. Aliquam dicta quod itaque reiciendis alias dignissimos quas. Ad enim, in excepturi illum minus perspiciatis ex quia cupiditate. Velit doloribus aperiam adipisci odit beatae consequuntur, impedit, sequi ad nisi corporis est! Nihil veritatis dignissimos molestiae. Quia magni unde, mollitia dicta tempora tenetur fuga reprehenderit maxime necessitatibus veritatis voluptatum odit hic ipsa sed possimus asperiores nemo recusandae fugit consequatur fugiat dolor quaerat aspernatur! Quas tempora quia repellendus? Fuga distinctio quod, illo suscipit quae dolorum unde facere error animi veritatis nobis ipsum omnis nemo!
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
