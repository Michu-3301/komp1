<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="utf-8">
  <title>Komponenty komputerowe</title>
  <meta name="description" content="Serwis prezentuje komponenty komputerowe. Sprawdź, czy znasz je wszystkie">
  <meta name="keywords" content="komputery, procesory, karty graficzne, GPU, CPU, płyta główna, ziemniak">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <style>
    #container {
      width: 1000px;
      margin: 0 auto;
    }
    #logo {
      background-color: black;
      color: white;
      text-align: center;
      padding: 15px;
    }
    #nav {
      float: left;
      background-color: lightgray;
      width: 120px;
      min-height: 850px;
      padding: 10px;
    }
    #content {
      float: left;
      padding: 20px;
      width: 640px;
    }
    #ad {
      float: left;
      width: 160px;
      min-height: 850px;
      padding: 10px;
      background-color: lightgray;
    }
    #footer {
      clear: both;
      background-color: black;
      color: white;
      text-align: center;
      padding: 20px;
    }
    #proc {
      width: 160px;
      margin: 20px auto;
      padding: 10px;
      background-color: blue;
      text-align: center;
    }
    #proc img {
      width: 100%;
    }
  </style>
</head>
<body>
  <div id="container">
    <div id="logo">
      <h1>Komponenty komputerowe</h1>
    </div>

    <div id="nav">
      Komponenty Komputerowe:
      <br><br>
      <a href="Procesor.html">- Procesor</a><br><br>
      <a href="Płyta Główna.html">- Płyta Główna</a><br><br>
      <a href="Karta Graficzna.html">- Karta Graficzna</a><br><br>
      <a href="Pamięć Ram.html">- Pamięć Ram</a><br><br>
      <a href="Zasilacz.html">- Zasilacz</a><br><br>
      <a href="Chłodzenie.html">- Chłodzenie</a><br><br>
      <a href="Dysk.html">- Dysk HDD/SSD</a><br>
    </div>

    <div id="content">
      <h2>Procesor – serce każdego komputera</h2>
      <p>
        Procesor, znany też jako CPU (Central Processing Unit), to jeden z najważniejszych komponentów komputera. To on wykonuje wszystkie obliczenia i przetwarza polecenia, dzięki czemu komputer może działać. Procesory różnią się liczbą rdzeni – im więcej rdzeni, tym więcej zadań może być wykonywanych jednocześnie. Ważna jest też ich częstotliwość, wyrażana w gigahercach (GHz), która wpływa na szybkość działania. Współczesne procesory są bardzo zaawansowane technologicznie – posiadają własną pamięć podręczną, zarządzają poborem mocy i często mają zintegrowaną grafikę. Najpopularniejsi producenci to Intel i AMD. Dobór odpowiedniego procesora ma kluczowe znaczenie dla wydajności całego komputera – zarówno w codziennej pracy, jak i w grach czy programowaniu.
      </p>

      <div id="proc">
        <img src="proc.jpg" alt="Procesor">
      </div>
    </div>

    <div id="ad">
      <img src="reklama.jpg" alt="Reklama" width="160px">
    </div>

    <div id="footer">
      Komponenty komputerowe - Michu 3301 &copy; Wszelkie prawa zastrzeżone
    </div>
  </div>
</body>
</html>
