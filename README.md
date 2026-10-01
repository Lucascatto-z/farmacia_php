<div align="center">

# 💊 Farmácia PHP

**Sistema web de farmácia desenvolvido em PHP, HTML e CSS.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

</div>

---

## 📖 Sobre o projeto

O **farmacia_php** é uma aplicação web simples desenvolvida como projeto de estudo para praticar **PHP**, **HTML** e **CSS** no contexto de um sistema de farmácia.

O projeto conta com uma página HTML (`index.html`) que serve como interface de entrada, um arquivo de estilos (`style.css`) responsável pelo visual, e um script PHP (`farmacia.php`) que processa os dados enviados pelo usuário.

É um projeto ideal para quem está começando a aprender **integração entre formulários HTML e back-end em PHP**.

---

## ✨ Funcionalidades

- 🏠 Página inicial em HTML com formulário de entrada
- 💾 Processamento de dados via PHP (`farmacia.php`)
- 🎨 Estilização personalizada com CSS
- 📱 Estrutura simples e de fácil manutenção

> 💡 As funcionalidades específicas podem variar conforme a implementação atual dos arquivos.

---

## 🚀 Tecnologias utilizadas

| Tecnologia | Uso |
|------------|-----|
| **HTML5** | Estrutura da página e formulário |
| **CSS3** | Estilização e layout |
| **PHP** | Processamento dos dados do formulário |

---

## 📁 Estrutura do projeto

```
📁 farmacia_php/
├── index.html      → Página inicial com o formulário
├── farmacia.php    → Script PHP que processa os dados
├── style.css       → Estilos da aplicação
└── README.md       → Este arquivo
```

---

## 🛠️ Como executar o projeto

### 🔧 Pré-requisitos

Você precisa de um servidor com suporte a **PHP** (versão 7.0 ou superior). Algumas opções:

- **XAMPP** (Windows / Linux / macOS)
- **WAMP** (Windows)
- **MAMP** (macOS)
- **Laragon** (Windows)
- **PHP built-in server** (via terminal)

### 📥 Passo a passo

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/Lucascatto-z/farmacia_php.git
   ```

2. **Coloque a pasta no diretório do seu servidor**:

   - XAMPP: `C:\xampp\htdocs\farmacia_php`
   - MAMP: `/Applications/MAMP/htdocs/farmacia_php`
   - Laragon: `C:\laragon\www\farmacia_php`

3. **Inicie o servidor** (Apache, no caso do XAMPP).

4. **Acesse no navegador**:

   ```
   http://localhost/farmacia_php/index.html
   ```

### 🐘 Alternativa: PHP built-in server

Se você tem o PHP instalado, basta rodar na pasta do projeto:

```bash
php -S localhost:8000
```

E acessar: [http://localhost:8000/index.html](http://localhost:8000/index.html)

> ⚠️ **Importante:** o arquivo `farmacia.php` **precisa** ser executado por um servidor PHP. Abrir diretamente com duplo clique **não funcionará**.

---

## 🧠 Como funciona

### 1️⃣ A interface (`index.html`)

O usuário preenche um formulário HTML, que envia os dados via **POST** (ou GET) para o script PHP.

### 2️⃣ O processamento (`farmacia.php`)

O PHP recebe os dados enviados pelo formulário, processa as informações e retorna uma resposta dinâmica ao usuário.

### 3️⃣ A estilização (`style.css`)

Todo o visual da aplicação é controlado pelo arquivo `style.css`, deixando a interface organizada e agradável.

---

## 🎨 Personalização

Sinta-se à vontade para modificar:

- **`style.css`** → cores, fontes, layout, responsividade
- **`index.html`** → campos do formulário, textos, estrutura
- **`farmacia.php`** → regras de negócio, validações, cálculos

---

## 🗺️ Melhorias futuras

- [ ] Conexão com banco de dados (MySQL)
- [ ] Cadastro de medicamentos
- [ ] Controle de estoque
- [ ] Sistema de login de usuários
- [ ] Módulo de vendas
- [ ] Layout responsivo aprimorado

---

## 🤝 Contribuições

Contribuições são muito bem-vindas! Sinta-se à vontade para:

1. Fazer um **fork** do projeto
2. Criar uma branch: `git checkout -b minha-feature`
3. Commitar as mudanças: `git commit -m "feat: minha nova feature"`
4. Fazer o push: `git push origin minha-feature`
5. Abrir um **Pull Request**

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

**Lucas Catto**
- GitHub: [@Lucascatto-z](https://github.com/Lucascatto-z)

---

<div align="center">

⭐ Se este projeto te ajudou, deixe uma estrela no repositório! ⭐

</div>
