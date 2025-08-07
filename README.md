<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Coltivare - Management Team</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f4f4f4;
            color: #333;
        }
        h1, h2 {
            font-family: 'Georgia', serif;
            color: darkgreen;
        }
        .executive {
            margin-bottom: 30px;
            padding: 15px;
            background-color: #ffffff;
            border-left: 5px solid green;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        .executive img {
            float: right;
            width: 150px;
            height: 150px;
            margin-left: 20px;
            border-radius: 8px;
        }
        .highlight {
            color: #1a73e8;
            font-size: 18px;
        }
        .important {
            color: #d9534f;
            font-weight: bold;
            font-style: italic;
        }
        .footer {
            margin-top: 50px;
            font-size: 14px;
            font-style: italic;
        }
    </style>
</head>
<body>
    <h1>The Coltivare Management Team</h1>
    <p>Welcome to <strong>The Coltivare</strong>, your trusted partner in delivering exceptional <u>products and services to the farming industry</u>.</p>
 <div class="executive">
        <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="CEO">
        <h2>Robert Ashwood - CEO (President)</h2>
        <p><span class="highlight">Visionary and founder</span> of Coltivare. Robert leads the company with over 25 years of experience in agricultural innovation.</p>
    </div>

    <div class="executive">
        <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="CFO">
        <h2>Linda Ferrell - CFO</h2>
        <p class="important">Linda ensures Coltivare's financial growth and fiscal responsibility. She has a strong background in agribusiness finance.</p>
    </div>

    <div class="executive">
        <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="COO">
        <h2>Thomas Beckett - COO</h2>
        <p>Thomas coordinates our supply chains and operations with <em>precision and dedication</em>. He manages day-to-day functions at scale.</p>
    </div>

    <div class="executive">
        <img src="https://randomuser.me/api/portraits/women/55.jpg" alt="VP">
        <h2>Maria Vaughn - VP of Innovation</h2>
        <p>Maria champions <strong>new farming technology</strong> solutions and <u>green sustainability practices</u>.</p>
    </div>

    <div class="executive">
        <img src="https://randomuser.me/api/portraits/men/22.jpg" alt="Lead Agronomist">
        <h2>Dr. Javier Salas - Lead Agronomist</h2>
        <p>With a PhD in soil science, Javier guides our clients through <span class="important">eco-conscious crop management</span> and soil health strategies.</p>
    </div>

    <h2>Our Company Principles</h2>
    <ol>
        <li>Integrity in every business decision</li>
        <li>Commitment to sustainable agriculture</li>
        <li>Client-centered innovation</li>
    </ol>

    <h2>What We Offer</h2>
    <ul>
        <li>Smart irrigation systems</li>
        <li>Custom fertilizer blends</li>
        <li>Soil and crop consulting</li>
    </ul>

    <p>Want to learn more about agricultural innovation? Visit <a href="https://www.agriculture.com" target="_blank">agriculture.com</a>.</p>
    <p>For product details, check our <a href="products.html">Product Page</a>.</p>
    <p>Reach out to us via email: <a href="mailto:contact@thecoltivare.com">contact@thecoltivare.com</a></p>

    <h3>Download Our 2025 Service Catalog</h3>
    <a href="downloads/Coltivare_Service_Catalog_2025.pdf" download>Click here to download our catalog (PDF)</a>

    <div class="footer">
        <p><em>Date last modified:</em> <span id="lastModified"></span></p>
    </div>

    <script>
        document.getElementById("lastModified").innerText = new Date(document.lastModified).toLocaleDateString();
    </script>
</body>
</html>
