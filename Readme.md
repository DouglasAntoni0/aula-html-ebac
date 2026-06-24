# Projeto HTML e CSS - EBAC

![HTML5](https://img.shields.io/badge/HTML5-semantica-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-seletores%20e%20estilo-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-publicacao-222222?style=for-the-badge&logo=githubpages&logoColor=white)
![QA](https://img.shields.io/badge/QA-DOM%20e%20seletores-0A66C2?style=for-the-badge)

Projeto de demonstração com HTML e CSS, criado para praticar estruturação de página, aplicação de estilos e publicação simples via GitHub Pages.

Embora seja um projeto de front-end básico, ele tem valor direto para QA Automation: entender HTML, CSS, DOM e seletores é essencial para criar testes web mais estáveis. Uma automação de interface depende da capacidade de ler a estrutura da página, identificar elementos confiáveis e interpretar comportamento visual.

## Objetivo do projeto

O objetivo é demonstrar conceitos fundamentais de uma página web estática:

- estrutura HTML;
- separação entre conteúdo e estilo;
- aplicação de seletores CSS;
- organização mínima de arquivos;
- execução local no navegador;
- possibilidade de publicação com GitHub Pages.

Essa base ajuda a conectar desenvolvimento web e automação de testes. Quando um QA entende como uma página é construída, consegue escolher melhores seletores, reportar problemas com mais precisão e dialogar melhor com o time de desenvolvimento.

## O que este projeto demonstra

| Frente | Valor técnico | Relação com QA |
| --- | --- | --- |
| HTML | Organização de conteúdo em uma página estática | Ajuda na leitura de DOM e hierarquia de elementos |
| CSS | Uso de seletores e estilização separada do markup | Facilita entendimento de estados visuais e layout |
| Publicação | Base pronta para hospedagem via GitHub Pages | Permite disponibilizar artefatos simples para validação |
| Boas práticas | Separação entre estrutura, estilo e documentação | Melhora manutenção e clareza |
| Inspeção web | Página pode ser analisada pelo DevTools | Aproxima do trabalho diário de automação UI |

## Estrutura

```text
.
├── Readme.md    # Documentação do projeto
├── index.html   # Estrutura da página
└── style.css    # Estilos aplicados à página
```

A separação entre `index.html` e `style.css` é uma prática simples, mas importante. Ela evita misturar conteúdo, apresentação e documentação no mesmo lugar.

## Como executar localmente

Clone o repositório:

```bash
git clone https://github.com/DouglasAntoni0/aula-html-ebac.git
cd aula-html-ebac
```

Abra o arquivo `index.html` no navegador.

Também é possível usar extensões como Live Server no VS Code para recarregamento automático durante alterações.

## Como inspecionar a página

Para usar o projeto como prática de leitura de DOM:

1. Abra `index.html` no navegador.
2. Pressione `F12` ou abra o DevTools.
3. Inspecione os elementos da página.
4. Observe tags, classes, estilos aplicados e hierarquia.
5. Relacione os seletores CSS com os elementos exibidos.

Esse exercício é útil para automação porque muitos testes web falham por seletores frágeis. Entender a estrutura da página ajuda a escolher estratégias melhores.

## Como publicar no GitHub Pages

1. Acesse `Settings` no repositório.
2. Entre em `Pages`.
3. Em `Source`, selecione `Deploy from a branch`.
4. Escolha a branch `main` e a pasta `/ (root)`.
5. Salve e aguarde a geração do link.

Após a publicação, a página poderá ser acessada em um endereço do tipo:

```text
https://seu-usuario.github.io/nome-do-repositorio/
```

## Resultado técnico

Este repositório registra domínio dos fundamentos de front-end que apoiam a atuação em QA: entender estrutura de DOM, seletores CSS e organização de página facilita a leitura de aplicações web e a criação de automações mais estáveis.

## Competências evidenciadas

- HTML básico.
- CSS básico.
- Organização de projeto web estático.
- Noção de publicação via GitHub Pages.
- Leitura de DOM e seletores.
- Documentação de execução local.

## Possíveis evoluções

- Adicionar HTML semântico mais completo.
- Criar classes e IDs pensados para testabilidade.
- Incluir uma checklist de validação visual.
- Publicar com GitHub Pages.
- Criar testes simples com Cypress ou Playwright para validar elementos da página.

## Conclusão

Este projeto é simples, mas conversa diretamente com qualidade de software. Um QA que entende HTML e CSS não depende apenas de tentativa e erro para automatizar: ele lê a página, entende a estrutura e constrói testes mais confiáveis.
