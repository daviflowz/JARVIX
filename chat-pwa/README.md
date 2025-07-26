# Chat AI - PWA Mobile First

Um aplicativo de chat moderno e intuitivo para conversar com inteligência artificial, construído com React, TypeScript e Tailwind CSS. O design é inspirado no Pinterest, com foco em mobile-first e funcionalidades PWA.

## 🚀 Funcionalidades

- **Interface Moderna**: Design inspirado no Pinterest com gradientes e animações suaves
- **Mobile First**: Otimizado para dispositivos móveis com design responsivo
- **PWA**: Progressive Web App com capacidade de instalação e funcionamento offline
- **IA Avançada**: Integração com Google Gemini AI para conversas inteligentes
- **Chat em Tempo Real**: Interface de chat fluida com indicadores de digitação
- **Histórico de Conversa**: Mantém o contexto das conversas
- **Sugestões Rápidas**: Botões de sugestão para iniciar conversas
- **Temas Personalizados**: Cores e estilos inspirados no Pinterest

## 🛠️ Tecnologias Utilizadas

- **React 18** com TypeScript
- **Tailwind CSS** para estilização
- **Google Generative AI** (Gemini) para IA
- **Lucide React** para ícones
- **PWA** com Service Worker
- **Mobile First** design responsivo

## 📱 Características do Design

- **Cores**: Esquema de cores do Pinterest (#E60023)
- **Tipografia**: Inter font para melhor legibilidade
- **Animações**: Transições suaves e micro-interações
- **Layout**: Grid masonry inspirado no Pinterest
- **Componentes**: Botões arredondados e cards com sombras
- **Responsividade**: Adaptável a todos os tamanhos de tela

## 🔧 Instalação e Uso

1. **Clone o repositório**:
   ```bash
   git clone <url-do-repositorio>
   cd chat-pwa
   ```

2. **Instale as dependências**:
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**:
   ```bash
   npm start
   ```

4. **Acesse o aplicativo**:
   Abra [http://localhost:3000](http://localhost:3000) no navegador

## 📦 Build para Produção

```bash
npm run build
```

O build otimizado será criado na pasta `build/`.

## 📱 Instalação como PWA

1. Acesse o aplicativo no navegador
2. Procure pelo ícone "Instalar app" na barra de endereços
3. Clique em "Instalar" para adicionar à tela inicial
4. O app funcionará como um aplicativo nativo

## 🔑 Configuração da API

A chave da API do Google já está configurada no projeto:
```typescript
const API_KEY = 'AIzaSyBvI-LCxl8u3tFjKZOIaNcpZr499pcVD9Q';
```

## 🎨 Estrutura de Componentes

```
src/
├── components/
│   ├── ChatContainer.tsx    # Container principal do chat
│   ├── ChatMessage.tsx      # Componente de mensagem
│   ├── ChatInput.tsx        # Input de mensagem
│   ├── Header.tsx           # Cabeçalho do app
│   └── EmptyState.tsx       # Estado vazio
├── services/
│   └── googleAI.ts          # Serviço de integração com Google AI
├── App.tsx                  # Componente principal
└── index.tsx               # Ponto de entrada
```

## 🎯 Funcionalidades Principais

### Chat Inteligente
- Conversas contextuais com IA
- Histórico de mensagens
- Indicadores de digitação
- Tratamento de erros

### Interface Moderna
- Design mobile-first
- Animações CSS suaves
- Componentes reutilizáveis
- Tema Pinterest

### PWA Features
- Instalável como app nativo
- Funcionamento offline (cache)
- Service Worker configurado
- Manifest.json otimizado

## 🔧 Personalização

### Cores
Edite o arquivo `tailwind.config.js` para personalizar as cores:

```javascript
colors: {
  pinterest: {
    red: '#E60023',
    'red-dark': '#B8001F',
    'red-light': '#FF3040',
  }
}
```

### Estilos
Modifique `src/index.css` para ajustar estilos globais e componentes.

## 📱 Compatibilidade

- **Navegadores**: Chrome, Firefox, Safari, Edge (versões modernas)
- **Dispositivos**: Smartphones, tablets, desktops
- **PWA**: Suporte completo para instalação em dispositivos móveis

## 🚀 Deploy

O aplicativo pode ser deployado em qualquer serviço de hospedagem estática:

- **Vercel**: `npm i -g vercel && vercel`
- **Netlify**: Arrastar pasta `build/` para Netlify
- **Firebase Hosting**: `firebase deploy`
- **GitHub Pages**: Configurar workflow de deploy

## 📄 Licença

Este projeto é de código aberto e está disponível sob a licença MIT.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature
3. Fazer commit das mudanças
4. Fazer push para a branch
5. Abrir um Pull Request

## 📞 Suporte

Para dúvidas ou suporte, abra uma issue no repositório do projeto.

---

Desenvolvido com ❤️ usando React, TypeScript e Tailwind CSS
