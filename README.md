# UC7
Atividade de versionamento de projetos - SENAI UC7  

**git init** –> iniciar repositório local  
**git status** –> verificar o status do repositório local  
**git add .** –> adicionar arquivos a área de staging para commit  
**git commit -m “mensagem de commit”** –> fazer o commit do projeto em seu estado atual  
**git remote add origin https://github.com/yuritries/UC7.git** -> estabelecer um link entre meu repositório local e o repositório remoto criado  
**git push -u origin main** –> atualizar o trunk (branch principal – main) do repositório remoto com a versão atual em minha branch principal do repositório local  
**git pull** -> para baixar as atualizações do repositório remoto  
**git checkout -b tarefa1** –> criação de uma branch para simular a alteração no arquivo de texto  
**git checkout “nome da branch”** – comando para visualizar determinada branch  
**git branch -d tarefa1** –> comando para deletar a branch chamada tarefa1 após a tarefa ter sido concluída e seu código mergido para a branch main (branch principal)  
**git merge tarefa1** –> comando executado no trunk mergindo as alterações feitas na branch tarefa1   
**git tag -a v1.0 -m “release 1.0”** –> demarcando um ponto crucial no desenvolvimento do projeto. Primeira entrega parcial do projeto  
**git push --tags** –> publicando a tag no repositório remoto  
