### Aula GIT ###

###
Instalação 

sudo apt install git

## SCENES

[] - Voce deseja criar pontos na historia da produção do seu projeto

[] - Você deseja verificar mudanças feitas no seu projeto

	git init [Inicia um repositorio local]
	git add (nome do arquivo) - [add um arquivo ao repositorio do git]
	git commit -m "informar um comentario" [cria um comentario informando um ponto na historia do projeto]
	git log - [mostra os pontos na historia do projeto]
	git status - [mostra os status do desenvolvimento do projeto no git]
	git show + (n do commit) - []


[] - Você começa uma nova funcionalidade no seu projeto, sem estragar o que ja foi feito

[] - Você add as novas funcionalidades no seu projeto em produção

[] - Você quer deletar a branch da nova funcinalidade, depois de aplicar e seu projeto

	git branch feature/cart - [Cria uma nova funcinalidade no projeto sem estragar a anterior]

	git checkout feature/cart - [Mostra o caminho alternativo criado]

	git merge feature/cart - [Juntar a linha alternativa com a linha principal]

	git -D feature/cart - [Deleta a branch]


[] - Você quer add seu projeto na nuvem 

