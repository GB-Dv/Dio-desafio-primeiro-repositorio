### **Comandos básicos Git (versão windows)**

* dir/ls  - lista arquivos de um diretório
* dir/ls -a - lista todas os arquivos incluindo os ocultos
* cd - acessa um diretório
* cd .. - retorna de um diretório
* mk dir - cria um diretório
* rm dir - remove um diretório
* echo > - cria arquivos



### **Criando um repositório no Git e o conectando com o GitHub**

1. git init - inicia repositório;

2. git add * - move arquivos do diretório para o estado de "staging", tornando-os assim disponiveis para o commit;

3. git commit -m " " - permite que você crie um commit, ou seja guarda uma "fotografia" do seu repositório naquele momento para que possa ser; 

4. git remote add - irá fazer a conexão entre o repositório local e global;

5. git push - irá "empurrar" os arquivos do repositório local para o repositório global.



### **Outros comandos relevantes**

* git clone + url - irá criar um clone do repositório global selecionado, para repositório local
* git pull - irá "puxar" os arquivos do repositório global para o local, podendo assim identificar possíveis conflitos entre versões dos arquivos
* git mv - possibilita renomear arquivos, ou move-lós entre os diretórios
* git status - verifica status dos arquivos do repositorio (untracked,modified, unmodified e staged)
* git config - possibilita realizar configurações básicas e essenciais no git para comits dos arquivos como cadastro de e-mail e nome de usuário





