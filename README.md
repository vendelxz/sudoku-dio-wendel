# Projeto Sudoku - Santander Bootcamp 2025 (DIO)

Este projeto é um jogo de Sudoku implementado em Java, desenvolvido durante o Santander Bootcamp 2025 em parceria com a DIO.

## Melhorias Implementadas

- **Organização do código:** Separação clara entre `model` (regras e estrutura do jogo) e `util` (template do tabuleiro).
- **Validação robusta de entrada:** Implementação de métodos para garantir que as entradas do usuário estejam dentro dos limites esperados (colunas, linhas e valores).
- **Controle do estado do jogo:** Melhor tratamento do status do jogo (não iniciado, incompleto, completo) e detecção de erros no tabuleiro.
- **Proteção de valores fixos:** Espaços fixos não podem ser alterados pelo usuário, evitando inconsistências.
- **Interface de texto clara:** Uso de um template para exibir o tabuleiro no terminal de forma organizada e visualmente agradável.
- **Fluxo de jogo interativo:** Menu com opções para iniciar, modificar, visualizar e finalizar o jogo.
- **Uso correto dos argumentos de linha de comando:** Parsing estruturado para carregar o tabuleiro inicial a partir dos argumentos.

## Como rodar

- Compilar o código Java com os pacotes organizados.
- Passar os argumentos no formato `"coluna,linha;valor,fixed"` protegidos por aspas (especialmente no PowerShell).
- Executar a classe principal `br.com.dio.Main`.

## Autor

José Wendel

---

**Santander Bootcamp 2025 em parceria com a DIO**

