# Portfólio Bootstrap — Bruna

Portfólio pessoal de uma página, desenvolvido durante a formação em Software Development no CESAE. Foi construído apenas com HTML e classes e componentes do **Bootstrap 5**, sem CSS personalizado.

## Secções

- **Início**: apresentação, foto, botões de ação e ligações para o GitHub e o LinkedIn.
- **Sobre mim**: percurso, formação, localização e competências com barras de progresso.
- **Projetos**: cartões com os trabalhos feitos durante a formação (1 coluna no telemóvel, 2 no tablet, 3 no computador).
- **Contacto**: ligações para as redes e formulário com validação nativa do HTML (campos obrigatórios e consentimento).
- **Rodapé** e botão fixo para voltar ao início.

## Funcionalidades

- Layout responsivo com a grelha do Bootstrap
- Menu de navegação fixo, que passa a menu hambúrguer em ecrãs pequenos
- Scrollspy: o menu destaca a secção visível
- Ícones do Bootstrap Icons
- Favicon personalizado

## Tecnologias

- HTML5
- [Bootstrap 5.3.3](https://getbootstrap.com/) (CSS e JavaScript via CDN)
- [Bootstrap Icons 1.11.3](https://icons.getbootstrap.com/)

## Estrutura

```
bootstrap-Bruna/
├── index.html          # página do portfólio
├── images/
│   ├── bruna2.jpeg     # foto de perfil
│   └── favicon2.png    # ícone do separador
└── README.md
```

## Como ver o projeto

Não é preciso instalar nada. Basta:

1. Clonar o repositório:
   ```bash
   git clone https://github.com/brunajacby/bootstrap-Bruna.git
   ```
2. Abrir o ficheiro `index.html` no browser.

É necessária ligação à internet para carregar o Bootstrap e os ícones a partir do CDN.

> O formulário de contacto valida os campos, mas ainda não envia mensagens: não está ligado a nenhum serviço.

## Contacto

- GitHub: [brunajacby](https://github.com/brunajacby)
- LinkedIn: [brunamgama](https://www.linkedin.com/in/brunamgama)
