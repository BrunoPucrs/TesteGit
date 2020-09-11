_______________________________________
Console
_______________________________________
Iniciar o repositório
        git init

Para testar
        git status

Adicionando e Comitando
	git add nomeArquivo  <--Para adicionar arquivo
	git add . <--Para adicionar Pasta/ Onde "." Significa a pasta atual

	git commit -m "Comentário"

Conectando Repositório local com o da web
	git remote add "apelidoRepo" https://github.com/BrunoPucrs/TesteGit.git

Testar conexão 
	git remote -v 
	
	Retorno deve ser semelhante a esse:
		ApelidoRepo	https://github.com/BrunoPucrs/TesteGit.git (fetch)
		ApelidoRepo	https://github.com/BrunoPucrs/TesteGit.git (push)

Sincronizando os repositórios
	git push ApelidoRepo master 
**Em caso de o Git ter sido recem instalado, será solicitado as configurações globais como e-mail e nome de usuário**

git config --global user.name "BrunoTeste"
git config --global user.email "teste.email@teste.com.br"

Remover Arquivo adicionado
	git rm --cached "nomeArquivo" <-- --cached significa que remove apenas a adicão ao git, mantendo o arquivo, para remover o arquivo de repositório, utiliza o -f
	

GitHub
_______________________________________
Criando Repositório
	Clicar no + 	
	Copiar a URL https://github.com/BrunoPucrs/TesteGit.git

Teste
