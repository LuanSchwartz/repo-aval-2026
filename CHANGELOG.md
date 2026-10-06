# Changelog

Todas as mudanças relevantes deste projeto são documentadas neste arquivo.

O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/)
e o projeto adota o [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [1.1.0] - 2026-10-06

### Adicionado

- Testes para validação de notas inválidas.
- Formatação da média com uma casa decimal e separador decimal por vírgula.
- Classificação como Aprovado com distinção para médias a partir de 9,0.

### Alterado

- Cálculo da média reescrito sem utilização de laço `for`.
- Média igual a 7,0 passou a ser considerada Aprovado.

### Corrigido

- Correção da classificação de médias exatamente iguais a 7,0.

## [1.0.0] - 2026-09-14