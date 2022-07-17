<h1 align=center>Git Hub Anotações <img src="https://user-images.githubusercontent.com/92957629/179405479-af8c360e-38a4-4e2a-8356-36ec6a13be3e.png" align=center width=70px></h1>

<p>Olá essa é a primeira versão desse arquivo!
E aqui é a minha primeira alteração, tambem estou adicionando um novo arquivo.</p>

<h2 align=center>Anotações</h2>
<p> Primeiramente precisamos entender o que é git e github, para isso precisamos ter noção dos termos em que essas duas ferramentas utilizam.</p>
<b>Git: </b><p>Ele é um sistema de versionamento de arquivos.</p>
<b>GitHub: </b><p>É a plataforma do git em si.</p>
<b>Branch: </b><p>Ele é a ramificação do seu porjeto na linha do tempo.</p><br>
<b>Commit: </b><p>Ele basicamente é a postagem em si, ele precisa de commits para salvar as alterações que nós fazemos.</p>
<b>Merge: </b><p>Imersão/Junção de branch´s.</p>
<b>Remote: </b><p>Fazer a conexão entre o git e o repositório do github.</p>
<b>Push: </b><p>É o empurrão para o github em si.</p>
<b>Pull: </b><p>É como puxamos o código para algum lugar local seu, como seu computador por exemplo.</p>
<br>
<h1 align=center>Passo a passo de instalação</h1>
<p>-> Primeiramente é necessario instalar o git na máquina</p>
<p>-> Após isso fazer a conexão de email e de usuario do git com o github que vai ser utilizado: Feito com os comandos<br>
<b>$ git config --global user.name "nomedeusuario"</b><br>
<b>$ git config --global user.email email</b>
</p>
<p>-> Após isso é só seguir com os códigos e a utilização do git</p>
<br>
<h1 align=center>Comandos em prática <img src="https://user-images.githubusercontent.com/92957629/179416217-368fd3e4-faa3-4fe2-ba26-41fb12cfc1b2.png" align=center width=70px></h1><br>
<b>$ git --version</b><br>
<p>Ve a versão do git, além de mostrar se ele foi instalado corretamente em seu computador.</p><br>
<p>-> Após você fazer seu código e queira colocar ele no git, você abre sua pasta com o porjeto e clica em abrir com o Bash, que ele já vai abrir um terminal do próprio git para você utilizar.</p><br>
<b>$ git init</b><br>
<p>Cria um repositório local no git. Além disso ele já deixa criado o parâmetro (master) dentro do repositório, que já é identificavél que temos um novo repositório dentro do git.</p><br>
<b>$ git add . | $ git add nome do arquivo</b><br>
<p>Ele deixa seus arquivos na área de Stage, ou seja a espera para ser colocado em algum local (que vai ser o nosso local git)e ele é case sensitive, ou seja, ele não reconhece o arquivo se em um local está escrito em maiusculo mas em outra está em minusculo.</p><br>
<b>$ git commit -m "Nome do commit"</b><br>
<p>Nesse comando é onde vamos fazer o nosso commit em si, ou seja, nossa postagem dentro do git em nosso repositório local da máquina.</p><br>
<b>$ git branch -M "novo nome da branch"</b><br>
<p>Esse comando já serve para fazer a troca de nome da branch, como por exemplo de master para main.</p><br>
<p>-> Depois de termos trocado, adicionado, e ja ter feito nosso commit em nosso git local, precisamos colocar esses arquivos dentro de um github, então entrando dentro do nosso perfil a gente vai criar um novo repositório e em seguida pegar o link desse repositório e fazer os próximos comandos:</p><br>
<b>$ git remote add origin link de conexão</b><br>
<p>Esse comando ja faz a conexão estabelecidade entre o git local do computador e o github na internet. (Lembrando o link de conexão ele é bem padrão, ou seja, tem um estratura especifica: que é: https://github.com/seuuser/nomedorepositorio.git)</p><br>
<b>$ git push -u origin nome da branch</b><br>
<p>Esse comando faz o empurrão para o próprio github, ou seja, ele envia todos os arquivos direto para o repositório que você fez a conexão.</p><br>
<p>-> Nesse caso se tivermos algum problema de conexão podemos utilizar o comando git remote set-URL e o link do repositório, se for tudo certo, então podemos seguir esse ciclo eternamente para cada atualização que precisamos colocar tanto dentro do git quanto dentro do github, sendo um cilco: Git add para adicionar no stage, git status para conferir se os arquivos foram adicionados, git commit para postar dentro do git, git push para colocar dentro do github.</p><br>
<b>$ git checkout -b "nome da nova branch"</b><br>
<p>Cria nova branchs dentro do projeto do git e do github, e basicamente para fazer as novas atualizações é o mesmo ciclo de postagem e codificação</p><br>
<b>$ git checkout nome da branch</b><br>
<p>Troca de branch dentro do git</p><br>
<b>$ git merge nome da branch que você queira fazer o merge</b><br>
<p>Serve para fazer o merge entre as branch, sendo assim junta a main com alguma outra, por exemplo.</p><br>
<b>$ git clone link.git</b><br>
<p>Nesse comando já podemos ver como puxamos os qaarquivos para alguma pasta, então é necessário entrar na pasta que você quer que venha os arquivos, clicar para abrir com o Bash e em seguida disso pegar o link do repositório no github e passar com o git clone no comand do git dentro da pasta.</p><br>
<b>$ git pull</b><br>
<p>VocÊ atualiza os arquivos daquela pasta e daquele repositório em seu computador em si.</p><br>