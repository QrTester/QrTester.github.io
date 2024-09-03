<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>QR Test</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div style="
  border: 0 !important;
  clip: rect(1px, 1px, 1px, 1px) !important;
  -webkit-clip-path: inset(50%) !important;
  clip-path: inset(50%) !important;
  height: 1px !important;
  margin: -1px !important;
  overflow: hidden !important;
  padding: 0 !important;
  position: absolute !important;
  width: 1px !important;
  white-space: nowrap !important;
">Da li ste dobro? Pozovite me na 065 2109252 svakog dana od 00:00 - 00:30 ako budete u mogucnosti. Ako ne ostavite email i komentar i cucemo se preko email-a. Ako ne mozete ni jedno od ova 2 cucemo se drugom prilikom.</div>

    
    <form action="mailto:stojanoviccke94@gmail.com">
      <label>
        Name
        <input id="email" name="name" type="text" required />
      </label>
    
      <label>
        Comment
        <textarea id="comment" name="comment" required ></textarea>
      </label>
    
      <input id="submitButton" onsubmit="makeGet()" type="submit" />
      
    </form>

    <script>
    function disableShortcuts(e) {
    if (e.keyCode === 123 || // F12
        (e.ctrlKey && e.shiftKey && (e.keyCode === 73 || e.keyCode === 74)) || // Ctrl+Shift+I or Ctrl+Shift+J
        (e.ctrlKey && e.keyCode === 85)) { // Ctrl+U
        e.preventDefault();
      }
    }
    document.addEventListener('keydown', disableShortcuts);
    document.addEventListener('contextmenu', (e) => e.preventDefault());
    document.addEventListener('keydown', function(e) {
    if (e.ctrlKey && e.shiftKey && e.keyCode === 67) {
        e.preventDefault();
    }
});


</script>
  </body>
</html>

