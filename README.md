# 💬 Quote Editor

Um aplicativo web moderno, rápido e reativo para gerenciamento e edição de citações (quotes). Este projeto foi desenvolvido para demonstrar o uso do ecossistema **Ruby on Rails** moderno, combinando a robustez do backend Rails com a reatividade de uma Single Page Application (SPA) utilizando **Hotwire (Turbo e Stimulus)**, sem a necessidade de frameworks Javascript complexos no frontend.

---

## 🚀 Tecnologias Utilizadas

* **Backend:** Ruby 3.x / Rails 7.x
* **Frontend:** Hotwire (Turbo Frames, Turbo Streams & Stimulus JS)
* **Estilização:** Tailwind CSS (via Tailwind CSS Rails gem)
* **Banco de Dados:** PostgreSQL (ou SQLite para desenvolvimento)
* **Testes:** RSpec (ou Minitest) & System Tests (Capybara)

---

## ✨ Funcionalidades Principais

* **CRUD Completo de Cotações:** Criação, visualização, edição e exclusão de citações de forma instantânea.
* **Atualizações em Tempo Real (Real-time):** Uso de **Turbo Streams** para atualizar a interface instantaneamente sem recarregar a página.
* **Componentização com Turbo Frames:** Edição e criação de registros inline de forma fluida.
* **Design Responsivo:** Interface limpa, moderna e adaptável para dispositivos móveis e desktops utilizando Tailwind CSS.
* **Segurança e Escopo:** Organização de dados com autenticação/isolamento de dados por conta ou usuário (Multi-tenancy básico).

---

## 🛠️ Como Executar o Projeto Localmente

Siga os passos abaixo para rodar a aplicação em sua máquina de desenvolvimento:

### Pré-requisitos
Certifique-se de ter instalado em sua máquina:
* **Ruby** (versão recomendada no arquivo `.ruby-version`)
* **Rails 7+**
* **Yarn** ou **NPM** (caso utilize assets JS externos)
* **PostgreSQL** (se configurado como banco padrão)

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/raphaelcampean/quote-editor.git](https://github.com/raphaelcampean/quote-editor.git)
   cd quote-editor