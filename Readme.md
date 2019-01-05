um app q por enquanto n faz nada

funçoes do git:

git status -> para ver quais arquivos foram adicionados ou modificados

git add -A -> para adicionar os arquivos ao monitoramento git

git log    -> para ver todos os commits (ate onde eu entendi sao comentarios sobre as mudanças)

git commit -m "mensagem qualquer" -> (ate onde eu entendi sao comentarios sobre as mudanças)

git branch -> lista todos os branchs (os q tiverem * é o q esta naquele momento)

git branch qualquercoisa -> cria um novo branch com o nome qualquercoisa (ele sera uma copia do anterior)

git checkout qualquercoisa -> ele entrara no branch com o nome qualquercoisa

git commit -am -> "qualquer msg" adiciona a lista ja com um commit ()

git reset --hard id do commit para o qual voce deseja voltar -> apaga tudo e volta para as informaçoes para o commit escolhido(desespero quando alguma merda ocorreu)

git reset --soft id do commit para o qual voce deseja voltar ->  volta porem apenas sem o commit deixando as informaçoes la(o mais comum)

git reset --mixed id do commit para o qual voce deseja voltar -> muito parecido com o soft porem ele nao volta sem adicionar os documentos(git add -A)

git diff -> mostra todas as mudanças ocorridas nos arquivos

git diff --name-only -> mostra apenas o nome dos arquivos modificados

git diff nomedoarquivo -> ver apenas as mudanças no arquivo mencionado
