# Guia Básico de Marcação Markdown
Este guia oferece um passo a passo detalhado sobre como utilizar  a marcação Markdown para formatação de texto em documento. Iniciando desde os conceitos básicos, como títulos e parágrafos, até tópicos mais avançados, como tabelas, notas de rodapé e alertas. Cada tópico é acpmpanhado por uma descrição simples e exemplos práticos em Markdown, permitindo que os usuários aprendam e apliquem rapidadente a marcação Markdown em seus própios documentos.

## Títulos
São usados para criar diferentes níveis de Títulos em um documento Markdown.

Exemplo:
# Título 1
## Título 2
### Título 3

## Parágrafos 
Simplismente escreva seu texto como parágrafos normais. Não é necessáriamente nenhum tipo de marcação adicional.

Exemplo:
Aqui eu tenho um parágrafo

## Listas
permitem criar listas ordenadas ou não ordenadas.

Exemplo:
Lista não ordenada: 

* Item 1
* Item 2
* Item 3

  Lista ordenada:
  
1. Primeiro item
2. Segundo item
3. Terceiro item 
  
## Links
Criam links para outras páginas da web.

Exemplos: 

[Texto do link](URL) para criar um link.

## Imagems
Insira imagens em um documento Markdown.

Exemplo:

![Imagem](URL_da_imagem)

## Ênfase
Permitem enfatizar texto, como itálico, negrito, tachado,subscrito e sobrescrito.

Exemplo:

*texto em iálico* ou _texto em negrito_ para negrito.

~~Texto em tachado~~

Aqui é um texto <sub> subscrito </sub>

Aqui é um texto <sup> sobrescrito </sup>

## Citações em bloco
São usadas para destacar uma citação ou bloco de texto.

Exemplo:

> Isso é uma sitação de bloco.

## Linhas hirizontais
São usadas para criar uma linha horizontal para separar seções do documento.

---

## Código 
Permitem inserir blocos de código ou destacar código dentro do texto.

Exemplo:

Use crases (\`) para inserir código `inline`.

```
idade = 17
print(f"A idade é {idade}")
```
## Tabelas
Criem tabelas organizadas em colunas e linhas 

Exemplo:

| Cabeçalho 1 | Cabeçalho 2 |
|-------------|-------------|
| Dado 1      | Dado 2      |
| Dado 3      | Dado 4      |

## Listas de tarefas
Criem listas de tarefas que podem ser marcados como concluídas ou pendentes.

Exemplo:

- [x] Tarefas concluída
- [ ] Tarefas pendente

## Referências
Permitem adicionar notas de rodapé para fornecer mais informações sobre o conteúdo do documento.

Exemplo:

Aqui é um exemplo de marcação em rodapé[^1]

a aula é como o Ricardo[^2]

[^1]: Rodapé: conteúdo inferior do documento.
[^2]: Ricardo: Professor da turma de git.

## Notas de rodapé
Permitem adicionar notas de rodapé para fornecer mais informações sobre o conteúdo do documento.

Exemplo:

Aqui é um exemplo de marcação em rodapé[^1]

a aula é como o Ricardo[^2]

[^1]: Rodapé: conteúdo inferior do documento.
[^2]: Ricardo: Professor da turma de git.

## Alertas
São usados para destacar informações importantes, como notas, avisos ou mensagens.

Exemplo:

> **Note**
> Esta é uma Nota

> [!NOTE]
> Destaca informações que os usuários devem levar em consideração, mesmo durante a leitura superficial.

> [!IMPORTANT]
> Informações cruciais necessárias para o sucesso dos usuáarios.

> [!WARNING]
> Conteúdo crítico que exige atenção imediata do usuário devido a riscos potencias.
