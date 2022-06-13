# Estudo Gii e GitHub

### Comandos GIT
- cd = Entra em pastas
- cd .. = Volta uma pasta
- Dir = Exibe o conteúdo de uma pasta
- mkdir = Cria uma pasta
- echo = Cria um arquivo
- del = Apaga um arquivo
- rmdir = Deleta uma pasta
- cls = Limpa tudo no CMD no git (CTRL + L)
- git status = Contultar o status do diretório

#### cd 
Para entrar em uma pasta <br>
ex: **cd pasta**

#### cd ..
Para voltar uma pasta <br>
ex: **cd ..**

#### dir
Para verificar os arquivos e pastas de um diretório <br>
ex: **dir**

#### mkdir
para criar uma pasta <br>
ex: **mkdir nome_da_pasta**

#### echo
Para criar um arquivo de qualquer extensão <br>
ex: **echo novo_arquivo > novo_arquivo.txt**

#### del
Para deletar um arquivo <br>
ex: **del aquivo.txt**

#### rmdir
Para apagar todo diretório <br>
ex: **rmdir nome_da_pasta /S /Q**

#Git Bash
Sha1

### Sincronizar, procedimento de configuração <br>
Comando: **ssh-keygen -t ed25519 -C "email@email.com"** <br>
vai pedir e-mail & Senha

**ls** <br>
Ler o arquivo

***cat id_25519.pub** <br>
para ler a chave

**eval $(ssh-agent -s)** <br>
**ls**<br>
**ssh-add id_ed25519.pub**

**git config --global user.email email@email.com** <br>
**git config --global user.name nome** <br>
Ver se as configurações estão iguais
**git config --list


### Clonar 

**git clone link(colar)**<br>
para clonar (baixar) um projeto

### Subir repositório
no GitHub<br>
**menu repositório**  
**mew**
**nome, descrição e gerar**  

no GIT<br>
**git remote add origin  link_do_repositório**<br>
**git remote -v**<br>
**git push origin master**


### Iniciar o processo GIT
**git init**
**git add ou add.**
**git commit -m "texto a ser marcado"**



