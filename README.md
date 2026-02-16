# Sparta Cursos - Site Institucional

Site institucional one page para a Sparta Cursos, preparatório especializado em carreiras policiais em Maceió, Alagoas.

## 📋 Sobre o Projeto

Site moderno e responsivo desenvolvido para apresentar os serviços da Sparta Cursos, incluindo:
- Preparatórios para Polícia Militar (PMAL)
- Preparatórios para Polícia Civil (PCAL)
- Preparatórios para Guarda Municipal (GCM)
- Preparatórios para Polícia Penal

## 🚀 Publicação no GitHub Pages

### Passo 1: Criar Repositório

1. Acesse [GitHub](https://github.com) e faça login
2. Clique em "New" para criar um novo repositório
3. Nomeie o repositório (ex: `sparta-cursos-site`)
4. Deixe como **público**
5. Clique em "Create repository"

### Passo 2: Upload dos Arquivos

#### Opção A: Via Interface Web

1. No repositório criado, clique em "uploading an existing file"
2. Arraste os arquivos:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `logo.jpg`
3. Clique em "Commit changes"

#### Opção B: Via Git (Terminal)

```bash
# Inicializar git no diretório
git init

# Adicionar os arquivos
git add .

# Fazer o commit
git commit -m "Initial commit - Sparta Cursos website"

# Adicionar o repositório remoto (substitua USERNAME e REPO)
git remote add origin https://github.com/USERNAME/REPO.git

# Enviar para o GitHub
git branch -M main
git push -u origin main
```

### Passo 3: Ativar GitHub Pages

1. No repositório, vá em **Settings** (Configurações)
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione:
   - Branch: `main`
   - Folder: `/ (root)`
4. Clique em **Save**
5. Aguarde alguns minutos e seu site estará disponível em:
   `https://USERNAME.github.io/REPO/`

## 📁 Estrutura de Arquivos

```
sparta-cursos-site/
│
├── index.html          # Página principal HTML
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interatividade
├── logo.jpg            # Logo da Sparta Cursos
└── README.md           # Este arquivo
```

## 🎨 Características

### Design
- ✅ Design moderno e profissional
- ✅ Paleta de cores institucional (azul royal, dourado)
- ✅ Layout responsivo (mobile-first)
- ✅ Animações suaves e elegantes
- ✅ Ícones Font Awesome

### Funcionalidades
- ✅ Menu de navegação fixo
- ✅ Botão flutuante WhatsApp
- ✅ Botão "Voltar ao topo"
- ✅ Menu mobile responsivo
- ✅ Smooth scroll entre seções
- ✅ Animações ao scroll
- ✅ Google Maps integrado

### Seções
1. **Hero** - Banner principal com CTA
2. **Sobre** - Informações da empresa
3. **Carreiras** - Cursos oferecidos
4. **Disciplinas** - Matérias abordadas
5. **Professores** - Corpo docente
6. **Diferenciais** - Por que escolher a Sparta
7. **CTA** - Call-to-action intermediário
8. **Contato** - Informações e mapa
9. **Footer** - Links e redes sociais

## 🔧 Personalização

### Alterar Cores

No arquivo `styles.css`, modifique as variáveis CSS:

```css
:root {
    --primary-color: #1a237e;      /* Azul principal */
    --secondary-color: #FFD700;     /* Dourado */
    --accent-color: #DC143C;        /* Vermelho */
}
```

### Alterar Conteúdo

Edite o arquivo `index.html` e modifique os textos conforme necessário.

### Adicionar/Remover Seções

No `index.html`, cada seção está claramente marcada com comentários:
```html
<!-- Nome da Seção -->
<section class="nome-secao" id="id-secao">
    <!-- Conteúdo -->
</section>
```

## 📱 Responsividade

O site é totalmente responsivo e otimizado para:
- 📱 Mobile (smartphones)
- 📱 Tablet
- 💻 Desktop
- 🖥️ Telas grandes

## 🌐 Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Grid, Variables)
- JavaScript (ES6+)
- Font Awesome 6.4.0
- Google Fonts (Poppins)
- Google Maps API

## 📞 Informações de Contato

**Sparta Cursos**
- 📍 Endereço: Av. Grand Jardim, 960 - Sala 32, Cidade Universitária, Maceió - AL
- 📱 Telefone: (82) 99658-2460
- 📧 E-mail: contato.spartacursos@gmail.com
- 📷 Instagram: @spartacursos.oficial
- 🏢 CNPJ: 63.055.728/0001-30

## 🔒 Licença

Este projeto é propriedade da Sparta Cursos. Todos os direitos reservados.

## 👨‍💻 Suporte

Para dúvidas ou suporte técnico, entre em contato através dos canais oficiais da Sparta Cursos.

---

**Desenvolvido com ❤️ para Sparta Cursos**

*Sua aprovação começa aqui!* 🛡️
