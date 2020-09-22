# **DON'T PANIC**

forka, Raquel ヾ(-_- )ゞ 

Output comentado do history do meu terminal:
```git clone https://github.com/lucascs20182/to-learn-git.git``` //copia o repositório criado no github

```git status``` //verifica a situação do versionamento

```git add index.html``` //adiciona o arquivo para uma espécie de área de preparação

```git add .``` //adiciona tudo para staging

```git status```

```git config --global user.email 'lucascs20182@gmail.com'``` //sem a flag --global a configuração fica apenas para o projeto

```git config --global user.name 'lucascs20182'```

```git commit -m "initial commit"``` //flag -m para passar a mensagem do commit direto no comando, sem abrir o arquivo num editor e depois ter que salvar etc.

```git status```

```git push origin master``` //empurra para o github as alterações da branch master

//----------------------------------------------------------------

```git status```

```git log``` //lista últimos commits realizados

```git branch``` //informa branches existentes no projeto

```git branch dev-schedule-component``` //cria branch chamada dev-schedule-component

```git branch```

```git checkout dev-schedule-component``` //muda para branch dev-schedule-component

```git status```

```git add .```

```git commit -m "commit schedule.js da branch dev-schedule-component"```

```git branch -v``` //mostra o último commit realizado

```git push origin dev-schedule-component``` //empurra para o github as alterações da branch dev-schedule-component

//----------------------------------------------------------------

```git branch```

```git checkout master```

```git merge dev-schedule-component``` //unifica alterações das 2 branches

```git branch -d dev-schedule-component``` //deleta dev-schedule-component

```git branch```

```git push```
