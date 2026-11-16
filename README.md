# Automação Residencial com IoT

Infográfico de pesquisa exploratória (Desenvolvimento de Sistemas – Etec) sobre automação residencial com Internet das Coisas.

Artigo estudado: *Controle Residencial de Dispositivos Infravermelho e de Iluminação Utilizando um Módulo Central de Baixo Custo*, de Jorge Luiz P. Oliveira e Thais Reggina Kempner (UFMT), ERI-MT 2023 / SBC.
DOI: [10.5753/eri-mt.2023.236366](https://doi.org/10.5753/eri-mt.2023.236366)

## Tecnologias

- HTML5 semântico
- [Bootstrap 5.3](https://getbootstrap.com/) e [Bootstrap Icons](https://icons.getbootstrap.com/) via CDN
- CSS próprio em `assets/css/style.css`

## Estrutura

```
index.html                 página principal
assets/css/style.css       cores e estilos
assets/img/favicon.svg     ícone da aba
assets/downloads/          infográfico em PNG e PDF
.nojekyll                  publica os arquivos sem processamento do Jekyll
```

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub e envie estes arquivos (o `index.html` precisa ficar na raiz).
2. No repositório, abra **Settings › Pages**.
3. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
4. Em alguns minutos o site fica disponível em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.
