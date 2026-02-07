# Wirbellose-Tiere-
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Biologie 7 – Wirbellose entdecken</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      background: #f4f8fb;
      color: #222;
    }
    header {
      background: #2e7d32;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      color: #2e7d32;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 30px;
      background: white;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 12px;
      vertical-align: top;
    }
    th {
      background: #e8f5e9;
      text-align: left;
    }
    .task {
      background: #f1f8e9;
      padding: 10px;
      border-left: 5px solid #7cb342;
      margin: 5px 0;
    }
    .portfolio {
      background: #e3f2fd;
      border-left: 5px solid #1976d2;
      padding: 10px;
      margin-top: 10px;
    }
    button {
      background: #2e7d32;
      color: white;
      border: none;
      padding: 8px 12px;
      cursor: pointer;
      border-radius: 4px;
      margin-top: 5px;
    }
    button:hover {
      background: #1b5e20;
    }
    .hidden {
      display: none;
    }
    footer {
      background: #c8e6c9;
      padding: 15px;
      text-align: center;
      font-size: 0.9em;
    }
  </style>

  <script>
    function toggle(id) {
      const el = document.getElementById(id);
      el.classList.toggle("hidden");
    }
  </script>
</head>

<body>

<header>
  <h1>🦋 Biologie 7 – Wirbellose entdecken</h1>
  <p>Interaktive Unterrichtseinheit (Realschule Niedersachsen)</p>
</header>

<section>
  <h2>Überblick über die Unterrichtseinheit</h2>
  <p>
    In dieser Einheit erforschst du die faszinierende Welt der <strong>Wirbellosen</strong>.
    Der Schwerpunkt liegt auf <strong>Insekten</strong>, zusätzlich lernst du alle
    <strong>Weichtiergruppen</strong> kennen.  
    Du arbeitest forschend, kreativ und sammelst deine Ergebnisse in einem
    <strong>Portfolio</strong>.
  </p>
</section>

<section>
  <h2>Unterrichtsverlauf (10 Doppelstunden à 90 Minuten)</h2>

  <table>
    <tr>
      <th>Doppelstunde</th>
      <th>Thema</th>
      <th>Was lernst du?</th>
      <th>Deine Aufgaben</th>
    </tr>

    <tr>
      <td>1–2</td>
      <td>Einführung: Wirbellose Tiere</td>
      <td>
        • Unterschied Wirbeltiere / Wirbellose<br>
        • Überblick über Tiergruppen<br>
        • Warum Insekten so erfolgreich sind
      </td>
      <td>
        <div class="task">
          🔍 Recherchiere: Welche Wirbellosen kennst du aus deinem Alltag?
        </div>
        <div class="task">
          🧠 Ordne Tiere richtig zu (Insekten, Spinnentiere, Weichtiere …)
        </div>
        <div class="portfolio">
          📁 Portfolio: Mindmap „Wirbellose Tiere“
        </div>
      </td>
    </tr>

    <tr>
      <td>3–4</td>
      <td>Insekten – Bau und Merkmale</td>
      <td>
        • Körperbau der Insekten<br>
        • Bedeutung von Beinen, Flügeln und Mundwerkzeugen
      </td>
      <td>
        <div class="task">
          🔬 Untersuche Insekten mit Lupe oder Mikroskop
        </div>
        <div class="task">
          ✏️ Zeichne ein Insekt und beschrifte es
        </div>
        <div class="portfolio">
          📁 Portfolio: Insekten-Steckbrief
        </div>
      </td>
    </tr>

    <tr>
      <td>5–6</td>
      <td>Entwicklung von Insekten</td>
      <td>
        • Metamorphose verstehen<br>
        • Entwicklungsstadien vergleichen
      </td>
      <td>
        <div class="task">
          🐛 Beobachte Raupen oder Videos zur Metamorphose
        </div>
        <div class="task">
          📸 Dokumentiere Veränderungen
        </div>
        <div class="portfolio">
          📁 Portfolio: Entwicklungsreihe (Text + Bild)
        </div>
      </td>
    </tr>

    <tr>
      <td>7–8</td>
      <td>Weichtiere: Schnecken, Muscheln, Tintenfische</td>
      <td>
        • Bauplan der Weichtiere<br>
        • Fortbewegung und Lebensräume
      </td>
      <td>
        <div class="task">
          🐌 Beobachte eine Schnecke genau
        </div>
        <div class="task">
          🧩 Vergleiche Schnecke – Muschel – Tintenfisch
        </div>
        <div class="portfolio">
          📁 Portfolio: Vergleichstabelle Weichtiere
        </div>
      </td>
    </tr>

    <tr>
      <td>9–10</td>
      <td>Wirbellose im Ökosystem & Nachhaltigkeit</td>
      <td>
        • Rolle der Wirbellosen im Wald<br>
        • Bedeutung für den Menschen
      </td>
      <td>
        <div class="task">
          🌳 Untersuche Laubstreu oder Bodenproben
        </div>
        <div class="task">
          💬 Diskutiere: Warum brauchen wir Insekten?
        </div>
        <div class="portfolio">
          📁 Portfolio: Reflexion „Warum Wirbellose schützen?“
        </div>
      </td>
    </tr>
  </table>

  <button onclick="toggle('hilfe')">💡 Lernhilfe ein-/ausblenden</button>
  <div id="hilfe" class="hidden">
    <p>
      <strong>Tipp:</strong> Nutze dein Portfolio nicht nur zum Sammeln,
      sondern auch zum Nachdenken:  
      <em>Was habe ich gelernt? Was war schwierig? Was hat mich überrascht?</em>
    </p>
  </div>

</section>

<footer>
  Biologie 7 · Wirbellose · Realschule Niedersachsen · Kompetenzorientierter Unterricht
</footer>

</body>
</html>
