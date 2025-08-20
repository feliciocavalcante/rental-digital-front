# Rental Digital Front

Sistema de aluguel digital - Interface Frontend moderna e responsiva.

## 📋 Descrição

O **Rental Digital Front** é uma aplicação web frontend para um sistema de aluguel digital, desenvolvido com tecnologias modernas para proporcionar uma experiência de usuário fluida e intuitiva.

## 🚀 Tecnologias Utilizadas

- **[React](https://reactjs.org/)** - Biblioteca JavaScript para construção de interfaces de usuário
- **[TypeScript](https://www.typescriptlang.org/)** - Superset do JavaScript com tipagem estática
- **[Vite](https://vitejs.dev/)** - Ferramenta de build rápida e moderna
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utilitário para estilização
- **[shadcn/ui](https://ui.shadcn.com/)** - Componentes de UI reutilizáveis e acessíveis
- **[Lovable](https://lovable.dev/)** - Plataforma de desenvolvimento integrada

## 📦 Pré-requisitos

Certifique-se de ter instalado em sua máquina:

- **Node.js** (versão 16 ou superior)
- **npm** ou **yarn**

### Instalação do Node.js com NVM (recomendado)

```bash
# Instale o NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

# Reinicie o terminal e instale a versão mais recente do Node.js
nvm install node
nvm use node
```

## 🛠️ Instalação e Configuração

### Método 1: Desenvolvimento Local

```bash
# 1. Clone o repositório
git clone https://github.com/feliciocavalcante/rental-digital-front.git

# 2. Navegue até o diretório do projeto
cd rental-digital-front

# 3. Instale as dependências
npm install

# 4. Inicie o servidor de desenvolvimento
npm run dev
```



### Método 2: GitHub Codespaces

1. Navegue até a página principal do repositório
2. Clique no botão **"Code"** (botão verde)
3. Selecione a aba **"Codespaces"**
4. Clique em **"New codespace"**
5. Edite os arquivos diretamente no Codespace

## 📝 Scripts Disponíveis

```bash
# Inicia o servidor de desenvolvimento
npm run dev

# Faz o build para produção
npm run build

# Executa o preview do build de produção
npm run preview

# Executa os testes
npm test

# Executa o linter
npm run lint
```

## 🏗️ Estrutura do Projeto

```
rental-digital-front/
├── public/                 # Arquivos públicos
├── src/                   # Código fonte
│   ├── components/        # Componentes reutilizáveis
│   ├── pages/            # Páginas da aplicação
│   ├── hooks/            # Hooks customizados
│   ├── lib/              # Utilitários e configurações
│   ├── types/            # Definições de tipos TypeScript
│   └── styles/           # Estilos globais
├── package.json          # Dependências e scripts
├── tailwind.config.js    # Configuração do Tailwind
├── tsconfig.json         # Configuração do TypeScript
└── vite.config.ts        # Configuração do Vite
```

## 🔧 Configuração do Ambiente

Crie um arquivo `.env.local` na raiz do projeto com as seguintes variáveis:

```env
# API Configuration
VITE_API_BASE_URL=http://localhost:3000/api
VITE_APP_NAME=Rental Digital

# Environment
VITE_NODE_ENV=development
```

## 🌐 Deploy

### Deploy Automático via Lovable

1. Abra o [Projeto - Aluguel de Carros](https://rental-digital-front.vercel.app/)

### Configurar Domínio Personalizado

1. Navegue para **Project** → **Settings** → **Domains**
2. Clique em **Connect Domain**
3. Siga as instruções para conectar seu domínio

📖 [Guia de configuração de domínio personalizado](https://docs.lovable.dev/tips-tricks/custom-domain#step-by-step-guide)

## 📱 Funcionalidades

- Interface moderna e responsiva
- Sistema de autenticação
- Gerenciamento de aluguéis
- Dashboard intuitivo
- Componentes reutilizáveis
- Tipagem TypeScript completa
- Otimizada para performance

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Felício Cavalcante**
- GitHub: [@feliciocavalcante](https://github.com/feliciocavalcante)

## 🆘 Suporte

Se você encontrar algum problema ou tiver dúvidas:

1. Verifique as [Issues](https://github.com/feliciocavalcante/rental-digital-front/issues) existentes
2. Crie uma nova issue se necessário
3. Consulte a [documentação do Lovable](https://docs.lovable.dev/)

---

⭐ **Se este projeto te ajudou, considere deixar uma estrela!**
