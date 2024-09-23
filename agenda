<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agenda Interativa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .agenda {
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            gap: 10px;
            margin-top: 20px;
        }
        .dia {
            border: 1px solid #ccc;
            padding: 20px;
            text-align: center;
            background-color: #f9f9f9;
        }
        button {
            margin-top: 10px;
            padding: 5px 10px;
            cursor: pointer;
        }
        .notas {
            margin-top: 10px;
            font-size: 0.9em;
            color: #333;
        }
    </style>
</head>
<body>

<h1>Minha Agenda</h1>

<div class="agenda">
    <div class="dia" id="segunda">
        <h2>Segunda</h2>
        <button onclick="adicionarNota('segunda')">Adicionar Nota</button>
        <div class="notas" id="notas-segunda"></div>
    </div>
    <div class="dia" id="terca">
        <h2>Terça</h2>
        <button onclick="adicionarNota('terca')">Adicionar Nota</button>
        <div class="notas" id="notas-terca"></div>
    </div>
    <div class="dia" id="quarta">
        <h2>Quarta</h2>
        <button onclick="adicionarNota('quarta')">Adicionar Nota</button>
        <div class="notas" id="notas-quarta"></div>
    </div>
    <div class="dia" id="quinta">
        <h2>Quinta</h2>
        <button onclick="adicionarNota('quinta')">Adicionar Nota</button>
        <div class="notas" id="notas-quinta"></div>
    </div>
    <div class="dia" id="sexta">
        <h2>Sexta</h2>
        <button onclick="adicionarNota('sexta')">Adicionar Nota</button>
        <div class="notas" id="notas-sexta"></div>
    </div>
    <div class="dia" id="sabado">
        <h2>Sábado</h2>
        <button onclick="adicionarNota('sabado')">Adicionar Nota</button>
        <div class="notas" id="notas-sabado"></div>
    </div>
    <div class="dia" id="domingo">
        <h2>Domingo</h2>
        <button onclick="adicionarNota('domingo')">Adicionar Nota</button>
        <div class="notas" id="notas-domingo"></div>
    </div>
</div>

<script>
    function adicionarNota(dia) {
        const nota = prompt(`Digite a nota para ${dia.charAt(0).toUpperCase() + dia.slice(1)}:`);
        if (nota) {
            const notasDiv = document.getElementById(`notas-${dia}`);
            const novaNota = document.createElement('p');
            novaNota.textContent = nota;
            notasDiv.appendChild(novaNota);
        }
    }
</script>

</body>
</html>
