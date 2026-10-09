# My Daily Habits

Projeto desenvolvido no Módulo 04 - Desenvolvimento Front-end com React.

## Requisitos
- Node.js compatível com a versão atual do Vite
- npm

## Como executar
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Funcionalidades (Checkpoint Aula 4)
- Listagem dinâmica de hábitos a partir de dados estruturados com `map()` e `key`.
- Componentização desacoplada com `HabitCard`, `HabitList` e `Panel` (utilizando a prop `children`).
- Gerenciamento de estado com o Hook `useState` no componente `App`.
- Atualização imutável do estado ao alternar a conclusão de um hábito (`handleToggleHabit`).
- Contagem dinâmica de hábitos concluídos como dado derivado, evitando inconsistências.
