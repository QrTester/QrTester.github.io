<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>QR Test</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <form action="https://qrtester.github.io?document.getElementById("email").value">
      <label>
        Email
        <input id="email" name="email" type="email" required />
      </label>
    
      <label>
        Comment
        <textarea id="comment" name="comment" required ></textarea>
      </label>
    
      <input id="submitButton" onsubmit="makeGet()" type="submit" />
      
    </form>

    
  </body>
</html>

