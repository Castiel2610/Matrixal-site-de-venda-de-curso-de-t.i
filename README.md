# Matrixal — Plataforma de Cursos de T.I.

Landing page e plataforma completa de cursos de tecnologia da informação, com sistema de autenticação, dashboard de alunos e área de conteúdo exclusivo.

## Visão geral

Projeto desenvolvido como freelancer para a **Matrixal**, plataforma de cursos profissionais de T.I. A aplicação conta com página de vendas, sistema de login/cadastro, dashboard do aluno e área de conteúdo com materiais exclusivos.

## Funcionalidades

- **Landing page de vendas** — apresentação do produto com CTA e seções de conversão
- **Autenticação completa** — login, cadastro, recuperação e redefinição de senha
- **Dashboard do aluno** — área logada com acesso ao conteúdo
- **Área de conteúdo** — módulos e materiais em PDF por nível de plano
- **Sistema de upgrade** — fluxo de upgrade de plano dentro da plataforma
- **Perfil do usuário** — edição de nome e foto de perfil (integração com AWS S3)
- **Chatbot de suporte** — widget integrado na plataforma

## Stack

| Tecnologia | Uso |
|---|---|
| Next.js 14 | Framework principal (App Router) |
| TypeScript | Tipagem estática |
| Tailwind CSS | Estilização |
| shadcn/ui | Componentes de UI |
| NextAuth.js | Autenticação |
| Prisma | ORM / banco de dados |
| AWS S3 | Upload de arquivos |

## Estrutura do projeto

```
nextjs_space/
├── app/                  # Rotas e páginas (App Router)
│   ├── api/              # Endpoints da API
│   ├── dashboard/        # Área logada do aluno
│   ├── vendas/           # Página de vendas
│   ├── login/            # Autenticação
│   └── registro/         # Cadastro
├── components/           # Componentes da aplicação
│   └── ui/               # Componentes base (shadcn/ui)
├── lib/                  # Utilitários e configurações
│   └── pdf-contents/     # Conteúdo dos módulos
├── prisma/               # Schema do banco de dados
└── public/               # Assets estáticos
```

## Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/seuperfil/matrixal-cursos-ti
cd matrixal-cursos-ti/nextjs_space

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env
# Preencha as variáveis necessárias no arquivo .env

# Execute o projeto
npm run dev
```

Acesse `http://localhost:3000`.

## Desenvolvido por

**José Renato** — Desenvolvedor Front-end Freelancer  
📧 joserenatosantosxavier22@gmail.com  
💼 [linkedin.com/in/seuperfil](https://linkedin.com/in/seuperfil)
