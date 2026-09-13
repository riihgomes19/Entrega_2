# 💻 InfoTech - Portal de Produtos de Tecnologia

Este repositório contém a interface web (UI) do projeto **InfoTech**, desenvolvida como parte da **Entrega 2** da disciplina de desenvolvimento front-end. O projeto consiste em um portal visual interativo para exibição de categorias de produtos de tecnologia (notebooks, celulares, PCs e placas de vídeo) com menu lateral adaptável.

---

## 🛠️ Tecnologias Utilizadas

Para o desenvolvimento desta aplicação, foram adotadas as seguintes tecnologias:

* **HTML5:** Utilizado para a estruturação semântica de todo o conteúdo da página (`<aside>`, `<main>`, `<section>`, `<footer>`, etc.).
* **CSS3:** Responsável pela estilização visual, layout responsivo via `Flexbox`, posicionamento fixo de elementos e efeitos de transição/hover nos cards.
* **JavaScript (Vanilla JS):** Empregado para manipular o DOM e permitir o dinamismo de abas e recolhimento da barra lateral.

---

## 📁 Estrutura de Pastas

A organização dos arquivos do projeto local está estruturada da seguinte forma:

```text
infotech-frontend/
│
├── index.html              # Arquivo HTML principal da aplicação
├── style.css               # Folha de estilos e regras visuais
├── script.js               # Código JavaScript com a lógica da interface
├── README.md               # Documentação completa do repositório
│
└── assets/                 # Pasta dedicada às imagens do projeto
    ├── qual-a-tecnologia.jpg
    ├── notebook.jpg
    ├── celular.jpg
    ├── pcs.jpg
    └── placas de video.jpg
```

---

## 🚀 Instruções de Execução

Você pode executar e testar o projeto em sua máquina local seguindo os passos abaixo:

### Pré-requisitos
* Um navegador web atualizado (Google Chrome, Mozilla Firefox, Microsoft Edge ou Safari).
* Opcional: editor **VS Code** com a extensão **Live Server**.

### Passo a Passo

1. **Clonar ou Baixar o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. **Acessar o Diretório do Projeto:**
   ```bash
   cd infotech-frontend
   ```

3. **Executar a Aplicação:**
   * **Via Navegador Directo:** Dê um duplo clique no arquivo `index.html` ou abra-o diretamente pelo seu navegador preferido.
   * **Via VS Code (Recomendado):** Abra a pasta no VS Code, clique com o botão direito sobre o arquivo `index.html` e selecione **"Open with Live Server"**.

---

## 📋 Funcionalidades da Interface

- [x] **Barra Lateral (Sidebar):** Painel de navegação com dados de perfil e menus interativos.
- [x] **Grid de Produtos:** Exibição em cards para notebooks, celulares, PCs e componentes de hardware.
- [x] **Feedback Visual:** Animações e elevação de cards ao passar o ponteiro do mouse (*hover*).
- [x] **Rodapé Fixo:** Seção inferior com direitos autorais e atalhos para redes sociais.

---

## ⚙️ Gestão e Versionamento

* **Metodologia Ágil (Sprint 1):** Planejamento e organização de tarefas realizados no **Trello**.
* **Controle de Versão:** Versionado utilizando **Git** e integrado ao repositório remoto no **GitHub/GitLab**.

---

© 2026 **InfoTech** — Todos os direitos reservados.