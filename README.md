# consulta_clima

Cliente para API do Clima Tempo em Python.

## Funcionalidades
- permite pesquisar o ID da cidade pelo nome
- permite adicionar uma cidade ao token do usuário
- permite consultar o clima da cidade
- permite listar todas as cidades registradas no token do usuário

## Usando
1. Realizar o cadastro no site do [Clima Tempo](https://advisor.climatempo.com.br)

2. Clonar este repositório:

	`git clone "https://github.com/dnc0/consulta_clima" && cd consulta_clima`
3. Configurar o Token to usuário

	Existem 3 formas de configurar o token:

	- Diretamente no arquivo python

		Editar o arquivo `consulta_clima` e preencher o conteúdo da variável `TOKEN`.

	-  Usando de arquivo de configuração

		Criar/editar arquivo `/home/Usuario/.clima_tempo` com o conteúdo:
	`token = aaaaaaaaaaaaaaaaaaaa`

		Subsituir "aaaaaaaaaaaaaaaaaaaa" com o token do usuário.

	- Usando variáveis de ambiente

		Definir a variável de ambiente `CLIMA_TEMPO_TOKEN` com o valor do token do usuário.
		Exemplo:
		`export CLIMA_TEMPO_TOKEN="aaaaaaaaaaaaaaaaa"`

4. Pesquisar o ID da cidade

	`./consulta_clima --pesquisar-cidade "Nome da cidade"`

	Exemplo:
	`./consulta_clima --pesquisar-cidade "Porto Alegre"`

5. Adicionar cidade no token

	`./consulta_clima --adicionar-cidade ID-CIDADE`

	Exemplo:
	`./consulta_clima --adicionar-cidade 5346`
6. Realizar a consulta

	`./consulta_clima --clima ID-CIDADE`

	Exemplo:
	`./consulta_clima --clima 5346`

## Sobre
Desenvolvido por Marlon Soares (marlonslbr@gmail.com) 
Github: [dnc0](https://github.com/dnc0)
