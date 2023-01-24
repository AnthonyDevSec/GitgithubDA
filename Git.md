git branch -M main (serve para mudar o nome principal de master para main, super util)
git init (para iniciar o processo de guardar o código localmente com git para futuramente envia-lo
para o github)
git add "nome do que vai por na fila para enviar ao git local" 
git add . (Adiciona tudo que foi modificado para ser colocado no git local)
git commit -m "qualquer coisa" (para salvar localmente a sua versão do código(O nome colocado entre aspas vai como descrição para o github quando enviado))
git status (vê o status de o que está em espera para ser adicionado, o que já pode ser comitado e
enviado)
git remote add origin "link do repositório no github"
git push origin main (enviar para o github as atualizações que você fez)
git reflog (O historico de de mudanças no código)
git reset --hard 0000 (No espaço dos zeros você coloca o código a esquerda que identifica as suas mudanças no código para voltar a uma versão anterior.)
