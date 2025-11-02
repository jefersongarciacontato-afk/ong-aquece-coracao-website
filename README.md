![Logo da ONG Aquece Coração](images/logotipo.png)

# ONG Aquece Coração - Plataforma Web

[![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Status do Projeto](https://img.shields.io/badge/status-conclu%C3%ADdo-green.svg)](#)

Uma plataforma web front-end completa e responsiva para a ONG "Aquece Coração", focada em divulgar projetos, contar sua história e capturar cadastros de novos voluntários.

---

### 📖 Tabela de Conteúdos

* [Visão Geral do Projeto](#-visão-geral-do-projeto)
* [Funcionalidades Principais](#-funcionalidades-principais)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Estrutura de Arquivos](#-estrutura-de-arquivos)
* [Como Executar](#-como-executar)
* [Contexto Acadêmico](#-contexto-acadêmico)
* [Autor](#-autor)

---

### 🎯 Visão Geral do Projeto

Este projeto simula o desenvolvimento front-end de um site institucional para uma ONG fictícia. O objetivo principal é criar uma presença digital profissional que inspire confiança, conte a história da organização e sirva como um canal eficaz para a captação de voluntários, aplicando conceitos modernos de desenvolvimento web, desde a estruturação semântica com HTML5 até a interatividade com JavaScript.

---

### ✨ Funcionalidades Principais

* **Design Responsivo (Mobile-First):** Totalmente adaptável a desktops, tablets e smartphones.
* **Sistema de Design Consistente:** Uso de variáveis CSS para uma paleta de cores, tipografia e espaçamento modulares.
* **Navegação Intuitiva:** Menu principal com submenu (dropdown) e menu hambúrguer para dispositivos móveis.
* **Páginas Institucionais:**
    * **Home:** Com um banner "hero" impactante e destaques do impacto da ONG.
    * **Nossa História:** Uma página dedicada a contar a trajetória da organização, criando conexão emocional.
    * **Projetos:** Detalhamento da principal campanha ("Missão Cobertor") com indicadores de impacto.
* **Formulário de Cadastro Complexo:**
    * Agrupamento lógico de campos (`fieldset`).
    * **Validação de dados nativa (HTML5)** para todos os campos obrigatórios.
    * **Validação interativa (JavaScript)** que exibe mensagens de erro sem recarregar a página.
    * **Máscaras de entrada (IMask.js)** para campos de CPF, Telefone e CEP, melhorando a experiência do usuário.

---

### 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as principais tecnologias do front-end:

* **HTML5:** Estruturação semântica, atributos de acessibilidade e validação de formulários.
* **CSS3:**
    * Variáveis CSS (Custom Properties) para o Sistema de Design.
    * **Flexbox** e **CSS Grid** para layouts complexos e responsivos.
    * Media Queries para 5 pontos de interrupção (breakpoints).
    * Estados de UI (`:hover`, `:focus`, `:active`) em botões e links.
* **JavaScript (ES6+):**
    * Manipulação do DOM para o menu hambúrguer.
    * Validação interativa do formulário de cadastro.
* **IMask.js:** Biblioteca externa para aplicação de máscaras nos campos do formulário.

---

### 🗂️ Estrutura de Arquivos

A estrutura de pastas do projeto é organizada para separar claramente as responsabilidades:
