# 🎉 Primeiro Commit

### Guia rápido para conseguir fazer um Commit em um novo repositório.

# ⚠️ Atenção

***Este documento foi criado por mim mesmo para facilitar meus commits, porém, eu não tenho ainda muito entendimento dos comandos então pode ser que eu adicione algo errado.***

# 💻 Comandos

1. **git init** </br>
O comando git init cria um novo repositório do Git. Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio.

2. **git add .**</br>
O comando git add é responsável por adicionar as alterações feitas nos arquivos a uma área temporária.

3. **git commit -m "primeiro commit"**</br>
Ele leva as mudanças de um ambiente local para o repositório no git, permitindo ainda a inserção de uma mensagem descritiva.

4. **git branch -M main**</br>
O branch é a solução perfeita, pois cria uma ramificação do código principal para que seja possível fazer alterações sem nenhum tipo de problema. Neste caso aqui, estamos adicionando os arquivos listados no git add . à branch Main, a branch principal do projeto.

5. **git remote add origin (junto com o link do repositório)**</br>
O comando git remote permite criar, ver e excluir conexões com outros repositórios. Neste caso estamos se conectando com o nosso próprio repositório onde iremos adicionar os arquivos.

6. **git push -u origin main**</br>
Em geral, git push origin main é executado para efetuar push das alterações locais para o repositório online. Didáticamente falando, ele envia as alterações feitas no projeto para o repositório linkado no passo anterior.
