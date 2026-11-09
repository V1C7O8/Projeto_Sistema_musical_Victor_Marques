# 🎵 Sistema Musical — Plataforma Web (`Victor`)

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge">
  <img src="https://img.shields.io/badge/SENAI-FF0000?style=for-the-badge" alt="SENAI Badge">
  <img src="https://img.shields.io/badge/Layout-Responsivo-green?style=for-the-badge" alt="Responsivo Badge">
</p>

---

## 👤 Autor

| Nome do Aluno | Nº | Função / Contribuição |
| :--- | :---: | :--- |
| **Victor Marques dos Santos** | 30 | Desenvolvedor Web |

* **Curso:** Técnico em Desenvolvimento de Sistemas
* **Turma:** 1IF-DS
* **Instituição:** Escola SENAI A. Jacob Lafer

---

## 🎯 Sobre o Projeto

O **Sistema Musical** é uma interface web front-end desenvolvida para gerenciamento de acervo musical. A aplicação permite autenticação simulada de usuário, navegação por painel principal, cadastro de criadores (artistas), cadastro de obras (músicas) com link do YouTube e uma biblioteca completa para consulta e filtragem do catálogo.

---

## 🖥️ As 5 Telas da Aplicação

1. **`login.html` (Tela de Login):** Interface de acesso ao sistema com validação de campos obrigatórios, suporte a preenchimento automático e credenciais de teste para demonstração (`admin` / `123`). Contém o comentário com o nome do integrante no topo do arquivo.
2. **`index.html` (Menu Principal):** Painel de controle (*Dashboard*) centralizado com cartões interativos que direcionam para o gerenciamento de artistas, cadastro de músicas e biblioteca.
3. **`cadastro_artista.html` (Cadastro do Criador):** Formulário em duas colunas para registro de novos artistas (nome, gênero, país e upload de foto), integrado à exibição da tabela de artistas cadastrados.
4. **`cadastro_musica.html` (Cadastro da Obra):** Formulário completo com seleção de artista associado, título, álbum, gênero, link para vídeo do YouTube, envio de capa e área de texto para a letra da música.
5. **`listagem_musicas.html` (Biblioteca Musical):** Tabela de consulta do acervo com filtros rápidos por busca textual, artista e gênero, além de botões diretos para reprodução via YouTube.

---

## 🎨 Estilização Centralizada (`styles.css`)

Toda a identidade visual da aplicação foi construída em um único arquivo de folha de estilos (`styles.css`), utilizando variáveis de ambiente no `:root`:

* **Paleta de Cores Temática:**
  * `--primary` (`#2c3e50`): Títulos e cabeçalhos de tabela.
  * `--blue` (`#3498db`): Botões de ação principal e edição.
  * `--green` (`#27ae60`): Botões de navegação para músicas do artista.
  * `--red` (`#e74c3c`): Destaques de campos obrigatórios e exclusão.
  * `--bg` (`#f0f2f5`): Fundo padrão neutro.
* **Layout Responsivo:** Implementado com CSS Grid e Flexbox, garantindo transição fluida entre monitores *desktop* e dispositivos móveis (telas de até 768px via `@media`).

---

## 📂 Estrutura de Arquivos do Repositório

```text
musica-victor/
├── login.html             # Tela de Login (Contém nome do autor no topo)
├── index.html             # Menu principal do sistema
├── cadastro_artista.html  # Tela de cadastro e tabela de artistas
├── cadastro_musica.html   # Tela de cadastro de músicas
├── listagem_musicas.html  # Biblioteca musical com filtros e listagem
├── styles.css             # Arquivo único de estilos (CSS Variables + Grid + Responsividade)
└── README.md              # Documentação oficial do repositório
