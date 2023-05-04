# Site e Blog SoteroLab

Esse site foi construído a partir do tema [Affiliates - Jekyll Theme for Bloggers](https://bootstrapstarter.com/template-affiliates-bootstrap-jekyll/). 


## Executando localmente

Link para fazer a [instalação do Jekyll localmente](https://jekyllrb.com/docs/installation/).

Após fazer a instalação do Jekyll e o `git clone` do repositório, realizar os seguintes comandos:

`bundle`

`jekyll serve --watch`

## Adicionando nova postagem do Blog

Criar um novo arquivo markdown na pasta `_post` e configurar o seu início preenchendo os seguintes campos:

```
---
layout: post 
title:  "Título da Postagem"
categories: [ "Coloque ali a sua lista de categorias separadas por vírguça" ]
image: assets/images/imagem_do_meu_post.png (Indique aqui qual imagem irá ser o cabeçalho do seu post. Lembre-se de fazer o upload na respectiva pasta `assets/images`) 
author: nome_autor (Indique aqui a chave de identificação do autor, coforme dicionário descrito da seção `# Authors` do arquivo `_config.yml`) 
---
```

Após a configuração é so escrever a sua postagem seguinto das regras do markdown. Pode adicionar outras fotos, gŕaficos, vídeos, gifs, fórmulas, tabelas, links...! 
O que a sua narrativa permitir.
