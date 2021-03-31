# consulta_clima

Cliente para API do Clima Tempo em Python

## Funcionalidades
- permite pesquisar o ID da cidade pelo nome
- permite adicionar uma cidade ao token do usuário
- permite consultar o clima da cidade
- permite listar todas as cidades registradas no token do usuário

## Usando
1. Realizar o cadastro no site do [Clima Tempo](https://advisor.climatempo.com.br)
2. Clonar este repositório:
`git clone "https://github.com/dnc0/consulta_clima" && cd consulta_clima`
3. Pesquisar o ID da cidade
`./consulta_clima --pesquisar-cidade "Nome da cidade"`
Exemplo:
`./consulta_clima --pesquisar-cidade "Porto Alegre"`
4. Adicionar cidade no token
`./consulta_clima --adicionar-cidade ID-CIDADE`
Exemplo:
`./consulta_clima --adicionar-cidade 5346`
5. Realizar a consulta
`./consulta_clima --clima ID-CIDADE`
Exemplo:
`./consulta_clima --clima 5346`

## Sobre
Desenvolvido por Marlon Soares (marlonslbr@gmail.com) 
Github: [dnc0](https://github.com/dnc0)
