# Desafio CESAR

Projeto desenvolvido como parte do processo seletivo para a vaga de UI Developer Mid-Level na CESAR.

## Sobre o Desafio

O desafio consiste em:

1. **Design Proposal**: Criar uma proposta de design baseada no wireframe fornecido
2. **Implementação HTML/CSS**: Desenvolver a página estática seguindo o design proposto

## Etapa 1: Design

O arquivo PNG do design está disponível em `data/mockup.png`.

O design foi desenvolvido no Figma e pode ser acessado através do link:
[https://www.figma.com/design/7o9t3L0tbwwj6TtpcXAJ3J/Desafio-CESAR?node-id=1-123&t=1QAmApu7YCjN578C-1](https://www.figma.com/design/7o9t3L0tbwwj6TtpcXAJ3J/Desafio-CESAR?node-id=1-123&t=1QAmApu7YCjN578C-1)

### Estrutura do Figma

- **Style Guide**: Página com tokens de design system
  - Tokens de cores (brand colors fornecidas no desafio)
  - Tokens de tipografia
- **Componentes**: Criação de componentes
  - Navbar
  - Input fields
  - Buttons (primary e secondary)

## Etapa 2: Implementação HTML/CSS

### Estrutura do Projeto

    .
    ├── index.html
    ├── main.css
    ├── assets/             # Imagens e ícones
    ├── data/               # Mockup do design
    │   └── mockup.png
    └── README.md

### Design System
O projeto utiliza um sistema de tokens CSS para manter consistência visual. Os tokens são definidos em `main.css` e podem ser customizados para atender às necessidades do projeto.

#### Acessibilidade
O projeto implementa boas práticas de acessibilidade, como navegação por teclado e HTML semântico.

#### Responsividade
O layout é responsivo e se adapta a diferentes tamanhos de tela:

- Desktop (> 1280px): Layout completo
- Tablet (640px - 1280px): Painel ocupa largura disponível
- Mobile (< 640px):
  - Formulário em coluna única
  - Elementos da navbar ocultos para melhor uso de espaço

## Como executar
- Clone o repositório disponível em: https://github.com/johnn1sbo3s/desafio_cesar
- Abra o arquivo `index.html` diretamente no navegador.
