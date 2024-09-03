<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>QR Test</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <form action="https://qrtester.github.io?${enteredValue}">
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

    <script>
      let enteredValue = "#";
      const submitButton = document.getElementById("submitButton");
      const email = document.getElementById("email");
      const comment = document.getElementById("comment");
      email.addEventListener("change", (event) => {
        enteredValue = email.event.target.value;
      }
    </script>
  </body>
</html>

