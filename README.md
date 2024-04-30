
  font-size: 1.2rem;
  padding: 1rem 2.5rem;
  border: none;
  outline: none;
  border-radius: 0.4rem;
  cursor: pointer;
  text-transform: uppercase;
  background-color: rgb(14, 14, 26);
  color: rgb(234, 234, 234);
  font-weight: 700;
  transition: 0.6s;
  box-shadow: 0px 0px 60px #1f4c65;
  -webkit-box-reflect: below 10px linear-gradient(to bottom, rgba(0,0,0,0.0), rgba(0,0,0,0.4));
}

.btn:active {
  scale: 0.92;
}

.btn:hover {
  background: rgb(2,29,78);
  background: linear-gradient(270deg, rgba(2, 29, 78, 0.681) 0%, rgba(31, 215, 232, 0.873) 60%);
  color: rgb(4, 4, 38);
}



<!DOCTYPE html>
<html lang="pt-br">
<head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Robsu</title>
     <link rel="stylesheet" href="style.css">
</head>
<body>
          <main>
               <header>
                    <h1>header</h1>
               </header>
               <section>
                    <h1>section</h1>
               </section>
               <section>
                    <h1>section</h1>
               </section>
               <footer>
                    <h1>footer</h1>
               </footer>
          </main>
             

</body>
</html>


* {
     margin: 0;
     padding: 0;
     box-sizing: border-box;

}

main {
     border: 1px solid black;
     max-width: 1200px;
     margin: auto;
     height: 100vh;

}

header, footer, section {
     border: 1px solid black;
     margin: 1.2rem;
     text-align: center;
     background-color:#f0f8ff;
}

