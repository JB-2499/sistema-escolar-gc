# sistema-escolar-gc

Projeto em grupo para praticar **HTML e Bootstrap**. É um sistema de gestão escolar com três áreas (Aluno, Professor e Sala), cada uma com as telas de um CRUD.

O projeto usa apenas classes do Bootstrap 5.3.3, carregado por CDN. Não há CSS nem JavaScript próprio, nem backend: os formulários não salvam dados, e as telas de consulta, alteração e exclusão mostram informações de exemplo.

## Estrutura

```
sistema-escolar-gc/
├── index.html                  # página inicial com o menu
├── sala/
│   ├── inserir-sala.html
│   ├── procurar-sala.html
│   ├── alterar-sala.html
│   └── excluir-sala.html
├── .github/workflows/pages.yml # publicação no GitHub Pages
└── .gitignore
```

As páginas de Aluno e Professor ficam com os outros integrantes do grupo.

## Fluxo de cada área

O menu da página inicial tem dois itens por área: **Cadastrar** e **Consultar**.

1. **Cadastrar**: formulário de cadastro.
2. **Consultar**: lista os registros, e cada linha tem os botões **Alterar** e **Excluir**.
3. **Alterar** e **Excluir**: abertos a partir da lista.

## Branches

- `main`: versão final, publicada no GitHub Pages a cada push.
- `desenvolvimento`: integração do trabalho de todos.
- `<nome>/<feature>`: uma branch por integrante, para a sua área.

## Integrantes

- João Barreto: Sala
- Felipe Feliciano Lopes: Professor
- Lucas: Aluno
