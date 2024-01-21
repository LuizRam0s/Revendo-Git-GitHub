# Git e Git Hub :school_satchel:

Este repositório, esta sendo usado para atualizar e rever tanto teoria como a pratica do Git e GitHub.

Esta sendo utilizado o conteúdos do curso do professor *Nélio Alves*  do curso completo: **Java COMPLETO Programação Orientada a Objetos + projetos.**



## Configurando sua identificação no GIT ::desktop_computer:

Adicionando nome.

**git config --global user.name "Seu nome"**

Adicionando email

**git config --global user.email "Seu email de cadastro do Github"**

Vendo lista de configurações.

**git config --list**



### Configurando chave ssh

Segue vídeo no you tube para melhor aprendizado

https://www.youtube.com/watch?v=cfgc51svrkg



## Salvando primeira versão :one:

**git init**

**git add .**

**git commit -m "Mensagem explicativa"**

**git branch -M main**

**git remote add origin git@github.com:seuusuario/seurepositorio.git**

**git push -u origin main**



### Salvando uma nova versão

**git add .**

**git commit -m "Mensagem explicativa"**

**git push origin**



## Clonando ou modificando um projeto

**git clone  git@github.com:seuusuario/seurepositorio.git**

**git add .**

**git commit -m "Mensagem"**

**git push**



## Um pouco sobre STATUS e STAGE

**Modified:** quando um arquivo sofre alguma modificação.

**Untracked:** quando adicionado um arquivo novo.

**Deleted:** quando um arquivo é deletado

**Stage:** área onde os arquivos estão prontos para ser comitado



### Git DIFF :

Comando utilizado para poder ver as diferenças feitas num arquivo modificado (Linhas adicionadas ou textos modificados por exemplo).



## Git checkout

Utilizado para modificar temporariamente os arquivos de um projeto para uma versão anterior (Commit ou branch)

**git log :** para poder ver o código das versão comitadas.
