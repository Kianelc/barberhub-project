# Barber Hub

## Descrição

O **Barber Hub** é uma aplicação full stack desenvolvida para conectar clientes com as melhores barbearias da região, oferecendo uma experiência intuitiva e completa para encontrar, avaliar e agendar serviços de barbearia. O sistema é projetado para fornecer uma interface amigável e funcionalidades robustas tanto para os clientes quanto para as barbearias.

## Tecnologias Utilizadas

- **Next.js**: Framework para desenvolvimento de aplicações React com renderização do lado do servidor.
- **React.js**: Biblioteca para construção de interfaces de usuário.
- **PostgreSQL**: Sistema de gerenciamento de banco de dados relacional.
- **Tailwind CSS**: Framework para estilização de interfaces com classes utilitárias.
- **Prisma**: ORM (Object-Relational Mapper) para trabalhar com bancos de dados SQL.
- **Node.js**: Ambiente de execução para JavaScript no lado do servidor.
- **ShadCN**: Biblioteca para componentes de interface.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **JavaScript**: Linguagem de programação principal para o desenvolvimento da aplicação.

## Cronograma

**05/08 a 12/08**

- **Aula 0**: Setup e apresentação do projeto
- **Aula 1**: Tela inicial
- **Aula 2**: Detalhes da barbearia
- **Aula 3**: Login com o Google
- **Aula 4**: Reserva de um barbeiro
- **Aula 5**: Tela de agendamentos
- **Aula 6**: Deploy e revisão do projeto

## Funcionalidades

- **Tela Inicial**: Visão geral das barbearias disponíveis, com opções para buscar e filtrar.
- **Detalhes da Barbearia**: Informações detalhadas sobre cada barbearia, incluindo serviços, avaliações e localização.
- **Login com Google**: Integração com o Google para autenticação de usuários.
- **Reserva de um Barbeiro**: Funcionalidade para agendar serviços com uma barbearia específica.
- **Tela de Agendamentos**: Visualização sobre a baerbearia e reserva de serviços.

## Instalação e Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/Kianelc/barberhub-project.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd barber-hub
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Configure as variáveis de ambiente:
   - Crie um arquivo `.env` na raiz do projeto e adicione suas variáveis de ambiente (consulte o arquivo `.env.example` para mais detalhes).
5. Inicialize o banco de dados:
   ```bash
   npx prisma migrate dev
   ```
6. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```
