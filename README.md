# Website do DevMT
Este repositório contém os fontes para a geração do site do DevMT. Foi desenvolvido utilizando o gerador de sites estáticos [Hugo](https://gohugo.io). 

## Pré requisitos
- Hugo - [download](https://gohugo.io)

## Como rodar 
- Para desenvolver localmente rode o comando com livereload:
```shell
hugo server --watch
```
- Para dar deploy (tendo as devidas permissões no repo de destino):
```shell
./deploy.sh "Mensagem de deploy"
```

## Quero apenas adicionar conteúdo, como faz ?
- Basicamente nós temos 3 tipos de conteudo no site, eventos, meetups e artigos que ficam em suas respectivas pastas em `content`. Cada um possui alguns metadados mas o conteúdo de cada deve ser escrito em [Markdown](https://daringfireball.net/projects/markdown/).
- Para colaborar dê fork no projeto, escreva um conteudo novo, ou faça alguma alteração e mande pull-request que vamos avaliar e publicar no nosso site.

## Créditos
- Gerador de sites estaticos [Hugo](https://gohugo.io). 
- Tema HugoMDL - [jchatkinson/HugoMDL](https://github.com/jchatkinson/HugoMDL).


