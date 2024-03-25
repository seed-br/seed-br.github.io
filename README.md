# Site do Grupo SEED.BR

- DOI: [10.5281/zenodo.8314250](https://doi.org/10.5281/zenodo.8314250)
- Site: https://seed-br.github.io

## Rodar site local usando docker

Instale Docker, Docker Compose e execute o comando abaixo.

```sh
docker-compose up
```

Então acesse o site em:
- http://127.0.0.1:4000 ou http://localhost:4000

## Atualização do site

O site SEED.BR está hospedado no [GitHub Pages](https://pages.github.com) e é
atualizado automaticamente a cada novo commit no repositório abaixo:

- https://github.com/seed-br/seed-br.github.io

## Organização do código-fonte do site

O site do SEED.BR é feito com o gerador de site estático
[Jekyll](https://jekyllrb.com) versão 4.2.0 e o código-fonte está organizado
segundo a estrutura abaixo.

| Arquivo ou Pasta     | Descricao  |
| -------------------- | ---------- |
| `_config.yml`        | Arquivo de configuração do Jekyll |
| `css/`               | Pasta com arquivos de estilo CSS |
| `docker-compose.yml` | Arquivo docker compose para rodar site localmente para desenvolvimento |
| `files/`             | Arquivos de imagens, videos, outros |
| `_includes/`         | Arquivos de templade HTML do Jekyll para Header, Footer, Menu e outros |
| `index.html`         | Arquivo HTML Jekyll da página inicial do site |
| `javascript/`        | Pasta com arquivos de Javascript |
| `_layouts/`          | Pasta com layouts HTML do Jekyll para páginas, blog posts, slides |
| `_pages/`            | Pasta com arquivos Markdown com conteúdos do site |
| `_posts/`            | Pasta com arquivos Markdown com conteúdos de Blog ou Notícias |
| `_site/`             | Pasta com todo o site gerado pelo Jekyll conteudo resultado de build (é o que está publicado em produção) |
| `_slides`/           | Pasta com slides HTML escritos em Reveal.js |
| `start.sh`           | Shell script para rodar o site localmente |

## Como atualizar e contribuir com o site

Para contribuir com o site é necessário fazer um clone do repositório git do
site, fazer as modificações desejadas, commit e enviar um Pull Request para o
repositório no GitHub.

É possível também enviar commits diretamente via git push sem Pull Request caso
você tenha permissão e não precise de revisão de alguém do grupo antes de
aplicar as mudanças em produção.
