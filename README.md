<html lang="pt-BR">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Red Dead Redemption II
  </title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
            background-color: black;
            color: white;
            margin: 0;
            padding: 0;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 16px;
            border-bottom: 1px solid #4a4a4a;
        }
        header img {
            height: 40px;
        }
        header h1 {
            font-size: 24px;
            font-weight: bold;
        }
        header h1 span {
            color: #e60000;
        }
        nav a {
            margin: 0 12px;
            text-decoration: none;
            color: white;
        }
        nav a:hover {
            text-decoration: underline;
        }
        nav button {
            padding: 8px 16px;
            border: 1px solid white;
            background: none;
            color: white;
            cursor: pointer;
        }
        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            text-align: center;
        }
        main h2 {
            font-size: 48px;
            font-weight: bold;
        }
        main h2 span {
            color: #e60000;
        }
        .form-container {
            margin-top: 40px;
            padding: 24px;
            border: 1px solid #4a4a4a;
        }
        .form-container p {
            margin-bottom: 16px;
        }
        .form-container form {
            display: flex;
            justify-content: space-between;
        }
        .form-container form div {
            display: flex;
            flex-direction: column;
        }
        .form-container form label {
            font-size: 14px;
            margin-bottom: 4px;
        }
        .form-container form input {
            padding: 8px;
            background-color: #333;
            border: 1px solid #4a4a4a;
            text-align: center;
            color: white;
        }
        .form-container form button {
            padding: 8px 24px;
            background-color: #ffcc00;
            color: black;
            font-weight: bold;
            border: none;
            cursor: pointer;
        }
  </style>
 </head>
 <body>
  <header>
   <div class="logo">
    <img alt="Logotipo da Rockstar Games" src="https://placehold.co/40x40"/>
    <h1>
     RED DEAD REDEMPTION
     <span>
      II
     </span>
    </h1>
   </div>
   <nav>
    <a href="#">
     Visão geral
    </a>
    <a href="#">
     Explorar
     <i class="fas fa-caret-down">
     </i>
    </a>
    <a href="#">
     Progresso
     <i class="fas fa-caret-down">
     </i>
    </a>
    <a href="#">
     Mídia
     <i class="fas fa-caret-down">
     </i>
    </a>
    <a href="#">
     Online
    </a>
    <a href="#">
     Catálogo
    </a>
    <a href="#">
     Suporte
    </a>
    <button>
     COMPRE JÁ
    </button>
    <i class="fas fa-search">
    </i>
    <i class="fas fa-user-circle">
    </i>
   </nav>
  </header>
  <main>
   <div class="title">
    <p>
     ROCKSTAR GAMES APRESENTA
    </p>
    <h2>
     RED DEAD
     <br/>
     REDEMPTION
     <span>
      II
     </span>
    </h2>
   </div>
   <div class="form-container">
    <p>
     Para visualizar esta página, insira sua data de nascimento
    </p>
    <form>
     <div>
      <label for="mes">
       Mês
      </label>
      <input id="mes" placeholder="MM" type="text"/>
     </div>
     <div>
      <label for="dia">
       Dia
      </label>
      <input id="dia" placeholder="DD" type="text"/>
     </div>
     <div>
      <label for="ano">
       Ano
      </label>
      <input id="ano" placeholder="AAAA" type="text"/>
     </div>
     <button type="submit">
      ENVIAR
     </button>
    </form>
   </div>
  </main>
 </body>
</html>
