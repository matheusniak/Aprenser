# Aprenser

Homepage single-page de uma instituição de ensino fictícia, construída com HTML e CSS. Navegação por âncoras (Cursos, Nossa Escola, Contatos), hero com CTA e mapa integrado via iframe. Projeto didático para praticar HTML semântico, layout e boas práticas de acessibilidade.

## Demo / Imagem

### Mockup

![Imagem mockup do projeto](<Aprenser conteúdo/assets/Desktop.png>)

### Implementação

![Imagem resultado da implementação](<Aprenser conteúdo/assets/screenshot-implementacao.png>)

**Obs.**: O mapa do Google integrado (iframe) não aparece na imagem de screenshot exibida acima, porém, ao abrir a página ao vivo/local via `index.html` o mapa é carregado normalmente.

---

## Características principais

- Single-page: navegação por âncoras internas (`#cursos`, `#escola`, `#contatos`).
- Hero com CTA ("Saiba mais") e imagem de destaque.
- Sessão de cursos com cartões (Design, Front End, Back End).
- Sessão "Nossa escola" com texto institucional e imagem.
- Sessão de contatos com mapa integrado via `<iframe>` e endereço de contato.
- Uso de `normalize.css` para consistência visual entre navegadores.
- Projeto voltado para prática: sem frameworks, apenas HTML/CSS puros.

## Tecnologias

- HTML5 (index.html)
- CSS3 (arquivo `css/estilo.css`)
- Normalize (`css/normalize.css`)
- Assets (PNG, FIG) para ilustrações e logo

## Estrutura do projeto

```
.
├─ Aprenser conteúdo/
│ ├─ assets/ # arquivos do Figma e exemplo final
│ ├─ imagens/ # imagens usadas no site
│ ├─ css/
│ │ ├─ normalize.css
│ │ └─ estilo.css
│ └─ texto-da-pagina.txt
├─ index.html
├─ README.md
└─ LICENSE
```

## Como abrir / visualizar

Para que o `index.html` abra corretamente e todas as imagens e estilos apareçam, **é necessário baixar/clonar o repositório inteiro**, mantendo a estrutura de pastas (`Aprenser conteúdo/`, `css/`, `assets/`, `imagens/`).
Caso abra apenas o `index.html` isoladamente, algumas imagens ou o CSS podem não funcionar.

Basta abrir o `index.html` no navegador (duplo clique) ou servir por um servidor HTTP simples para evitar restrições de CORS em alguns navegadores:

```bash
# Rodando um servidor local com Python 3
python -m http.server 8000

# Acesse no navegador:
http://localhost:8000

# Para parar o servidor, pressione Ctrl+C
```

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
