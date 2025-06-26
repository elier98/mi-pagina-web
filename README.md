para ana maria la mas linda

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Para Ana María 💖</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffd6eb, #ffe5f7);
      color: #5a0030;
      overflow-x: hidden;
      animation: backgroundFade 12s infinite alternate;
    }

    @keyframes backgroundFade {
      0% { background: linear-gradient(135deg, #ffd6eb, #ffe5f7); }
      100% { background: linear-gradient(135deg, #ffe5f7, #ffebf9); }
    }

    header {
      text-align: center;
      padding: 2rem;
      font-family: 'Great Vibes', cursive;
      font-size: 3.2rem;
      color: #ff4081;
      animation: fadeInDown 1.5s ease;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      background: #fff0fa;
      border-radius: 25px;
      padding: 2rem;
      box-shadow: 0 0 30px rgba(255, 105, 180, 0.3);
      animation: float 6s ease-in-out infinite;
    }

    .photo-frame {
      width: 250px;
      height: 250px;
      border-radius: 20px;
      margin: 2rem auto;
      background: url('tufoto.jpg') center/cover no-repeat;
      box-shadow: 0 0 20px rgba(255, 105, 180, 0.5);
      border: 5px solid #fff;
    }

    .message {
      text-align: center;
      font-size: 1.2rem;
      line-height: 1.8;
      padding: 1rem;
      color: #6b0b3c;
    }

    .heart {
      text-align: center;
      font-size: 3rem;
      animation: pulse 2s infinite;
    }

    button {
      display: block;
      margin: 2rem auto;
      padding: 0.8rem 2rem;
      background: #ff69b4;
      border: none;
      color: white;
      font-size: 1rem;
      border-radius: 30px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #ff1493;
    }

    #acercaDeElla {
      display: none;
      margin-top: 2rem;
      background: #ffe6f0;
      padding: 1.5rem;
      border-radius: 20px;
      color: #77003c;
      animation: fadeIn 1s ease;
    }

    .extra-photo {
      width: 100%;
      max-width: 400px;
      margin: 2rem auto;
      border-radius: 25px;
      display: block;
      box-shadow: 0 0 20px rgba(255, 182, 193, 0.5);
      border: 4px solid #fff;
    }

    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-50px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      font-size: 0.9rem;
      color: #aa0055;
    }
  </style>
</head>
<body>

  <header>
    🌸 Para Ana María 🌸
  </header>

  <div class="container">
    <div class="photo-frame"></div>

    <div class="message">
      En este poco tiempo que llevamos conociéndonos, has tocado algo muy bonito en mí.<br>
      Eres una persona especial, única y con una luz que se nota desde lejos.<br><br>

      Puede que el tiempo haya sido corto, pero el cariño que te tengo ha crecido mucho, de verdad.  
      Esta página es solo un pequeño regalo, una muestra de lo que inspiras en mí.  
      Me encanta hablar contigo, reír contigo y conocerte más cada día.<br><br>

      Gracias por ser tú, Ana María. 💖
    </div>

    <div class="heart">💗</div>

    <button onclick="mostrarInfo()">Acerca de ella</button>

    <div id="acercaDeElla">
      Ana María es una persona que brilla con solo sonreír.  
      Tiene una dulzura que se siente, una voz que calma y una energía que alegra.  
      Su forma de ser inspira ternura, respeto y mucha admiración.  
      Esta página está hecha para celebrar lo especial que es… porque ella se lo merece 💕
    </div>

    <img src="la mas linda.jpg" alt="La más linda" class="extra-photo">

  </div>

  <footer>
    Hecho con mucho cariño solo para ti 💘
  </footer>

  <script>
    function mostrarInfo() {
      const info = document.getElementById("acercaDeElla");
      info.style.display = info.style.display === "block" ? "none" : "block";
    }
  </script>

</body>
</html>
5 
