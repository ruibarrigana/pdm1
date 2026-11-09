# Projeto de aulas — documento integrado

## Estrutura

```text
projeto_aulas_completo/
├── main.tex
├── config.tex
├── Aula1/
│   ├── planificacao.tex
│   └── enunciado.tex
└── Aula2/
    ├── planificacao.tex
    └── enunciado.tex
```

## Compilar

Compile `main.tex` (por exemplo, no Overleaf). Este ficheiro reúne, pela ordem,
as duas aulas, incluindo a planificação e o enunciado de cada uma.

`config.tex` contém o preâmbulo e os comandos comuns. Os ficheiros dentro de
`Aula1/` e `Aula2/` são fragmentos incluídos pelo documento principal; não devem
ser compilados isoladamente.

O conteúdo do enunciado original da Aula 1 foi mantido. Apenas o preâmbulo e
os delimitadores do documento foram deslocados para `config.tex` e `main.tex`,
respetivamente, para permitir a inclusão no documento integrado.

Os campos de planificação e o enunciado da Aula 2 são estruturas iniciais
a preencher.
