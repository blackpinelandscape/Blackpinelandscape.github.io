--green:#596F2A;   /* matched to your logo */
      --text:#1a1a1a;
      --bg:#ffffff;
      --max:860px;
    }
    html,body {
      margin:0;
      padding:0;
      background:var(--bg);
      color:var(--text);
      font: 400 18px/1.7 system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;
    }
    .wrap {
      max-width:var(--max);
      margin:0 auto;
      padding:40px 22px;
      text-align:center;
    }
    img.logo {
      width:40vw;          /* responsive */
      max-width:200px;     /* don’t get too big */
      height:auto;         /* preserve aspect ratio */
      margin:0 auto 24px;
      display:block;
    }
    h1 {
      margin:0 0 32px;
      color:var(--green);
      font-weight:800;
      letter-spacing:.08em;
      text-transform:uppercase;
      font-size: clamp(28px, 5vw, 50px);
    }
    p {
      margin:0 auto 18px;
      text-align:left;
    }
    .sig {
      margin-top:28px;
      font-weight:600;
      text-align:center;
    }
    .phone a {
      color:var(--green);
      text-decoration:none;
      border-bottom:1px solid rgba(89,111,42,.35);
    }
    .phone a:hover {
      border-bottom-color:transparent;
    }
  </style>
</head>
<body>
  <main class="wrap">
    <!-- Logo -->
    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/defcdc82-43d7-49a7-acf3-759f1e577951" />


    <!-- Company name -->
    <h1>BLACK PINE LANDSCAPE</h1>

    <!-- Main description -->
    <p>Arboriculture is more than just my profession—it’s my passion. I specialize in the traditional Japanese Sukashi style of pruning, an art form that emphasizes balance, beauty, and intention. My focus is on blending these timeless techniques with modern arboricultural practices to bring out the best in every tree.</p>

    <p>With years of experience caring for and maintaining trees of all sizes, I’ve built Black Pine Landscape as an intentionally small company. This ensures that nothing is lost in translation—you’ll be working directly with me from start to finish, receiving both my expertise and my personal attention at every step.</p>

    <!-- Signature and contact -->
    <div class="sig">Alex Hacké</div>
    <div class="phone"><a href="tel:+15039365900">503.936.5900</a></div>
  </main>
</body>
</html>
