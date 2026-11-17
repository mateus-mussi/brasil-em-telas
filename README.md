# Brasil em Telas 🎨

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Projeto acadêmico](https://img.shields.io/badge/Projeto-acad%C3%AAmico-blue)

## 📌 Visão geral

**Brasil em Telas** é um projeto acadêmico em equipe para apresentar a pintura e a diversidade cultural brasileira em um site de navegação simples. O conteúdo aborda paisagens, tradições e identidades regionais por meio de seções temáticas.

**Autores citados no material original:** Clarice Gabriela e Mateus Mussi. A identificação completa dos participantes e as permissões de publicação/licenciamento precisam ser confirmadas com o grupo.

## ✨ Funcionalidades

- Navegação por seções da mesma página.
- Introdução à pintura e às manifestações culturais brasileiras.
- Galeria com seis espaços reservados a imagens de obras.
- Textos sobre diversidade regional.
- Mapa incorporado do Google Maps (requer acesso à internet).
- Formulário **demonstrativo** de contato, sem envio de mensagens a servidor.

> **Estado atual:** esta é uma versão de demonstração. Os arquivos originais de imagens (`img/logo.webp`, `img/hero.jpg`, `img/1.jpg` a `img/6.jpg`) não estavam disponíveis; foram substituídos por placeholders identificados. Esses blocos **não são reproduções das obras originais**.

## 🧰 Tecnologias

| Tecnologia | Utilização |
|---|---|
| HTML5 | Estrutura do conteúdo, navegação e formulário |
| CSS3 | Layout, estilos e adaptação de tela |
| Google Maps Embed | Mapa externo via `iframe` |

Não há dependências Node.js, Python ou banco de dados.

## ▶️ Como executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/mateus-mussi/brasil-em-telas.git
   cd brasil-em-telas
   ```
2. Abra o arquivo `index.html` em um navegador moderno.
3. Se preferir, abra a pasta no VS Code e use a extensão **Live Server** para executar localmente.

O mapa depende da conexão com a internet. O formulário não envia mensagens; ao pressionar **Enviar**, mostra um aviso de demonstração.

## 🖼️ Demonstração visual

As capturas da versão demonstrativa foram preparadas separadamente, mas **ainda precisam ser enviadas à pasta `docs/` deste repositório**. Consulte [as instruções de conclusão](docs/LEIA-ANTES-DE-PUBLICAR.md).

Quando adicionadas, aparecerão aqui:

```markdown
![Página inicial](docs/inicio.png)
![Galeria](docs/galeria.png)
```

## 🗂️ Estrutura

```text
brasil-em-telas/
├── index.html
├── css/
│   └── style.css
├── docs/
│   └── LEIA-ANTES-DE-PUBLICAR.md
├── README.md
└── .gitignore
```

## 🔧 Melhorias planejadas

- Adicionar imagens originais licenciadas ou autorizadas, com créditos e texto alternativo.
- Substituir as capturas demonstrativas por screenshots da versão final.
- Melhorar a acessibilidade e a adaptação a telas pequenas.
- Implementar envio de contato apenas se houver serviço backend e política de privacidade adequados.

## 📚 Contexto acadêmico e licença

Antes de apresentar como projeto obrigatório do semestre **2026.2**, é necessário confirmar a disciplina e que o trabalho pertence a esse semestre. O arquivo `LICENSE` não foi incluído enquanto não houver autorização dos autores e titulares dos recursos utilizados.
