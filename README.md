<h3>Bem-vindo(a) ao meu perfil 😁</h3>

<div>
  <a href="https://github.com/JDLeader">
    <img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=JDLeader&theme=highcontrast&locale=pt_BR&mode=weekly&dates=EB5454&stroke=808080&border=808080&background=334155&fire=EB5454" alt="GitHub JDLeader" />
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JDLeader&layout=compact&langs_count=6&theme=tokyonight"/>
  </a>
</div>

<br>

<div>
  <img alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" />
  <img alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" />
  <img alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" />
</div>

<br>
  
<div> 
  <a href="https://www.youtube.com/JDLeader" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/JDLeader" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 <a href="https://discord.gg/" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 
  <a href = "joaodaniel.buenodemello@gmil.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/jd-mello/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>
<div>
 <html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botão de Créditos com Contribuições</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1a1a1a;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;

        /* Estilo do Botão Créditos */
        .btn-creditos {
            background-color: #238636; /* Verde padrão do GitHub */
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 16px;
            font-weight: bold;
            border-radius: 6px;
            cursor: pointer;
            transition: background-color 0.2s;
        }

        .btn-creditos:hover {
            background-color: #2ea043;
        }

        /* Estilo do Modal (Janela que vai abrir) */
        .modal {
            display: none; /* Escondido por padrão */
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            justify-content: center;
            align-items: center;
        }

        /* Conteúdo do Modal */
        .modal-content {
            background-color: #0d1117; /* Fundo escuro estilo GitHub */
            padding: 20px;
            border: 1px solid #30363d;
            border-radius: 10px;
            max-width: 600px;
            width: 90%;
            text-align: center;
            box-shadow: 0 4px 20px rgba(0,0,0,0.5);
            position: relative;
        }

        /* Botão de fechar (X) */
        .close-btn {
            position: absolute;
            top: 10px;
            right: 15px;
            color: #8b949e;
            font-size: 24px;
            cursor: pointer;
        }

        .close-btn:hover {
            color: #fff;
        }

        .modal-content h2 {
            margin-top: 0;
            color: #58a6ff;
        }

        /* Estilização dos Links e Imagens de Contribuição */
        .github-link {
            display: inline-block;
            margin-bottom: 20px;
            color: #58a6ff;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
        }

        .github-link:hover {
            text-decoration: underline;
        }

        .stats-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
            align-items: center;
        }

        .stats-container img {
            max-width: 100%;
            height: auto;
            border-radius: 6px;
        }
    </style>

    <button class="btn-creditos" onclick="abrirModal()">Créditos</button>

    <div id="modalCreditos" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="fecharModal()">&times;</span>
            
            <h2>Desenvolvido por JDleader</h2>
            
            <a href="https://github.com/JDleader" target="_blank" class="github-link">
                Visitar Perfil no GitHub ↗
            </a>

            <div class="stats-container">
                <a href="https://git.io/streak-stats" target="_blank">
                    <img src="https://streak-stats.demolab.com/?user=JDleader&theme=dark" alt="GitHub Streak" />
                </a>

                <img src="https://github-readme-stats.vercel.app/api?username=JDleader&show_icons=true&theme=dark&include_all_commits=true" alt="Status do GitHub" />
            </div>
        </div>
    </div>

    <script>
        function abrirModal() {
            document.getElementById("modalCreditos").style.display = "flex";
        }

        function fecharModal() {
            document.getElementById("modalCreditos").style.display = "none";
        }

        // Fecha o modal se o usuário clicar fora da caixinha preta
        window.onclick = function(event) {
            var modal = document.getElementById("modalCreditos");
            if (event.target == modal) {
                modal.style.display = "none";
            }
        }
    </script>
</a>
</div>
