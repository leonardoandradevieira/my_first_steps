 # my_first_steps
 1. Após criado a sua conta no GitHub, crie um repositório remoto público chamado “my_first_steps” e cole o link aqui;
https://github.com/leonardoandradevieira/my_first_steps

2. Crie um diretório em sua máquina e o vincule ao seu repositório remoto “my_first_steps” utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

No git Bash:
Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD
$ mkdir my_first_steps

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD
$ cd my_first_steps

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (master)
$ git remote add origin https://github.com/leonardoandradevieira/my_first_steps


3. Dentro do diretório em sua máquina, crie um arquivo chamado “ola_mundo.txt”, adicione algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git add .

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git commit -m 'aaa'
On branch main
nothing to commit, working tree clean

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git push --set-upstream origin main
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 599 bytes | 119.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/leonardoandradevieira/my_first_steps
   dca2a3b..7e3ee2f  main -> main
branch 'main' set up to track 'origin/main'.


4. Se não existir em seu diretório, adicione ao seu diretório um arquivo com o nome de “.gitignore”. Em seguida, crie um arquivo chamado “serei_ignorado.txt” e adicione algum texto dentro dele. Adicione a instrução ao arquivo “.gitignore” para que as alterações realizadas no arquivo “serei_ignorado.txt” não seja controlado pelo git. Cole aqui o conteúdo que você utilizou no “.gitignore” para realizar esta tarefa.

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ vi .gitignore

//Foi inserido o nome do arquivo a ser ignorado: serei_ignorado.txt

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)


5. Dentro do seu diretório local, crie um arquivo chamado “README.md” e edite-o contendo todas as respostas aos enunciados das questões anteriores. Adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa. 

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

no changes added to commit (use "git add" and/or "git commit -a")

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git add .
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git commit -m "chore: modificações"
[main 86350fe] chore: modificações
 2 files changed, 61 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 rewrite README.md (100%)

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1.45 KiB | 743.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/leonardoandradevieira/my_first_steps
   7e3ee2f..86350fe  main -> main

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git add .

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git commit -m "chore: de novo o readme"
[main ed65a65] chore: de novo o readme
 1 file changed, 2 insertions(+), 2 deletions(-)

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 387 bytes | 387.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/leonardoandradevieira/my_first_steps
   86350fe..ed65a65  main -> main
Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

no changes added to commit (use "git add" and/or "git commit -a")

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git add .
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git commit -m "chore: modificações"
[main 86350fe] chore: modificações
 2 files changed, 61 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 rewrite README.md (100%)

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1.45 KiB | 743.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/leonardoandradevieira/my_first_steps
   7e3ee2f..86350fe  main -> main

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git add .

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git commit -m "chore: de novo o readme"
[main ed65a65] chore: de novo o readme
 1 file changed, 2 insertions(+), 2 deletions(-)

Administrador@LAPTOP-5LHLGVG6 MINGW64 ~/Documents/Leo/Aulas/Alpha EdTech/Exercícios/HARD/my_first_steps (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 387 bytes | 387.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/leonardoandradevieira/my_first_steps
   86350fe..ed65a65  main -> main
