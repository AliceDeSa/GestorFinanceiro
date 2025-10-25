# Gestor Financeiro - Astral Money Coach

Um aplicativo completo de gestão financeira pessoal construído com React, TypeScript e Supabase.

## 🚀 Funcionalidades

- **Autenticação**: Login/Cadastro com email/senha e Google OAuth
- **Dashboard**: Visão geral das finanças com gráficos interativos
- **Rendas**: Gestão de fontes de renda com diferentes frequências
- **Gastos**: Controle de despesas com categorização e parcelamento
- **Metas Financeiras**: Distribuição inteligente da renda
- **Educação Financeira**: Módulos educativos com quiz
- **Calculadora**: Juros compostos com gráficos

## 🛠️ Tecnologias

- **Frontend**: React 18 + TypeScript + Vite
- **UI**: shadcn/ui + Tailwind CSS
- **Backend**: Supabase (PostgreSQL + Auth)
- **Gráficos**: Recharts
- **Roteamento**: React Router DOM

## 📦 Instalação

1. **Clone o repositório**
```bash
git clone <seu-repositorio>
cd astral-money-coach
```

2. **Instale as dependências**
```bash
npm install
```

3. **Configure as variáveis de ambiente**
Crie um arquivo `.env.local` na raiz do projeto:
```env
VITE_SUPABASE_URL=sua_url_do_supabase
VITE_SUPABASE_PUBLISHABLE_KEY=sua_chave_publica_do_supabase
```

4. **Inicie o servidor de desenvolvimento**
```bash
npm run dev
```

## 🗄️ Configuração do Banco de Dados

O projeto usa Supabase. Certifique-se de ter as seguintes tabelas:

- `profiles` - Perfis dos usuários
- `incomes` - Rendas
- `expenses` - Gastos
- `cards` - Cartões de crédito
- `financial_goals` - Metas financeiras
- `education_progress` - Progresso educacional

## 🚀 Deploy

Para fazer deploy:

```bash
npm run build
```

Os arquivos serão gerados na pasta `dist/`.

## 📱 Scripts Disponíveis

- `npm run dev` - Servidor de desenvolvimento
- `npm run build` - Build para produção
- `npm run preview` - Preview do build
- `npm run lint` - Verificar código

## 🔧 Solução de Problemas

### Erro MIME Type
Se encontrar erro de MIME type, execute:
```bash
rm -rf node_modules .vite dist package-lock.json
npm install
npm run dev
```

### Problemas de Dependências
```bash
npm audit fix
npm update
```

## 📄 Licença

Este projeto é privado e proprietário.
