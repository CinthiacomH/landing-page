# 💻 Agência XPTO - Landing Page

Landing page responsiva desenvolvida para a Agência XPTO, uma agência digital fictícia focada em inovação e tecnologia. O projeto foi criado como parte dos estudos do curso **Dev em Dobro** e visa demonstrar habilidades em estruturação, estilização e manipulação do DOM.

A página possui um carrossel de projetos, seção "Quem Somos" e rodapé com redes sociais, utilizando apenas HTML, CSS e JavaScript.

## 🔗 Demonstração (Live Preview)

Acesse a versão hospedada do projeto:

👉 **[Ver o projeto online](https://cinthiacomh.github.io/landing-page/)**

## 🚀 Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias:

* **HTML5:** Para a estrutura e semântica da página.
* **CSS3 (Puro):** Para estilização, layout responsivo e transições suaves.
* **JavaScript (Puro):** Para a lógica de navegação do carrossel de projetos.
* **Font Awesome:** Para os ícones de redes sociais.
* **Google Fonts (Public Sans):** Para a tipografia.

## ✨ Recursos Principais

* **Carrossel de Projetos (Slider):** Utiliza botões "Voltar" e "Avançar" para alternar entre painéis de imagens de forma fluida, implementado com JavaScript puro.
* **Design Responsivo:** Layout totalmente adaptável a dispositivos móveis, com media queries bem definidas para o cabeçalho e rodapé.
* **Navegação com Âncoras:** Menu de navegação simples que direciona para as seções da página (`#projetos`, `#quem-somos`, `#contato`).
* **Estilização Moderna:** Uso de cores, filtros (`brightness(70%)`) e transições para um visual profissional.

## 🖼️ Estrutura de Arquivos

A organização do projeto segue a seguinte estrutura:
landing-page/
├── src/
│   ├── css/
│   │   ├── reset.css          # Estilos de reset e importação da fonte
│   │   └── style.css          # Estilos principais e regras de responsividade
│   ├── js/
│   │   └── painel.js          # Lógica de controle do carrossel (painel de imagens)
│   └── images/
│       ├── cafe.gif           # Logo da agência
│       ├── composition-12.svg # Imagem da seção Quem Somos
│       ├── painel1.jpg, ...   # Imagens de fundo para o carrossel de projetos
│       └── seta.png           # Imagem da seta de navegação do carrossel
└── index.html                 # Estrutura principal da landing page

## ⚙️ Como Rodar o Projeto

Este projeto é uma landing page estática e não requer um servidor ou instalações complexas.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/CinthiacomH/landing-page.git
    ```
2.  **Acesse a pasta do projeto:**
    ```bash
    cd landing-page
    ```
3.  **Abra o arquivo `index.html`** diretamente no seu navegador de preferência.

## 🛠️ Detalhes da Implementação
O arquivo painel.js gerencia o carrossel de projetos:

Ele rastreia o imagemAtual exibida.

Ao clicar nas setas (btn-avancar ou btn-voltar), ele verifica se atingiu o início ou o fim do painel para evitar erros.

A cada clique, ele remove a classe mostrar de todas as imagens e adiciona a classe mostrar apenas à imagem atual (imagensPainel[imagemAtual]), o que ativa a transição CSS de opacidade.

## 🤝 Contribuição
Sugestões de melhorias são bem-vindas, como:

Implementar navegação por bolinhas (dots) no carrossel.

Refatorar o JavaScript para ser mais reutilizável.

Adicionar mais seções (serviços, depoimentos de clientes).

Se você deseja contribuir, por favor, abra uma Issue ou um Pull Request.

<!-- ## 📝 Licença

Este projeto está sob a licença [Escolha uma licença, por exemplo: MIT, ISC ou simplesmente "Todos os direitos reservados"]. -->
