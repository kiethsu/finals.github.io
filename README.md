<!DOCTYPE html>
<html>
<head>
    <title>Netiquette Website</title>
     <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
      
<script type="text/javascript" src="js.js"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            margin-top: 30px;
        }

        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        li {
            display: inline;
            margin-right: 20px;
        }

        li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        p {
            text-align: center;
            margin-top: 50px;
        }

        .cta-button {
            display: block;
            margin: 0 auto;
            margin-top: 50px;
            text-align: center;
        }

       .cta-button a {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007BFF;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s ease-in-out; /* Added transition property */
}

.cta-button a:hover {
    background-color: #FF0000; /* Changed background color to red on hover */
}

        h2 {
            text-align: center;
            margin-top: 50px;
        }

        ul.bad-etiquette-list {
            margin-top: 20px;
            list-style-type: disc;
            padding-left: 20px;
            text-align: center;
        }

        ul.bad-etiquette-list li {
            margin-top: 10px;
        }

        .etiquette-image {
            background-color: #E5F0FF;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .etiquette-image img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
        }

        .bad-etiquette-box {
            display: flex;
            justify-content: space-between;
            margin-top: 50px;
        }

        .bad-etiquette-box .etiquette-item {
            flex-basis: 30%;
            padding: 20px;
            background-color: #f8f8f8;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: center;
        }
        .bad-etiquette-box .etiquette-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 10px rgba(0, 0, 0, 0.1);
        }

        .bad-etiquette-box .etiquette-item h3 {
            margin-top: 0;
        }

       .fa {
    display: flex;
    justify-content: center;
      margin: 5px 2px;
    padding: 20px;
    ont-size: 30px;
     text-align: center;
  text-decoration: none;
  
    
    }
.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  background: #3B5998;
  color: white;
  }
 .bg {
  animation:slide 3s ease-in-out infinite alternate;
  background-image: linear-gradient(-60deg, #6c3 50%, #09f 50%);
  bottom:0;
  left:-50%;
  opacity:.5;
  position:fixed;
  right:-50%;
  top:0;
  z-index:-1;
}
.bg2 {
  animation-direction:alternate-reverse;
  animation-duration:4s;
}

.bg3 {
  animation-duration:5s;
}
.content {
  background-color:rgba(255,255,255,.8);
  border-radius:.25em;
  box-shadow:0 0 .25em rgba(0,0,0,.25);
  box-sizing:border-box;
  left:50%;
  padding:10vmin;
  position:fixed;
  text-align:center;
  top:50%;
  transform:translate(-50%, -50%);
  }
  @keyframes slide {
  0% {
    transform:translateX(-25%);
  }
  100% {
    transform:translateX(25%);
  }
}
 .navigation {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .navigation a {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007BFF;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            margin: 0 10px;
            transition: background-color 0.3s ease-in-out;
            position: relative;
            overflow: hidden;
        }

        .navigation a:hover {
            background-color: #FF0000;
        }

        .navigation a::before {
            content: "";
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            opacity: 0;
            background-color: #FF0000;
            z-index: -1;
            transition: opacity 0.3s ease-in-out;
        }

        .navigation a:hover::before {
            opacity: 1;
        }
</style>
</head>
<body>
<div class="bg"></div>
<div class="bg bg2"></div>
<div class="bg bg3"></div>

    <div class="container">
        <h1>Welcome to Netiquette Website</h1>
        <nav class="navigation">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#etiquette">Etiquette</a></li>
                <li><a href="#tips">Tips</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
         <div class="cta-button">
            <a href="https://drive.google.com/file/d/1mKhySAL0WmGigGE_JlhZVrh7lk4D83j9/view?usp=share_link">Watch the Video</a>
        </div>
        <section id="about">
            <h2>About Netiquette</h2>
            <p>Netiquette refers to the etiquette or rules of conduct for online communication. It governs how people should behave when interacting with others on the internet, including in email, social media, online forums, and other online platforms.</p>
            <div class="etiquette-image">
                <img src="dj.jpg" alt="Netiquette">
            </div>
        </section>
        <section id="etiquette">
            <h2>Bad Netiquette Examples</h2>
            <ul class="bad-etiquette-list">
                <li>Using ALL CAPS in online communication, which is considered shouting</li>
                <li>Posting offensive or inappropriate content</li>
                <li>Not respecting others' privacy by sharing personal information without consent</li>
                <li>Engaging in cyberbullying or harassment</li>
                <li>Ignoring or interrupting others in online discussions</li>
            </ul>
            <div class="bad-etiquette-box">
                <div class="etiquette-item">
                    <h3>Example 1</h3>
                    <p>Using excessive capitalization in online communication can come across as rude and shouting at others, which is considered bad netiquette.</p>
                </div>
                <div class="etiquette-item">
                    <h3>Example 2</h3>
                    <p>Posting offensive or inappropriate content, such as hate speech or explicit material, is a violation of netiquette and can harm others.</p>
                </div>
                <div class="etiquette-item">
                    <h3>Example 3</h3>
                    <p>Sharing personal information, such as addresses or phone numbers, without consent is a breach of privacy and considered poor netiquette.</p>
                </div>
            </div>
        </section>
        <section id="tips">
            <h2>Tips for Good Netiquette</h2>
            <ul>
                <li>Use polite and respectful language in online communication</li>
                <li>Be mindful of others' opinions and avoid engaging in online arguments</li>
                <li>Respect others' privacy and do not share personal information without consent</li>
                <li>Use proper grammar and avoid excessive use of capitalization, emojis, and abbreviations</li>
                <li>Be aware of online security and avoid sharing or clicking on suspicious links</li>
                <li>Give credit to others for their work and ideas</li>
                <li>Participate in online discussions in a constructive and respectful manner</li>
            </ul>
      <section id="contact">
    <h2>Contact Us</h2>
    <p>If you have any questions or comments, please feel free to contact us through our Facebook page.</p>
    <div class="fa">
    <a href="https://www.facebook.com/profile.php?id=100078925843524&mibextid=ZbWKwL/" class="fa fa-facebook" target="_blank" rel="noopener noreferrer"></a>
</div>

</section>

<footer>
<p>© 2023 Netiquette Website. All rights reserved. | Privacy Policy | Terms of Service</p>
</footer>
</div>

</body>
</html>
