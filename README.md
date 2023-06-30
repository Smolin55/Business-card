<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact</title>
  <link rel="stylesheet" href="#">
  <style>
    @import url('https://fonts.googleapis.com/css?family=Pappins:200,300,400,500,600,700,800,900&display=swaps');
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins',sans-serif;
    }
    :root {
      --clr: #673ab7;
    }
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: var(--clr);
    }
    .card {
      position: relative;
      width: 320px;
      height: 430px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .card .box {
      position: relative;
      width: 110%;
      height: 200px;
      background: transparent;
      border-radius: 15px;
    }
    .card .box:nth-child(2) {
      background: #fff;
      height: 220px;
      width: 100%;
    }
    .card .circle {
      position: absolute;
      top: 50%;
      left: -70px;
      transform: translateY(-50%);
      width: 150px;
      height: 150px;
      background: #0f0;
      border-radius: 50%;
      border: 10px solid var(--clr);
    }
    .card .circle .imgBx,
    .card .box .imgBx {
      position: absolute;
      inset: 0;
      overflow: hidden;
      border-radius: 50%;
    }
    .card .box .imgBx {
      border-radius: 15px;
    }
    .card .circle .imgBx img,
    .card .box .imgBx video {
      position: absolute;
      width: 100%;
      height: 100%;
      object-fit: center;
    }
    .card .box .content {
      position: absolute;
      inset: 0;
      padding: 30px 10px 20px;
      display: flex;
      align-items: center;
      flex-direction: column;
      gap: 20px;
    }
    .card .box .content h2 {
      width: 100%;
      padding-left: 110px;
      text-transform: uppercase;
      font-size: 1.15em;
      letter-spacing: 0.1em;
      font-weight: 600;
      line-height: 1.1em;
      color: #333;
    }
    .card .box .content h2 span {
      font-size: 0.75em;
      font-weight: 400;
      letter-spacing: 0.05em;
      color: #e91e63;
      text-transform: initial;
    }
    .card .box .content ul {
      position: relative;
      top: 15px;
      display: grid;
      grid-template-columns: repeat(3,1fr);
      width: 100%;
      padding: 0 10px;
      justify-content: space-evenly;
    }
    .card .box .content ul li {
      list-style: none;
      display: flex;
      flex-direction: column;
      text-align: center;
      padding: 0 10px;
      font-size: 0.85em;
      font-weight: 500;
      color: #999;
    }
    .card .box .content ul li:not(:last-child) {
      border-right: 3px solid #ccc;
    }
    .card .box .content ul li span {
      font-size: 1.65em;
      color: #333;
    }
    .card .box .content button {
      position: relative;
      top: 20px;
      padding: 8px 30px;
      border: none;
      outline: none;
      background: #03a9f4;
      border-radius: 30px;
      color: #fff;
      font-size: 1em;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      font-weight: 500;
      cursor: pointer;
      border: 5px solid var(--clr);
      box-shadow: 0 0 0 15px #fff;
      transition: 0.5s;
    }
    .card .box .content button:hover {
      letter-spacing: 0.5em;
      background: #ff3d7f;
    }
    .card .box .content a {
      text-decoration: none;
      list-style-type: none;
      color: #fff;
    } 
  </style>
</head>
<body>
  <div class="card">
    <div class="box">
      <div class="imgBx">
        <video src="/priroda_960x540-10s.mp4" type="video/mp4" autoplay loop muted>
      </div>
    </div>
    <div class="box">
      <div class="content">
        <h2>Boris Smolin<br><span>Web Designer</span><br><span><b>Ukraine 🇺🇦</b></span></h2>
        <ul>
          <li>HTML<span>93%</span></li>
          <li>CSS<span>48%</span></li>
          <li>JS<span>27%</span></li>
        </ul>
        <button><a href="https://smolin55.github.io/Business-card/">contact</a></button>
      </div>
    </div>
    <div class="circle">
      <div class="imgBx">
        <img src="/bor_285x285.png">
      </div>
    </div>
  </div>
</body>
</html>
