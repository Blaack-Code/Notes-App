# Boas vindas ao repositório do projeto Notes App!

 Neste repositório você vai encontrar tudo que precisa para desenvolver o projeto! <br>
 desde informações até tutoriais para a melhor execução, caso tenha alguma dúvida mande no Discord da comunidade!
 
 # Sumário
 
  - [Desenvolvimento](#desenvolvimento)
  - [Instruções para enviar o desafio](#instruções-para-enviar-o-desafio)
  - [Antes de começar a desenvolver](#antes-de-começar-a-desenvolver)
  - [Requisitos](#requisitos)
 
 # O que deverá ser desenvolvido?
 
 Neste projeto você vai desenvolver uma aplicação de anotações pessoais, ao utilizar essa aplicação um usuário deverá ser capaz de:
 <ul>
 <li>1 - Criar uma lista de tarefas</li>
 <li>2 - Criar parágrafos com conteúdo</li>
 <li>3 - Adicionar links a uma área de 'links importantes'</li>
 </ul>
 
 Para entregar o projeto a equipe deverá criar um Pull Request neste repositório. <br>
 A apresentação para a comunidade acontecerá no próximo sábado (18/12/2021) no nosso discord!
 Lembrando que não é uma competição! A colaboração entre as equipes é um prática que incentivamos aqui :D
 
 # Desenvolvimento
 
 O desenvolvimento do projeto pode ser escolhido pela equipe, deve apenas ser especificado como será desenvolvido <br>
 pessoas com conhecimento em um mesmo framework estarão na mesma equipe e podem optar por utilizá-lo ou não.
 
 # Instruções para enviar o desafio
 
 ### Antes de começar a desenvolver:

1. Clone o repositório
  * `git clone git@github.com:Blaack-Code/desafio-1-notes-app.git`
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd desafio-1-notes-app`
  * Vá para a branch do seu grupo, com `git checkout main-group-XX && git pull`, onde `XX` é o número do seu grupo. Exemplos: `main-group-1`, `main-group-22`.

2. Faça alterações separadas por novas branchs criadas a partir da branch `main-group-XX`, criando uma nova branch para cada demanda
  * Verifique que você está na branch `main-group-XX`
    * Exemplo: `git branch`
  * Se não estiver, mude para a branch `main-group-XX`
    * Exemplo: `git checkout main-group-XX && git pull`
  * Agora, crie uma branch para a demanda que você vai desenvolver do seu projeto
    * Você deve criar uma branch com uma breve descrição da demanda a ser desenvolvida
    * Exemplo: `git checkout -b main-group-XX-cria-campo-de-input`

3. Adicione as mudanças ao _stage_ do Git e faça um `commit`
  * Verifique que as mudanças ainda não estão no _stage_
    * Exemplo: `git status` (devem aparecer listadas as novas alterações em vermelho)
  * Adicione o arquivo alterado ao _stage_ do Git
      * Exemplo:
        * `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
        * `git status` (devem aparecer listadas as novas alterações em verde)
  * Faça seus `commit`
      * Exemplo:
        * `git commit -m 'cria componente de input'`
        * `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

4. Adicione a sua branch com o novo `commit` ao repositório remoto
  * Usando o exemplo anterior: `git push -u origin main-group-XX-cria-campo-de-input`

5. Crie um novo `Pull Request` _(PR)_
  * Vá até a página de _Pull Requests_ do repositório
  * Clique no botão verde _"New pull request"_
  * Clique na caixa de seleção _"Compare"_ e escolha a branch do grupo, `main-group-XX`, e a sua branch **com atenção**
  * Coloque um título para a sua _Pull Request_
    * Exemplo: _"[GRUPO XX] Cria tela de busca"_
  * Clique no botão verde _"Create pull request"_
  * Adicione uma descrição para o _Pull Request_ e clique no botão
 
 ### Requisitos
 
 ### Login
 <ol>
 
 <li>Desenvolva uma tela de login</li>
 <li>Crie um input para o usuário digitar o email</li>
 <li>Crie um input para o usuário digitar o nome</li>
 <li>Crie um botão "Entrar"</li>
 <li>Clicando no botão o usuário deve ser redirecionado para a tela principal e seu email e o nome devem ser salvos no localStorage</li>
 <li>O botão deve estar desativado se algum input estiver vazio</li>
 
 </ol>
 
 ### Tela principal
 <ol>
 
 <li>Desenvolva uma tela principal</li>
 <li>Crie um header com as informações do usuário e o nome da aplicação</li>
 <li>Crie uma mensagem de boas-vindas caso o usuário não tenha nenhuma anotação</li>
 <li>Crie uma área onde o usuário poderá adicionar uma nova anotação</li>
 <li>Na área citada acima deverá ser possível: Criar uma anotação de texto, criar uma lista de tarefas, adicionar um link útil e/ou criar listas ordenadas!</li>
 <li>Deverá ser possível excluir uma anotação</li>
 <li>Deverá ser possível esconder e mostrar a área citada acima</li>
 <li>Crie uma área prícipal onde aparecerá todas as anotações criadas pelo usuário</li>
 <li>Crie um footer</li>
 <li>Adicione links da comunidade Black Code no footer (Discord e Instagram)</li>
 <li>Adicione o nome da plataforma no footer</li>
 <li>Adicione links da equipe (linkedin/github dos dev's) no footer</li>
 
 </ol>
 
  ### Tela perfil
  <ol>
 
 <li>Desenvolva uma tela de perfil</li>
 <li>Mostre as informações do usuário</li>
 <li>Crie inputs para alterar as informações</li>
 <li>Crie inputs para adicionar novas informações</li>
 
 </ol>
 
 ### Persinalização! (OPCIONAL)
 <ol>
 
 <li>Possibilite o usuário personalizar a aplicação (com emojis, imagens de capa, etc..)
 
 </ol>
 
 # Protótipo do Projeto
 
 https://www.figma.com/file/pZs3nbkdpRlUj4x9FEX2Vt/Untitled?node-id=0%3A1
