<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Proposal Page for Ekta ❤️</title>

  <!-- Custom Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  
  <style>
    /* Global Styling */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffdee9, #b5fffc);
      color: #ff3366;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      overflow: hidden;
    }

    /* Container Styling */
    .container {
      max-width: 600px;
      text-align: center;
      background: rgba(255, 255, 255, 0.9);
      padding: 50px;
      border-radius: 20px;
      box-shadow: 0px 15px 25px rgba(0, 0, 0, 0.2);
      opacity: 0;
      transform: scale(0.9);
      transition: opacity 0.6s ease, transform 0.6s ease;
    }
    .container.active {
      opacity: 1;
      transform: scale(1);
    }

    /* Heading Styling */
    h1, h2 {
      font-family: 'Great Vibes', cursive;
      color: #ff66a3;
      font-size: 3em;
      margin-bottom: 30px;
    }

    /* Buttons Styling */
    .button {
      display: inline-block;
      margin: 25px;
      padding: 20px 40px;
      font-size: 1.5em;
      color: #fff;
      background: #ff4d4d;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
      transition: 0.3s;
    }
    .button:hover {
      background: #ff80a6;
      transform: translateY(-5px);
      box-shadow: 0 12px 20px rgba(0, 0, 0, 0.3);
    }

    /* Certificate Styling */
    .certificate {
      font-family: 'Poppins', sans-serif;
      text-align: left;
      padding: 40px;
      background-color: #ffe6f7;
      border: 2px solid #ff99cc;
      border-radius: 10px;
      box-shadow: 0px 0px 15px rgba(255, 153, 204, 0.3);
      margin-top: 40px;
    }
    .certificate h2 {
      font-size: 2.5em;
      color: #ff66a3;
      margin-bottom: 20px;
    }
    .certificate p {
      font-size: 1.5em;
      font-style: italic;
      color: #ff3366;
    }

    /* Emoji Animations */
    .emoji {
      font-size: 3em;
      animation: bounce 1.5s infinite;
      display: inline-block;
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
    }

    /* Thumbprint Styling */
    .thumbprint {
      font-size: 3.5em;
      color: #ff66a3;
      margin-top: 20px;
      text-align: center;
    }

  </style>
</head>
<body>

  <!-- Main Container -->
  <div id="page1" class="container active">
    <h1>Ekta, do you like me? ❤️</h1>
    <button class="button" onclick="showNext('page2')">Yes</button>
    <button class="button" onclick="noResponse()">No</button>
  </div>

  <div id="page2" class="container">
    <h2>I love you too, Ekta ji 💖</h2>
    <p>ye niche jo kiss wla emoji hai na isko dabado ek baar and jst feel ki hum kiss kr liye h 😘</p>
    <button class="button emoji" onclick="showNext('page3')">😘</button>
  </div>

  <div id="page3" class="container">
    <h2>kuch puchna h, Will you marry me, Ekta? 💍</h2>
    <button class="button" onclick="showNext('page4')">Yes, I will marry you</button>
    <button class="button" onclick="showNext('page4')">Haan, mere Ishitva ji</button>
  </div>

  <div id="page4" class="container certificate">
    <h2>Certificate of Love & Future Marriage</h2>
    <p>This certifies that Ekta and Ishitva are bound together in love forever and are excited to begin a beautiful journey together. hehe ab to tum hmari sach me wife bn hi gyi aaj🙈accha suno raat ko pkd ke sona wo bhi naked fully🌚 ...chipka jayega🙈🙈 💞</p>
    <p>They vow to support, cherish, and adore each other for all time.</p>
    <div class="thumbprint">💖 Ekta ek sign krke hme send krna for this agreement💖</div>
  </div>

  <!-- JavaScript for Page Transitions and Response Handling -->
  <script>
    // Function to show the next page
    function showNext(pageId) {
      document.querySelectorAll('.container').forEach(page => page.classList.remove('active'));
      document.getElementById(pageId).classList.add('active');
    }

    // Function for 'No' response
    function noResponse() {
      alert("suno ji aise glt button na press kro bhut pyar krte h hum tumse! 💔");
    }
  </script>

</body>
</html>
