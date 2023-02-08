<script>
</script>

<body>
    <div class="cards" >
        <div class="card">
            <h1>cat skills.txt</h1>
           <p>Intermediate Python 🐍 programmer <br>
            Fluent in Czech 🇨🇿 and English 🏴󠁧󠁢󠁥󠁮󠁧󠁿 <br>
            Beginner linux 🐧 user <br>
            Learning C# 🙈🪒 and web development 🕸️</p>
        </div>
      <div class="card">
      <h1>whoami</h1>
         <p>Hi my name is Josh and I'm a 16 year-old Czech 🇨🇿 programmer 🧑‍💻</p>
      </div>
     <div class="card">
        <h1>./hobbies.sh</h1>
           <p>Playing video games 🎮, cycling 🚲, reading 📖, watching films 📺</p>
        </div>
     </div>
   </body>

<style>
      .cards {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 3em;
            padding: 1em;
            width: 90%;
            margin: 0 auto;
        }
      .card {
        box-shadow: 0 15px 30px rgba(0,0,0,0.30), 0 11px 8px rgba(0,0,0,0.22);
        box-sizing: border-box;
        height: 350px;
        transition-duration: 0.5s;
        border-radius: 15px;
        opacity: 0.6;
        background-color: var(--shade);
        position: relative;;
      }

      .card > h1 {
         width: 230px;
         font-weight: 1000;
         margin: 1em auto 0 auto;
         color: var(--light);
         border-radius: 15px;
      }
      .card > p {
         font-weight: 100;
         margin: 1em 1em 0 1em;
         text-align: center;
         text-transform: uppercase;
         color: var(--light);
      }
      .card:hover{
         opacity: 1;
         border: var(--light) 10px solid;
         transform: scale(1.05);
         border-radius: auto;
         animation: none;
      }
      @media screen and (max-width: 1000px) {
         .cards {
            grid-template-columns: 1fr;
            width: 90%;
            padding: 0;
         }
         .card {
            width: 100%;
            padding: 1em;
         }
      }
      @media screen and (min-height: 1200px) {
         .card {
            height: 700px;
         }
         .card > h1 {
            font-size: 3em;
         }
         .card > p {
            font-size: 2em;
         }
      }

</style>