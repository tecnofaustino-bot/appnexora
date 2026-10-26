# NEXORA — Crie. Publique. Evolua.

Plataforma SaaS moderna, premium e preparada para produção para criação de produtos digitais com inteligência artificial, destinada principalmente a jovens e empreendedores, acessível a qualquer pessoa que queira criar aplicações, páginas e sistemas sem precisar dominar programação.

---

## 🌟 Proposta Central
> **“Transformar uma ideia em um produto digital profissional, desde a concepção até a publicação.”**

---

## 🚀 Tipos de Produtos Criados
- **Aplicações Web**
- **Progressive Web Apps (PWA)**
- **Aplicações Android** (preparadas com Gradle, APK e AAB)
- **Projetos para iOS** (configuração de workspace Xcode e Podfile)
- **Aplicações para Windows/Desktop** (empacotamento Electron/Tauri)
- **Landing pages de alta conversão**
- **Páginas de vendas** com checkout integrado
- **Sites institucionais e portfólios**
- **Dashboards e sistemas internos**
- **MVPs e protótipos funcionais**

---

## 🏗️ Arquitetura Tecnológica Full-Stack

### Frontend
- **React 19 & TypeScript**
- **Tailwind CSS v4**
- **Lucide Icons & Framer Motion**
- **Command Palette (`Ctrl + K`)**
- **Guia do Iniciante** sem jargões para leigos (GitHub, Domínio, API, Hosting, Deploy, Build)
- **Design System com Dark Mode Principal** e Light Mode opcional
- **Exportação de Projetos em ZIP** com estrutura completa de arquivos

### Backend
- **Node.js & Express**
- **@google/genai SDK** (`gemini-3.8-flash` no lado do servidor) com telemetry `User-Agent: aistudio-build`
- **Controle de Acessos RBAC** (Super Admin, Admin, User)
- **Sistema de Quotas e Limites de Uso**
- **PaymentProvider Abstraction** (M-Pesa, E-Mola, Cartão, Transferência e Confirmação Manual)
- **Auditoria & Activity Logs** em conformidade com segurança (sem registro de senhas ou tokens)
- **GitHub App Integration** com gerenciamento seguro de repositórios

---

## 👥 Estados de Usuário & Camada de Autorização
1. **Pending**: Conta identificada aguardando autorização do administrador.
2. **Approved / Active**: Acesso liberado aos recursos contratados.
3. **Suspended**: Temporariamente suspenso pelo administrador.
4. **Blocked**: Bloqueado por conformidade.
5. **Rejected**: Não autorizado.

---

## 💳 Sistema de Planos & Preços (MZN)
- **Starter Grátis**: 1 projeto ativo, 5 gerações com IA por mês.
- **PRO MENSAL**: **150 MZN/mês** — Projetos ilimitados, 150 gerações/mês, GitHub push, PWA, SEO & Copy AI.
- **PRO TRIMESTRAL (Melhor Custo-Benefício)**: **300 MZN/trimestre** (equivale a 100 MZN/mês) — 350 gerações/trimestre, prioridade na fila de build, suporte prioritário.

---

## 🛠️ Execução Local

```bash
# 1. Instalar dependências
npm install

# 2. Iniciar servidor Full-Stack (porta 3000)
npm run dev

# 3. Compilar para produção
npm run build

# 4. Iniciar em produção
npm start
```

---

## 🔐 Variáveis de Ambiente (`.env.example`)

```env
GEMINI_API_KEY="SUA_CHAVE_GEMINI_AQUI"
APP_URL="http://localhost:3000"
NEXORA_SUPERADMIN_EMAIL="tecnofaustino@gmail.com"
GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""
PAYMENT_WEBHOOK_SECRET=""
```

---

## ⚖️ Licença
Distribuído sob a licença Apache-2.0.

**NEXORA** — Crie. Publique. Evolua.
