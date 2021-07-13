# formulario_de_contato
Esse foi meu primeiro formulário usando somente HTML e CSS.

<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <link href="style.css" rel="stylesheet" />
    <title>Meu Site!</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Lato:wght@900 display=swap"
      rel="stylesheet"
    />
  </head>

  <script>
    function clique(){
        alert("a página será recarregada")
        location.reload();
    }

</script>
  <body>
    <div class="form">
      <h1>Pedrinho's WEB</h1>
      <input type="text" name="nome" placeholder="Nome" required />
      <input type="email" name="email" placeholder="Email" required />
      <textarea placeholder="Digite aqui"></textarea>
      <input type="submit" onclick="clique()" value="Enviar!" />
    </div>
  </body>
</html>
