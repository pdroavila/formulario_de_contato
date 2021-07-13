# Formulário de Contato
Esse foi meu primeiro formulário usando somente HTML e CSS.

## Código HTML:
```bash
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

```

## Código CSS:
  ```bash
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Lato', sans-serif;
}

body {
  background-color: #27282d;
}

.form {
  padding: 20px;
}

.form h1 {
  text-align: center;
  margin-top: 150px;
  padding: 35px;
  color: white;
  text-shadow: rgb(46, 119, 255) 1.5px 1.5px;
  
}

.form input {
  padding-left: 10px;
  display: block;
  max-width: 500px;
  width: 100%;
  height: 30px;
  border: 1px solid #ccc;
  margin: 20px auto;
  border-radius: 5px;
}

.form textarea {
  padding-left: 10px;
  padding-top: 10px;
  resize: none;
  display: block;
  margin: 10px auto;
  border-radius: 5px;
  height: 120px;
  max-width: 500px;
  width: 100%;
}

.form input[type=submit]:hover {
  padding-left: 10px;
  display: block;
  max-width: 500px;
  width: 100%;
  height: 30px;
  color: white;
  border: 0;
  margin: 20px auto;
  cursor: pointer;
  background-color: rgb(0, 65, 187);
}
  ```

