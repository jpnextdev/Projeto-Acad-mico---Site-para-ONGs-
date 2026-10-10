# Instituto Raízes do Bairro

Plataforma web de uma ONG fictícia de hortas comunitárias, desenvolvida totalmente para um projeto academico.

## Páginas

- `index.html`: apresentação da organização (missão, visão, valores, história, equipe, transparência) e contato.
- `projetos.html`: projetos sociais, voluntariado e formas de doação.
- `cadastro.html`: formulário de cadastro com validação nativa HTML5 e máscaras de CPF, telefone e CEP.

## Estrutura de pastas


ong-raizes/
├── index.html
├── projetos.html
├── cadastro.html
├── css/
│   └── style.css
├── js/
│   └── mascaras.js
└── imagens/
    ├── logo.svg
    └── *.jpg / *.webp (duas resoluções cada)
```

## Recursos aplicados

- HTML5 semântico: `header`, `nav`, `main`, `section`, `article`, `figure`, `address`, `footer`, hierarquia de títulos h1 → h2 → h3.
- Formulário com `fieldset`/`legend`, tipos `email`, `tel`, `date`, `select`, `radio`, `checkbox` e atributos `required`, `pattern`, `minlength`, `maxlength`, `min`, `max`.
- Imagens otimizadas em WebP e JPG com `<picture>`, `srcset` e `loading="lazy"`.
- Layout responsivo mobile-first com breakpoints em 48em (tablet) e 64em (desktop).
- Acessibilidade: link "pular para o conteúdo", foco visível, textos alternativos, `aria-current` no menu.

## Validação

Os três arquivos HTML foram validados sem erros no W3C Nu HTML Checker (https://validator.w3.org/nu/).
