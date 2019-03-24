# Python Sudeste - 2019 - Site

Esse repositório contém o website para a Python Sudeste de 2019. Estamos usando um template chamado [hugo-conference](https://github.com/jweslley/hugo-conference/).

## Preparando ambiente

Estamos utilizando um gerador de sites estáticos, o [Hugo](https://gohugo.io/). A forma mais fácil é apenas baixar o binário mais recente compatível com o seu sistema operacional [aqui](https://github.com/gohugoio/hugo/releases) e colocá-lo em algum lugar que esteja no seu `PATH` para facilitar o uso. (`/usr/local/bin`, por exemplo).

As instruções de instalação se encontram [aqui](https://gohugo.io/getting-started/installing) se quiser entrar em mais detalhes ou fazer um build do código-fonte.

## Como rodar localmente

Por padrão, o server do Hugo roda na porta 1313. Configuramos uma `baseurl` no arquivo `config.yml`, portanto para rodar tranquilamente locamente, precisamos fazer um override dessa baseurl através de uma flag de linha de comando. O comando fica assim:

`hugo serve -b http://localhost:1313`