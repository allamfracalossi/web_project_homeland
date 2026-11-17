# De Pátria para Pátria — web_project_homeland

Página responsiva da Galeria de Arte TripleTen, desenvolvida para a primeira parte do projeto do Sprint 5. Apresenta a exposição, uma fotografia de uma cidade costeira e a introdução às histórias da comunidade.

## Tecnologias e organização

- HTML5 semântico, com idioma português, metadados, hierarquia de títulos e descrições das imagens.
- CSS3 com Flexbox, larguras fluidas, limites de largura e consultas de mídia em 1024px e 544px.
- Metodologia BEM Flat: um arquivo CSS por bloco em `blocks/`, importado por `pages/index.css`.
- Inter local, nos pesos Regular (400) e Black (900), com alternativas Arial e sans-serif.
- Normalize.css 8.0.1, logotipo vetorial extraído do Figma e fotografia JPEG otimizada.
- Sem JavaScript, frameworks, dependências de instalação ou etapa de build.

## Executar

Abra `index.html` no navegador. Todos os recursos são locais. Se preferir usar um servidor, execute na pasta do projeto:

```bash
python -m http.server 8000
```

Acesse `http://localhost:8000`.

## Publicar no GitHub Pages

**Status:** publicação pendente. O endereço real ainda não está disponível, pois a conta e o repositório do GitHub não foram fornecidos. Após a publicação, substitua este parágrafo pelo link real do site.

1. Clone seu repositório `web_project_homeland` usando a URL fornecida pelo GitHub.
2. Copie o conteúdo desta pasta para a raiz do repositório clonado, incluindo os arquivos iniciados com ponto.
3. Substitua `Seu nome` no rodapé de `index.html` pelo seu nome.
4. Faça commit e envie os arquivos para a ramificação `main`.
5. Nas configurações do repositório, em **Pages**, escolha publicação a partir da ramificação `main` e da pasta raiz (`/root`).
6. Copie a URL exibida pelo GitHub Pages e adicione o link real a este README antes da entrega.

## Referência

[Design do Figma](https://www.figma.com/file/gmZhyMHUJICpwDqC73CD58/)

A implementação usa os textos, a imagem e as medidas extraídos do arquivo `Sprint 5 PT.fig` anexado. O escopo é a primeira parte: cabeçalho, apresentação, introdução e rodapé. O ano do rodapé foi atualizado para 2026; o nome deve ser personalizado.

## Verificação

A estrutura de pastas, as referências locais, a sintaxe CSS e a estrutura HTML foram verificadas automaticamente. Os tamanhos e espaçamentos foram implementados a partir dos quadros de 1280px, 768px e 320px.

A infraestrutura de prévia estava indisponível durante a criação. Portanto, a validação visual no Chrome e no Firefox e a validação oficial do W3C ainda devem ser realizadas antes da submissão. Confira também 470px, 544px, 545px, 665px, 999px, 1024px, 1025px, 1100px e 1500px, observando quebras de texto e rolagem horizontal.

O quadro de tablet contém uma pequena sobreposição entre as caixas da citação e da autoria. O código mantém o fluxo natural do texto e o espaçamento de 10px usado nas demais versões, evitando reproduzir essa sobreposição.

## Créditos

Design e conteúdo: TripleTen. Fotografia: Kalegin Michail (arquivo fornecido no Figma). Fonte Inter: Rasmus Andersson, distribuída sob a licença SIL Open Font License em `vendor/Inter-LICENSE.txt`. Normalize.css: Nicolas Gallagher e Jonathan Neal, licença MIT.
