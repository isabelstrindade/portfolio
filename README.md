# 💼 Portfólio Pessoal & Currículo Web

> Portfólio responsivo, acessível e profissional voltado para estudantes e profissionais de **Administração, Gestão e Empreendedorismo**, com gerador de currículo em PDF (A4) integrado e tema claro/escuro.

---

## 🚀 Demonstração & Recursos

- **Zero dependências externas:** Construído em puro HTML5, CSS3 e Vanilla JavaScript (sem necessidade de Node.js, npm ou bundlers).
- **🌓 Alternância de Tema Claro / Escuro:**
  - Detecta automaticamente a preferência do sistema operacional (`prefers-color-scheme`).
  - Salva a escolha do usuário no `localStorage` sem "flash" branco no carregamento.
- **📄 Currículo Integrado para Impressão/PDF:**
  - Layout dedicado para folha **A4** ativado via `@media print` ou pelo botão *"Currículo em PDF"*.
  - Oculta menus e elementos visuais da web, formatando o conteúdo automaticamente em padrão executivo para envio em processos seletivos.
- **🏷️ Filtro Dinâmico de Projetos:**
  - Filtragem instantânea por categorias (*Empreendedorismo*, *Extensão*, *Acadêmico*, *Gestão* e *Todos*).
  - Contador dinâmico e suporte a leitores de tela com `aria-live`.
- **📱 100% Responsivo:**
  - Menu expansível em dispositivos móveis.
  - Acompanha arquivos de pré-visualização (`_desktop.html` e `_mobile.html`) para testes locais em diferentes resoluções.
- **♿ Acessibilidade & SEO:**
  - *Skip link* para navegação por teclado.
  - Suporte a `prefers-reduced-motion` para usuários sensíveis a animações.
  - Marcação de dados estruturados **Schema.org (`Person`)** e tags Open Graph para redes sociais.

---

## 📁 Estrutura de Arquivos

```text
├── index.html          # Código completo da página (HTML, CSS e JavaScript integrados)
├── _desktop.html       # Visualizador de teste em resolução Desktop (1280x900)
├── _mobile.html        # Visualizador de teste em resolução Mobile (390x844)
├── midia/              # Pasta recomendada para fotos, anexos e mídias do projeto
├── .gitignore          # Regras para ignorar atalhos (.lnk), arquivos temporários e do SO
├── .gitattributes      # Padronização de quebras de linha (LF)
├── LICENSE             # Licença de uso de código aberto (MIT)
└── README.md           # Documentação completa do projeto
```

---

## 🌐 Link do Site Publicado

O site já está configurado e publicado no **GitHub Pages**:

🔗 **[https://isabelstrindade.github.io/portfolio/](https://isabelstrindade.github.io/portfolio/)**

---

## ✏️ Guia de Personalização

Antes de publicar o seu portfólio no GitHub, abra o arquivo `index.html` em qualquer editor de código (como VS Code, Notepad++ ou Bloco de Notas) e atualize os seguintes campos:

| Campo original no código | O que você deve colocar |
| :--- | :--- |
| `"Seu Nome"` | Seu nome completo |
| `"SN"` | Suas iniciais (usadas no monograma do logo e cartão) |
| `seu.email@exemplo.com` | Seu e-mail de contato |
| `+55 (00) 00000-0000` | Seu WhatsApp comercial/pessoal com DDD |
| `https://wa.me/5500000000000` | Link direto do seu WhatsApp com DDI + DDD + número |
| `@seu.usuario` | Seu perfil no Instagram ou LinkedIn |
| `github.com/seu-usuario` | Seu usuário no GitHub |
| `[Sua cidade — UF]` | Sua cidade e estado de residência |
| `[Nome da Universidade]` | Nome da sua faculdade / universidade |
| `Projetos 1 a 6` | Títulos, descrições e entregas reais dos seus projetos |

---

## 💻 Como Visualizar Localmente

Não é necessário instalar nenhum servidor ou programa pesado:

1. Dê um duplo clique diretamente no arquivo `index.html` para abrir no seu navegador padrão.
2. Para testar a responsividade e como o site fica em diferentes telas, abra:
   - `_desktop.html` (simula tela de computador)
   - `_mobile.html` (simula tela de celular smartphone)
3. Para gerar o currículo em PDF, clique no botão **"Currículo em PDF (via impressão)"** ou pressione `Ctrl + P` (Windows) / `Cmd + P` (Mac) e escolha a opção **"Salvar como PDF"**.

---

## 🌐 Como Publicar Gratuitamente no GitHub Pages

O GitHub oferece hospedagem gratuita com certificado de segurança HTTPS para este site:

### Passo 1: Criar o Repositório no GitHub
1. Acesse sua conta no [GitHub](https://github.com/) e clique em **New Repository** (Novo Repositório).
2. Dê um nome ao repositório (exemplo: `portfolio` ou `seu-usuario.github.io`).
3. Deixe o repositório marcado como **Public** (Público).
4. Clique em **Create repository**.

### Passo 2: Subir os Arquivos
Você pode enviar os arquivos pelo terminal Git ou diretamente pelo navegador:

#### Opção A: Pelo Terminal Git
```bash
git init
git add .
git commit -m "feat: versão inicial do portfólio e currículo"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```

#### Opção B: Pelo Navegador (Sem linha de comando)
1. Na página inicial do repositório recém-criado, clique em **uploading an existing file**.
2. Arraste os arquivos (`index.html`, `_desktop.html`, `_mobile.html`, `README.md`, etc.) para a tela.
3. Clique em **Commit changes**.

### Passo 3: Ativar o GitHub Pages
1. No seu repositório no GitHub, clique na aba **Settings** (Configurações) no topo.
2. No menu lateral esquerdo, clique em **Pages**.
3. Em **Build and deployment > Source**, selecione **Deploy from a branch**.
4. Abaixo, em **Branch**, selecione `main` e a pasta `/(root)`.
5. Clique em **Save**.
6. Em cerca de 1 a 2 minutos, o GitHub exibirá o link público do seu site (ex: `https://seu-usuario.github.io/portfolio/`).

---

## 📄 Licença

Este projeto é disponibilizado sob a licença [MIT](LICENSE). Sinta-se livre para usar, customizar e publicar o seu próprio portfólio.
