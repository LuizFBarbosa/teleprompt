# 🎙️ Teleprompt + Gravação de Áudio

Uma aplicação web all-in-one que combina um teleprompter profissional com sistema de gravação de áudio, ideal para criadores de conteúdo, YouTubers, podcasters e profissionais de apresentação.

![Acesse:](https://luizfbarbosa.github.io/teleprompt/)

## ✨ Funcionalidades

### 📝 Editor de Roteiro
- Área de texto para escrever ou colar seu roteiro
- Suporte a múltiplos parágrafos (separados por duas quebras de linha)
- Cada parágrafo se torna uma linha independente no teleprompter

### 📜 Teleprompter Inteligente
- Rolagem automática contínua do texto
- **Destaque visual da linha atual** (linha central da tela)
- Controle de velocidade ajustável (0.5x a 5x)
- Botões Play/Pause para controle da rolagem
- Interface responsiva que se adapta ao tamanho da tela

### 🎤 Gravação de Áudio
- Captura de áudio via microfone do dispositivo
- **Visualizador de ondas em tempo real** (mixer de áudio)
- Conversão automática para MP3 (via lamejs)
- Download do arquivo com timestamp automático

### 📱 PWA Light
- Funciona offline após primeiro acesso
- Pode ser instalado como atalho na tela inicial do celular
- Experiência de aplicativo nativo

## 🚀 Como Usar

### Acesso Rápido
1. Acesse a página pelo navegador (desktop ou mobile)
2. Conceda permissão para notificações (se solicitado)
3. Permita o acesso ao microfone quando for gravar

### Fluxo de Trabalho

#### 1. Prepare seu Roteiro

#### 2. Configure o Teleprompter
- Ajuste a velocidade de rolagem com o slider
- Clique em "Atualizar Teleprompter" para carregar o texto
- Use "Iniciar Rolagem" para começar
- Use "Parar Rolagem" para pausar

#### 3. Grave sua Narração
- Clique em "Gravar Áudio" (🔴)
- Leia o texto que rola na tela
- Observe o visualizador de ondas mostrando o áudio
- Clique em "Parar Gravação" quando terminar
- Aguarde a conversão para MP3
- Clique em "Baixar MP3" para salvar o arquivo

## 🛠️ Tecnologias Utilizadas

- **HTML5/CSS3** - Estrutura e estilização moderna
- **JavaScript (ES6+)** - Lógica da aplicação
- **Web Audio API** - Captura e processamento de áudio
- **MediaRecorder API** - Gravação em tempo real
- **lamejs** - Conversão para MP3 no cliente
- **Canvas API** - Visualização das ondas de áudio
- **Flexbox/Grid** - Layout responsivo

## 📦 Instalação e Uso Local

### Opção 1: Apenas abrir o arquivo
```bash
# Baixe o arquivo index.html
# Abra diretamente no navegador

Opção 2: Servidor local (recomendado para testes)
bash
# Usando Python
python -m http.server 8000

# Usando Node.js (com http-server)
npx http-server

# Acesse http://localhost:8000
Opção 3: GitHub Pages
Fork este repositório

Vá em Settings > Pages

Selecione branch main como fonte

Acesse https://seu-usuario.github.io/nome-do-repo

📱 Instalação como App no Celular
Android (Chrome)
Abra a página no Chrome

Toque no menu (⋮) > "Adicionar à tela inicial"

Confirme o nome e toque em "Adicionar"

iOS (Safari)
Abra a página no Safari

Toque no botão Compartilhar (⬆️)

Role e toque em "Adicionar à Tela de Início"

Confirme o nome e toque em "Adicionar"

🎯 Casos de Uso
YouTubers - Leia roteiros enquanto grava a tela

Podcasters - Grave episódios com acompanhamento visual

Apresentadores - Treine ou grave apresentações

Estudantes - Pratique discursos e monólogos

Profissionais - Crie vídeos institucionais com teleprompter

⚙️ Requisitos do Navegador
Desktop
Chrome 80+

Firefox 75+

Edge 80+

Safari 14+ (macOS)

Mobile
Chrome para Android

Safari para iOS 14+

Samsung Internet

Permissões Necessárias
✅ Microfone (para gravação)

✅ Armazenamento local (para download)

🔒 Privacidade e Segurança
100% client-side - Nenhum dado é enviado para servidores

Processamento local - Conversão para MP3 acontece no seu dispositivo

Sem tracking - Não há analytics ou cookies

Código aberto - Totalmente transparente
