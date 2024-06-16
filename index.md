---
layout: default
---

Prova stile
<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tabella con Stile</title>
<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }

  table, th, td {
    border: 1px solid #ddd;
    padding: 8px;
  }

  th {
    background-color: #f2f2f2;
    color: black;
  }

  tr:nth-child(even) {
    background-color: #f9f9f9;
  }

  tr:hover {
    background-color: #f1f1f1;
  }

  th {
    padding-top: 12px;
    padding-bottom: 12px;
    text-align: left;
  }
</style>
</head>
<body>

<table>
  <tr>
    <th>Colonna 1</th>
    <th>Colonna 2</th>
    <th>Colonna 3</th>
  </tr>
  <tr>
    <td>Valore 1</td>
    <td>Valore 2</td>
    <td>Valore 3</td>
  </tr>
  <tr>
    <td>Valore 4</td>
    <td>Valore 5</td>
    <td>Valore 6</td>
  </tr>
</table>

</body>
</html>

