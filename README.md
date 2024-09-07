# Apresentação: MIMD - Múltiplos Fluxos de Instruções-Múltiplos Fluxos de Dados - SEL0631

Essa apresentação foi elaborada como atividade avaliativa para a disciplina SEL0631 - Processadores Digitais de Sinais e Aplicações, ministrada no segundo semestre de 2024 pelo professor doutor Maximiliam Luppe.

|**Data**  |**Título**                                                      |
|----------|----------------------------------------------------------------|
|08/24/2024| MIMD - Múltiplos Fluxos de Instruções-Múltiplos Fluxos de Dados|
-----------------------------------------------------------------------------

## Banner/Poster
Está disponível em [`main.pdf`](https://github.com/CarlosCraveiro/PDSA_Presentation/blob/main/main.pdf).

## Template utilizado

O template utilizado `poster.typ` foi retirado do repositório [typst-poster](https://github.com/pncnmnp/typst-poster/tree/master), com apenas algumas poucas adaptações.

## Compilar a apresentação

Baixe as dependências você mesmo, basicamente o `typst` e um visualizador de pdf.

Ou use `nix` para gerenciar as dependências para você: 
```bash
nix --experimental-features 'nix-command flakes'
nix develop -c $SHELL
```

Então, só compilar com:
```bash
typst compile main.typ
```

Agora você deve ter um `main.pdf` para olhar!

## Autores

| Estudante                             |  Nº USP  |
|---------------------------------------|--------- |
| Carlos Henrique Craveiro Aquino Veras | 12547187 |
| Pedro Oliveira Torrente               | 11798853 |

## Licensa
Este trabalho está sob a licensa **Creative Commons Attribution-ShareAlike 4.0 International**, o que inclui as imagens indicadas como autorais.
