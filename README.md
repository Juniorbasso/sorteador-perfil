# Baralho Perfil

Baralho online para jogar Perfil. As cartas são embaralhadas a cada rodada, exibidas uma por vez e podem ser usadas sem instalar nada.

## Como jogar

1. Abra [o baralho online](https://juniorbasso.github.io/sorteador-perfil/) ou abra `index.html` no navegador.
2. Selecione **Embaralhar e começar**.
3. Leia as dicas em sequência e use **Revelar** quando quiser mostrar a resposta.
4. Selecione **Próxima carta** para continuar. Ao terminar o baralho, uma nova rodada é embaralhada.

## Atualizar as cartas

Edite `cartas.js), mantendo a variável `baralho` e o formato abaixo. Cada dica deve ser um texto; a interface verifica os campos antes de exibir o baralho.

```js
const baralho = [
  {
    categoria: "LUGAR",
    resposta: "EXEMPLO",
    dicas: [
      "Primeira dica.",
      "Segunda dica."
    ]
  }
];
```

Não é necessário alterar `index.html` para adicionar cartas. Use textos simples nos campos; eles são exibidos como texto e não como HTML.

## Arquivos

- `index.html`: interface, estilos responsivos e lógica para embaralhar, navegar, revelar e validar cartas.
- `cartas.js`: conteúdo editável do baralho.

O projeto é estático e não depende de servidor ou bibliotecas externas. Para testar localmente, abra `index.html` em um navegador moderno.

## Acessibilidade

A interface pode ser operada por teclado, indica o estado da resposta e anuncia mensagens de status. O layout se adapta a telas pequenas e respeita a preferência por movimento reduzido.

## Licença

Consulte o arquivo de licença do repositório, se aplicável. O nome Perfil e seus elementos associados pertencem aos respectivos titulares.
