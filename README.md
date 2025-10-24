# 🚀 Realize Analytics - Build Estática

## 📁 O que é esta pasta?

Esta pasta contém o **Realize Analytics** compilado como arquivos estáticos HTML, CSS e JavaScript. Você pode colocar esta pasta em **qualquer servidor web** e o projeto funcionará perfeitamente!

## 🌐 Como usar em qualquer servidor

### Opção 1: Servidor Web Local
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

### Opção 2: Servidor Apache/Nginx
1. **Copie toda a pasta `build/`** para o diretório web do seu servidor
2. **Configure o servidor** para servir arquivos estáticos
3. **Acesse** via navegador

### Opção 3: Hospedagem Estática
- **Netlify**: Arraste a pasta `build/` para o Netlify
- **Vercel**: Faça upload da pasta `build/`
- **GitHub Pages**: Coloque os arquivos na branch `gh-pages`
- **Firebase Hosting**: Use `firebase deploy`

## 📂 Estrutura dos Arquivos

```
build/
├── index.html          # Página principal
├── courses/            # Páginas de cursos
├── students/           # Páginas de alunos
├── login/              # Página de login
├── reports/            # Página de relatórios
├── settings/           # Página de configurações
├── _next/              # Assets do Next.js
├── logo.svg            # Logo da empresa
├── manifest.json       # PWA manifest
├── robots.txt          # SEO robots
├── sitemap.xml         # SEO sitemap
└── _redirects          # Redirecionamentos
```

## ✅ Funcionalidades Incluídas

- ✅ **Dashboard completo** com KPIs e gráficos
- ✅ **Gestão de cursos** com estrutura hierárquica
- ✅ **Gestão de alunos** com perfis detalhados
- ✅ **Página de login** moderna
- ✅ **Relatórios** e configurações
- ✅ **SEO otimizado** (sitemap, robots, manifest)
- ✅ **Design responsivo** para mobile/tablet/desktop
- ✅ **CSS e JavaScript** otimizados

## 🔧 Configuração do Servidor

### Apache (.htaccess)
```apache
RewriteEngine On
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^(.*)$ /index.html [QSA,L]
```

### Nginx
```nginx
location / {
    try_files $uri $uri/ /index.html;
}
```

## 📱 Teste Local Rápido

1. **Abra o terminal** na pasta `build/`
2. **Execute**: `python -m http.server 8000`
3. **Acesse**: `http://localhost:8000`
4. **Pronto!** O dashboard está funcionando

## 🎯 URLs Disponíveis

- `/` - Dashboard principal
- `/courses` - Lista de cursos
- `/students` - Lista de alunos
- `/login` - Página de login
- `/reports` - Relatórios
- `/settings` - Configurações

## ⚡ Performance

- **Build otimizada** para produção
- **CSS minificado** e otimizado
- **JavaScript comprimido**
- **Imagens otimizadas**
- **Carregamento rápido**

## 🔒 Segurança

- **Headers de segurança** configurados
- **CSP (Content Security Policy)** implementado
- **HTTPS ready** para produção

---

**Realize Analytics** - Pronto para produção! 🚀

Para dúvidas: suporte@realizeanalytics.com