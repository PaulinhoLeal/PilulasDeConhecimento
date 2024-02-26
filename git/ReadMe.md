<h1 style="text-align:center;">Git e GitHub</h1>

<h2 style="text-align:center;">O que é Git e Github</h2>
<div>
    <h3 style="text-align:center; margin-bottom: -20px">Git</h3>
    <div style="  display: flex; justify-content: center; align-items: center; margin: 25px;">
        <div>
            <img src="assets\img\GitIcon.png" alt="Icone do Git"/>
        </div>
        <div>
            <ul>
                <li>Git é um sistema de controle de versão local.
                <li>Git ajuda você a acompanhar as alterações no código.
                <li>Git é usado para colaborar no código.
            </ul>
        </div>
    </div>
</div>

<div>
    <h3 style="text-align:center; margin-bottom: -20px">Github</h3>
    <div style="  display: flex; justify-content: center; align-items: center; margin: 25px;">
        <div>
            <img src="assets/img/GithubIcon.png" alt="Icone do Github"/>
        </div>
        <div>
            <ul>
                <li>Plataforma que permite controle de versão remoto.
                <li>Plataforma que permite gerenciamento de projetos.
                <li>Plataforma que permite hospedagem de código e código.
            </ul>
        </div>
    </div>
</div>

<div>
    <h2 style="text-align:center;">Para que serve?</h2>
    <div>
    <h3>Git</h3>
        <p>Gerenciar pastas e arquivos, permitindo voltar na linha do tempo através de um histórico, e coordenar o trabalho de pessoas em um repositório compartilhado.<br> Cada "commit" realizado no Git pode ser pensado como um "CheckPoint" em seu repositório.</p>
    </div>
    <div>
        <h3>Github</h3>
        <p>Permite criar, armazenar, gerenciar, compartilhar código, além de muitas outras coisas.</p> <!-- Melhorar aqui -->
    </div>
</div>

****
<div>
    <h2 style="text-align:center;">Comando Basicos</h2>
    <p>Para visualizar os comandos basicos e mais usados do Git, basta digitar "git" em seu git bash.</p>
    <p>Obs.: existem outros comandos do git, mas na maioria dos casos os comandos abaixo irao sanar suas necessidades.</p>
    <div>
        <h3>Comandos mais utilizado</h3>
        <ul>
            <h4>iniciar uma área de trabalho</h4>
            <li><code>clone</code> - Clonar um repositório em um novo diretório
            <li><code>init</code> - Crie um repositório Git vazio ou reinicialize um existente
        <br>
            <h4>Trabalhar na mudança atual</h4>
            <li><code>add</code> - Adicione o conteúdo do arquivo ao índice
            <li><code>mv</code> - Mover ou renomear um arquivo, diretório ou link simbólico
            <li><code>restore</code> - Restaurar arquivos da árvore de trabalho
            <li><code>rm</code> -  Remove arquivos da árvore de trabalho e do índice
        <br>
            <h4>Examinar a história e o status</h4>
            <li><code>status</code> - Mostrar o status da árvore de trabalho
            <li><code>log</code> - Mostrar registros de commit
        <br>
            <h4>Adicionar, marcar e ajustar sua história de commits</h4>
            <li><code><a href="#">branch</a></code> - Lista, cria, ou deleta branches
            <li><code>commit</code> - Registrar alterações no repositório
            <li><code>merge</code> - Junta duas ou mais branches
            <li><code>rebase</code> - Junta duas ou mais branches organizando seus históricos para tratar conflitos
        <br>
            <h4><a href="#">Colaboraçao</a></h4>
            <li><code>push</code> - Sincroniza seus repositório local com repositório remoto
            <li><code>pull</code> -  Baixa outro repositório remoto e integra com outro repositório local ou branch local
        </ul>
    </div>
    <div>
        <h3  style="text-align:center;">Como funciona o Git de forma visual</h3>
        <img src="assets/img/GitProcess.PNG" alt="Processo do Git" style="width:100%"/>
        <ul style="text-align:center; list-style: none;">
            <li>Working Directory = Diretório/Pasta de Trabalho
            <li>Staging Area/Index = Area de Prepato
        </ul>
    </div>
</div>
<div>
    <h2  style="text-align:center;">Versionamento com Git</h2>
    <p>Após realizar seus commits/checkpoints, o Git guarda-os em um histórico representado abaixo:</p>
    <img src="assets\img/HistoricoDoGit.png"/>
    <p style="text-align:center;">C0 = Commit 0 | C1 = Commit 1 | C2 = Commit 2<br>master e iss53= nome da branch atual</p>
    <p>A cada commit realizado, o novo commit aponta uma referencia para o commit anterior, assim como as setas repesentam na imagem, preservando seu historico.</p>
<div>

<div>
    <h2>Como Vincular Git ao Github(Remoto)</h2>
    <h3>Do Github para o Git</h3>
    <!--Criar o processo-->
    <h3>Do Git para o Github</h3>
    <p>Para vincular do Git ao Github, precisamos dar instrucoes de configuracao ao Git indicando qual repositório remoto queremos vincular ao repositório local que estamos trabalhando, alem da branch atual e da branch remota.</p>
    <p>Caso seu repositório do Github nao tenha nenhuma branch, o desenvolvedor pode simplesmente informar o repositório que deseja vincular que o Git configura, por padrao, a branch do Git com a do Github</p>

</div>

<h2>Como usar Branch</h2>
<p>Conteudo futuro...</p>

<h2>Como trabalhar em equipe com outros desenvolvedores</h2>
<p>Conteudo Futuro...</p>
