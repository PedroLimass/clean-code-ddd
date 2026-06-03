# clean-code-ddd

Projeto de estudo sobre **Domain-Driven Design (DDD)** e **Clean Code** com TypeScript.

## Sobre

Modela um domínio simples de perguntas e respostas (estilo fórum), aplicando conceitos de DDD: entidades, repositórios e casos de uso bem separados.

## Tecnologias

- [TypeScript](https://www.typescriptlang.org/)
- [Vitest](https://vitest.dev/) — testes
- [tsup](https://tsup.egoist.dev/) — build
- [tsx](https://github.com/privatenumber/tsx) — execução

## Estrutura

```
src/
└── domain/
    ├── entities/        # Entidades do domínio (Answer, Question, Instructor, Student)
    ├── repositories/    # Contratos de persistência (interfaces)
    └── use-case/        # Casos de uso da aplicação
```

## Como rodar

Instale as dependências:

```bash
npm install
```

Rode os testes:

```bash
npm test
```

Ou em modo watch:

```bash
npm run test:watch
```
