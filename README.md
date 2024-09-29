<div align="center">
 <h1>Desenvolvimento Web</h1>
</div>

<div align="center">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original-wordmark.svg" width="200" height="200" />
</div>
<div align="center">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="150" height="150" />
</div>

<div align="center">
  <h2>Laboratório 64</h2> 
</div>

<br>
<h3>No LAB64, criamos um server utilizando Node.JS</h3>
<br>
<br>
<strong>Entre na pasta do LAB64 antes de digitar qualquer comando!</strong>


<h4>--> Comando para rodar o server:</h4>
<strong>node server.js</strong> 

<h3>**LINKS**</h3> 
<h6>Página inicial:</h6>
<strong>http://localhost:3000/</strong>
<br>
<h6>Sobre nós:</h6>
<strong>http://localhost:3000/sobre</strong>
<br>
<h6>Upload de arquivos:</h6>
<strong>http://localhost:3000/upload</strong>
<h6>Erro 404:</h6>
<strong>http://localhost:3000/'qualquercoisa'</strong>
<br>
<br>

<h3>Comandos para Teste</h3>
<strong>Testar a página inicial:</strong>
curl http://127.0.0.1:3000/
<br>
<strong>Testar a página Sobre:</strong>
curl http://127.0.0.1:3000/sobre
<br>
<strong>Upload de arquivo:</strong>
curl -X POST -F "file=@caminho_para_arquivo/arquivo.txt" http://127.0.0.1:3000/upload
<br>
OBS: Substitua caminho_para_arquivo/arquivo.txt pelo caminho real do arquivo que você deseja enviar.

