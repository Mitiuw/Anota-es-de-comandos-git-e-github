Clonando Repositórios
 

Comandos básicos

Limpar terminal : ctrl+l
Ler todo conteúdo do diretório: ls



Open Gitbash

Criar pasta comando: mkdir repo-localmkdi
Entrar na pasta pelo terminal: cd repo-local/
Voltar pasta anterior: cd ..
Criar repositório local: git init
Mostrar que é um diretório git: cd .git
Exibir cointeudo: cat config
Clonar repositório do GitHub: git clone
Clonar repositório do GitHub com novo nome: git clone (url do conteudo) repo-clonado 
Verificar se a pasta ta vinculada: git remote -v
Contecar rep local ao remoto: git remote add origin (url)
Mostrar status commit e o estado dos arquivos: git status
Criar arquivo leia-me: touch READMD.md
Criar um commit: git commit -m"commit inicial"
Criar um arquivo .gitgnore: echo (nomedoarq)/ > .gitignore
remover diretório git e todo conteudo: rm -rf .git
restaurar conteudo de arquivo excluído. Ex README.md: git restore README.md
corrigir mensagens do ultimo commit criado: git commit --amend -m"(conteudo)"
editar mensagen do ultimo commit: git commit --amend(vai abrir o editor)
desfazer e alterar qualquer commit anterior utilizando a hash: git reset (opciones --soft --mixed --hard)
pra resetar o ultimo commit com hash: git restet --mixed
para remover arquivo: git reset (nome do arquivo)
histórico detalhado: git reflog