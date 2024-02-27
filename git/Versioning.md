<div>
    <div>
        <h2  style="text-align:center;">Como funciona um Commit</h2>
        <p>O processo de levar um pastas e arquivos para o repositório local acontece em 3 etapas, representadas na imagem abaixo:</p>
        <img src="assets\img/gitCommit.png" alt="Git Commit" style="width:100%"/>
        <p>A primeira parte, em laranja, representa <strong>pastas e arquivos no computador do desenvolvedor</strong>, onde ele as criou, alterou ou as deletou. Para enviar para etapa seguinte, basta utilizar <code>git add</code></p>
        <p>A segunda parte, em amarelo, representa algo chamado <strong>Area de Teste ou Indice</strong>. É uma área intermediária onde os commits podem ser formatados e revisados antes de serem concluídos. Para enviar para etapa seguinte, basta utilizar <code>git commit -m ""</code> ou <code>git commit -am ""</code> para enviar o commit da primeira etapa até a terceita.</p>
        <p>Por fim, na terceira parte, em azul, representa o repositório local, Git. Lugar onde sao armazenados, de forma cronológica os commits do desenvolvedor.</p>
        <ul style="text-align:center; list-style-type: none;">
            <li>&#128193; Working Directory = Pasta de Trabalho
            <li>&#9888; Staging Area = Area de Teste
            <li>&#9745; Repository = Repositório
        </ul>
    <div>
    <div>
        <h2  style="text-align:center;">Versionamente / Armazenamento de commits</h2>
        <p>Após realizar seus commits/checkpoints, o Git guarda-os em um histórico representado abaixo:</p>
        <img src="assets\img/HistoricoDoGit.png"/>
        <p style="text-align:center;">C0 = Commit 0 | C1 = Commit 1 | C2 = Commit 2<br>master e iss53= nome da branch atual</p>
        <p>A cada commit realizado, o novo commit aponta uma referencia para o commit anterior, assim como as setas repesentam na imagem, preservando seu historico.</p>
    <div>
</div>