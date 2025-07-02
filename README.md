# Intanationalshops
Online

<!DOCTYPE html>
<html lang="ha">
<head>
  <meta charset="UTF-8">
  <title>Bayyana Alaji Gayson</title>
</head>
<body>

  <!-- Maballin Next -->
  <button onclick="nunaRubutu()">Next</button>

  <!-- Rubutun da aka ɓoye -->
  <div id="alajigayson" hidden>
    <h2>Alaji Gayson</h2>
    <p>Wannan shine rubutun da aka ɓoye, yanzu ya bayyana.</p>
  </div>

  <!-- JavaScript -->
  <script>
    function nunaRubutu() {
      var rubutu = document.getElementById("alajigayson");
      rubutu.hidden = false; // cire boye
      rubutu.scrollIntoView({ behavior: "smooth" }); // jaka zuwa rubutun
    }
  </script>

</body>
</html>