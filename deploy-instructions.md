# 📋 INSTRUÇÕES DE DEPLOY - GitHub Pages

## 🚀 Como Publicar no GitHub Pages

### 1️⃣ Criar Repositório no GitHub
1. Acesse [github.com](https://github.com) e faça login
2. Clique em "New repository"
3. Nome sugerido: `conecta-rural-telecom`
4. Marque como "Public"
5. NÃO marque "Initialize with README" (já temos um)
6. Clique "Create repository"

### 2️⃣ Fazer Upload dos Arquivos
**Opção A - Interface Web (Mais Fácil):**
1. No seu repositório, clique "uploading an existing file"
2. Arraste TODOS os arquivos desta pasta
3. Commit message: "Initial commit - CONECTA Rural landing page"
4. Clique "Commit changes"

**Opção B - Git Command Line:**
```bash
git init
git add .
git commit -m "Initial commit - CONECTA Rural landing page"
git branch -M main
git remote add origin https://github.com/SEUUSUARIO/conecta-rural-telecom.git
git push -u origin main
```

### 3️⃣ Ativar GitHub Pages
1. Vá em "Settings" do repositório
2. Role até a seção "Pages"
3. Source: "Deploy from a branch"
4. Branch: "main"
5. Folder: "/ (root)"
6. Clique "Save"

### 4️⃣ Configurar Domínio (Opcional)
Se você tem um domínio próprio:
1. Na seção Pages, em "Custom domain"
2. Digite: `conectarural.com.br`
3. Marque "Enforce HTTPS"

### 5️⃣ URLs de Acesso
- **GitHub Pages:** `https://seuusuario.github.io/conecta-rural-telecom`
- **Domínio personalizado:** `https://conectarural.com.br`

## 🔧 Arquivos Incluídos

- ✅ `index.html` - Landing page principal
- ✅ `README.md` - Documentação do projeto
- ✅ `CNAME` - Configuração de domínio personalizado
- ✅ `.gitignore` - Arquivos a serem ignorados pelo Git
- ✅ `_config.yml` - Configuração Jekyll
- ✅ `robots.txt` - Configuração SEO para buscadores
- ✅ `sitemap.xml` - Mapa do site para SEO
- ✅ `LICENSE` - Licença MIT
- ✅ `deploy-instructions.md` - Este arquivo

## 📊 Próximos Passos Após Deploy

### SEO e Analytics
1. **Google Search Console**
   - Adicione a propriedade do seu site
   - Submeta o sitemap.xml

2. **Google Analytics**
   - Substitua `G-XXXXXXXXXX` no _config.yml pelo seu ID

3. **Facebook Pixel** (se usar Facebook Ads)
   - Adicione o código no index.html

### Marketing Digital
1. **Google My Business** - Adicione a URL do site
2. **Redes Sociais** - Link na bio de todas as redes
3. **WhatsApp Business** - Use o link nas mensagens automáticas

## 🆘 Suporte
Em caso de dúvidas:
- Documentação GitHub Pages: https://pages.github.com
- Suporte Jekyll: https://jekyllrb.com/docs/

**Desenvolvido por Tiago Cordeiro - Vereador de Apucarana/PR**
