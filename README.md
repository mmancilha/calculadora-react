# Calculadora — React Fundamentals

Projeto de estudo baseado no layout da calculadora com histórico de operações. O objetivo é praticar React, JSX e Tailwind no ambiente mais simples possível, mantendo um registro versionado do avanço.

## Visão geral
- **Calculadora** em painel escuro com teclas destacadas e acento roxo.
- **Histórico de operações** em painel separado para mostrar cálculos anteriores.
- **Estética**: fundo roxo suave, cartões com sombras e bordas arredondadas.

## Referência visual
- Figma: https://www.figma.com/design/8gktXHNqxkLJUNvWV0aMc3/Calculadora?node-id=3-376&m=dev&t=99omzl6vVxHKtDId-1

## Paleta e tokens (definidos no HTML)
- `--text`: #ebebeb
- `--text-secondary`: #6b6b6b
- `--primary`: #462878
- `--background`: #2d2a37
- `--gradient`: 180deg, rgba(0, 0, 0, 0.05) → rgba(255, 255, 255, 0.05)
- `--gradient-hover`: 180deg, rgba(0, 0, 0, 0.1) → rgba(255, 255, 255, 0.1)
- `--shadow`: combinação de múltiplos níveis de sombra
- `--font-sans`: "Rubik", sans-serif

## Componentes visuais (layout do mock)
- **Display** com expressão atual e resultado em destaque.
- **Teclas numéricas** em blocos arredondados com sombra suave.
- **Operadores** com acento roxo para diferenciar ações principais.
- **Histórico** com título e lista de operações.

## Objetivo deste repositório
Acompanhar o progresso do aprendizado. O arquivo versionado é:
- `calculadora.html`

## Como visualizar
Use o Live Server no Cursor e abra o arquivo `calculadora.html`.

## Próximos passos (ideias)
- Construir layout completo do teclado.
- Implementar estado de display e histórico.
- Adicionar estados de hover/active e acessibilidade.
