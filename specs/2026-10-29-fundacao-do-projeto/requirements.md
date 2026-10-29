# Requisitos: Fundação do projeto

## Contexto

A F01 do [roadmap](../roadmap.md) prevê definir requisitos e fontes de conteúdo e preparar frontend, API e banco de dados. A missão é oferecer um site institucional atraente, confiável e responsivo, com catálogo de cursos e notícias gerenciadas por usuários autorizados.

## Escopo

- Preparar uma aplicação frontend React com Vite.
- Preparar uma API separada em Node.js com Express.
- Usar TypeScript no frontend e no backend.
- Estabelecer comunicação REST com respostas JSON.
- Configurar SQLite para a persistência inicial.
- Permitir iniciar os serviços localmente por comandos documentados.
- Validar que frontend, API e conexão com SQLite estão operacionais.

## Fora de escopo

- Construir páginas completas do catálogo ou matrizes curriculares.
- Implementar autenticação ou cadastro e publicação de notícias.
- Definir o conteúdo final dos cursos.

## Decisões

- Seguir a stack registrada em [tech-stack.md](../tech-stack.md): TypeScript, React/Vite, Node.js/Express, API REST e SQLite.
- Manter frontend, API e persistência separados para permitir evolução independente.
- Não acrescentar escolhas de ORM, biblioteca de testes ou ferramenta de lint nesta especificação.

## Critério de aceite

O frontend e a API iniciam localmente, a API consegue validar a conexão SQLite e os comandos necessários estão documentados. Os resultados devem ser registrados em `validation.md` antes do merge.