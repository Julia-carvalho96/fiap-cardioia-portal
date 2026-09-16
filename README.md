# CardioIA Portal — Grupo Aura

Portal responsivo desenvolvido em **React + Vite** para o desafio **Ir Além 1** da Fase 2 do projeto CardioIA — FIAP.

> Todos os pacientes e agendamentos são fictícios. O projeto é exclusivamente educacional, não realiza diagnóstico e não deve ser usado em decisões clínicas.

## Funcionalidades

- autenticação simulada via Context API;
- JWT fictício salvo no `localStorage`;
- proteção de rotas;
- dashboard de pacientes, consultas e prioridades;
- listagem consumida de JSON local por uma camada de serviço;
- busca de pacientes;
- agendamento com `useState` e `useReducer`;
- inclusão, persistência e remoção de consultas simuladas;
- layout responsivo com CSS Modules.

## Tecnologias

- React;
- Vite;
- React Router;
- Context API;
- Vitest;
- Testing Library;
- CSS Modules.

## Estrutura

```text
src/
├── components/
├── contexts/
├── pages/
├── services/
└── styles/
```

## Executar localmente

Pré-requisito: Node.js `22.13` ou superior, ou Node.js `24`.

```bash
npm install
npm run dev
```

Acesse o endereço indicado pelo Vite, normalmente `http://localhost:5173`.

## Testes e build

```bash
npm test -- --run
npm run build
```

O workflow do GitHub Actions executa automaticamente os testes e a build em cada atualização da branch principal.

## Credenciais de demonstração

As credenciais são inteiramente fictícias e aparecem preenchidas na própria tela de login. Não reutilize credenciais reais neste protótipo.

## Integrantes

- **Nome completo — RM:** preencher antes da entrega.

## Vídeo de demonstração

- **YouTube (não listado, até 4 minutos):** adicionar o link antes da entrega.

## Origem

O portal integra a Fase 2 do projeto principal [CardioIA](https://github.com/murilosalla-blip/fiap-ano02-fase01-cap01-cardioia), desenvolvido de forma independente das modalidades textual, tabular e visual.
