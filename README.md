# AcessibilidadeNaWeb

Site sobre Tropicália refatorado com foco em acessibilidade web.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Sumário

- [Sobre](#sobre)
- [Recursos de acessibilidade](#recursos-de-acessibilidade)
- [Tecnologias](#tecnologias)
- [Como executar](#como-executar)
- [Estrutura](#estrutura)
- [Licença](#licença)
- [Autor](#autor)

## Sobre

Refatoração de um site temático sobre Tropicália, implementando recursos de acessibilidade em HTML, CSS e JavaScript. Projeto do 3º bimestre de Programação.

## Recursos de acessibilidade

- Atributos `aria-label` e `aria-expanded`
- Textos alternativos (`alt`) e `title` descritivos
- Navegação por teclado com `tabindex`
- Menu de acessibilidade: A+ / A- (tamanho da fonte) e alto contraste
- Ícones Bootstrap com rótulos acessíveis

> [!NOTE]
> O botão "acessibilidade" expande as opções. O contraste alterna uma classe no `body`.

## Tecnologias

- HTML5 semântico (`header`, `main`, `section`)
- CSS3 + Bootstrap 5.3 + Bootstrap Icons
- JavaScript (menu, fonte, contraste)
- ScrollReveal (animações de rolagem)

## Como executar

```bash
git clone https://github.com/VictorHFL/AcessibilidadeNaWeb.git
cd AcessibilidadeNaWeb
# abra index.html no navegador
```

> [!TIP]
> Teste com leitor de tela e navegação por Tab para validar os rótulos ARIA.

## Estrutura

```text
AcessibilidadeNaWeb/
├── index.html
├── styles.css
├── script.js
├── img/
└── README.md
```

## Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para detalhes.

## Autor

**VictorHFL**

- GitHub: [@VictorHFL](https://github.com/VictorHFL)
- E-mail: yvictorhfl@gmail.com
