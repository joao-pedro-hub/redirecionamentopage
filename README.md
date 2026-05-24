# 🌐 Landing Page com Redirecionamento
 
Projeto de página web estática composto por duas telas: uma página de entrada com uma chamada para ação e uma página de destino para onde o usuário é redirecionado ao clicar no botão.
 
Desenvolvido com **HTML e CSS puro**, sem dependências externas, e publicado via **GitHub Pages**.
 
---
 
## 📸 Estrutura do Projeto
 
```
📁 repositório/
│
├── index.html          → Página principal (aviso + botão)
├── style.css           → Estilo da página principal
│
└── 📁 site-destino/
    ├── sitedestino.html → Página de destino
    ├── sitedestino.css  → Estilo da página de destino
    └── download.png     → Imagem exibida na página de destino
```
 
---
 
## ✨ Funcionalidades
 
- ✅ Página de entrada com texto e botão de redirecionamento
- ✅ Navegação para página de destino ao clicar no botão
- ✅ Design responsivo com media queries para mobile
- ✅ Imagem customizável na página de destino
- ✅ Pronto para publicação no GitHub Pages
---
 
## 🚀 Como usar
 
### 1. Clone o repositório
 
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```
 
### 2. Abra o projeto
 
Abra o arquivo `index.html` diretamente no navegador ou use uma extensão como **Live Server** no VS Code.
 
---
 
## 🌍 Deploy no GitHub Pages
 
1. Vá em **Settings** no seu repositório
2. Clique em **Pages** no menu lateral
3. Em *Branch*, selecione **main** e clique em **Save**
4. Seu site estará disponível em:
```
https://seu-usuario.github.io/nome-do-repositorio/
```
 
---
 
## 🛠️ Personalização
 
### Alterar textos da página principal
 
Edite o arquivo `index.html`:
 
```html
<h1>Atenção</h1>
<p>texto de exemplo</p>
```
 
### Alterar a imagem da página de destino
 
Coloque sua imagem dentro da pasta `site-destino/` e atualize o `src` em `sitedestino.html`:
 
```html
<img src="nome-da-sua-imagem.png" alt="Descrição da imagem">
```
 
---
 
## 🧰 Tecnologias utilizadas
 
- HTML5
- CSS3
- Media Queries (responsividade)
---
 
## 📄 Licença
 
Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.
