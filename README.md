<!-- README.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Beyond Store - README</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap" rel="stylesheet">
  <style>
    body {
      background-image: url('https://files.catbox.moe/4eog92.jpg');
      background-size: cover;
      background-position: center;
      font-family: 'Luckiest Guy', cursive;
    }
    .scroll-text {
      animation: scroll 15s linear infinite;
      white-space: nowrap;
    }
    @keyframes scroll {
      from { transform: translateX(100%); }
      to { transform: translateX(-100%); }
    }
  </style>
</head>
<body class="text-white min-h-screen bg-black bg-opacity-70 p-6 flex flex-col items-center justify-start space-y-6">

  <h1 class="text-5xl text-yellow-300 animate-bounce mt-8">🌀 Beyond Store README 🛍️</h1>

  <p class="text-blue-200 scroll-text text-xl">✨ Fun, Cartoonish, Glowy, and Beyond! ✨</p>

  <div class="bg-white bg-opacity-10 p-6 rounded-xl w-full max-w-3xl space-y-4 text-lg">
    <p>📌 <strong>What is this?</strong><br>
      A cool cartoon-style website to sell bots, panels, and more with glowing buttons and LED-style text.
    </p>

    <p>🧩 <strong>Features:</strong></p>
    <ul class="list-disc list-inside text-blue-300">
      <li>Registration form with animated style</li>
      <li>Send new users to your Telegram automatically</li>
      <li>Pages: Products, Contact, Support, Logout</li>
      <li>Glowing product list with Tailwind styling</li>
      <li>Fun, anime-style background image</li>
    </ul>

    <p>📂 <strong>Pages Included:</strong></p>
    <ul class="list-disc list-inside text-yellow-300">
      <li><code>index.html</code> – Registration Page</li>
      <li><code>home.html</code> – Menu after Register</li>
      <li><code>products.html</code> – Glowing Product List</li>
      <li><code>support.html</code> – Telegram/WhatsApp Contact</li>
      <li><code>contact.html</code> – Email Support</li>
      <li><code>logout.html</code> – Logout Screen</li>
    </ul>

    <p>💌 <strong>Contact:</strong></p>
    <ul class="list-disc list-inside text-green-300">
      <li>Telegram: <a href="https://t.me/deekingbeyond" class="underline">@deekingbeyond</a></li>
      <li>WhatsApp: <a href="https://wa.me/447796179042" class="underline">+447796179042</a></li>
    </ul>

    <p>🌈 <strong>Designed By:</strong> Beyond 🌀</p>
    <p class="text-sm text-blue-400 italic">"Make it glow, make it wild, make it BEYOND."</p>
  </div>

  <footer class="text-sm text-blue-200 mt-8">Open this README like a website — just double click!</footer>
</body>
</html>
