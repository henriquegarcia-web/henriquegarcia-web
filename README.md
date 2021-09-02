<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * {
      /* color: black; */
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }
    body {
      background: white;
      display: flex;
      justify-content: center;
    }
  
    .profile_container {
      background-color: rgb(168, 168, 192);
      padding: 15px;
      border-radius: 10px;
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      margin-top: 20px;
      width: 100%;
    }
  
    .profile_container__infos {
      background-color: rgb(40, 40, 65);
      width: 50%;
      padding: 15px 20px;
      border-left: 2px solid white;
      border-right: 2px solid white;
      color: white;
      border-radius: 10px;
    }
    .profile_container__infos:nth-child(1) {
      width: calc(50% - 10px);
      margin-right: 10px;
    }
    .profile_container__infos:nth-child(2) {
      width: calc(50% - 10px);
      margin-left: 10px;
    }

    .profile_container__infos h1 {
      line-break: strict;
      margin: 0;
      margin-bottom: 5px;
      color: white;
      font-size: 24px;
      font-weight: 600;
    }
    .profile_container__infos h2 {
      margin: 0;
      color: white;
      font-size: 16px;
      margin-bottom: 15px;
      font-weight: 500;
    }
    .profile_container__infos p {
      margin: 0;
      font-size: 15px;
      text-align: justify;
      line-height: 1.35;
      margin-bottom: 5px;
      display: flex;
      justify-content: space-between;
      background-color: rgba(252, 252, 252, 0.05);
      padding: 3px 5px;
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <div class="profile_container" style="background-color: rgb(168, 168, 192); padding: 15px; border-radius: 10px; display: flex; flex-direction: row; flex-wrap: wrap; margin-top: 20px; width: 100%;">
    <div class="profile_container__infos">
      <h1>Olá, sou o Henrique Garcia</h1>
      <h2>Desenvolvedor front-end</h2>
      <p><b>Residência:</b> Brasil</p>
      <p><b>Cidade:</b> Canoas</p>
      <p><b>Idade:</b> 19</p>
    </div>
    <div class="profile_container__infos">
      <h1>Tecnologias</h1>
      <h2>Minhas principais habilidades</h2>
      <p><b>JavaScript:</b> | | | | | | | | | | | |</p>
      <p><b>HTML:</b> | | | | | | | | | | | | | | | | | |</p>
      <p><b>CSS:</b> | | | | | | | | | | | | | | | | | | | |</p>
      <p><b>SCSS:</b> | | | | | | | | | | | | | |</p>
    </div>
  </div>
</body>
</html>