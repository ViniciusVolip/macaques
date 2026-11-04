# Macaquês

**Macaco vê, macaco fala.** App de estudos com o Volipe, o macaco de três olhos.

Abra no celular: **https://viniciusvolip.github.io/macaques/**
No Chrome do Android, toque em ⋮ e depois em **Instalar app**.

## O que tem

- **Idiomas:** inglês, espanhol, francês e mandarim, com exercícios de montar frases, escrever, ouvir e ligar pares, além da unidade "Minhas aulas".
- **Matemática para o Enem**, **Programação (Python)**, **Dados** e **IA e prompts**.
- **Xadrez:** exercícios, partidas contra o Volipe em três níveis e quebra-cabeças com rating (mate em 1 e em 2, mais o modo Relâmpago de 3 minutos).
- **Flashcards** com repetição espaçada.
- **Inglês B1 e B2:** 9 unidades novas (expressões do dia a dia, should have, present perfect, direções, phrasal verbs, narrativa, condições, opiniões e trabalho avançado), com selo de nível. As unidades A1 e A2 continuam no fim da trilha para revisão.
- XP, sequência de dias e revisão de erros. Sem vidas: errar só significa que a questão volta no fim da lição.
- Funciona offline depois de aberto uma vez.

A conversa com o Volipe e o "Explicar meu erro" usam o Claude da conta de quem estuda, então funcionam na versão aberta pelo claude.ai.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | O app inteiro |
| `manifest.webmanifest`, `icons/` | Instalação no celular e ícone do Volipe |
| `sw.js` | Funcionamento offline, limitado ao endereço `/macaques/` |
| `chess.js` | Regras do xadrez ([chess.js](https://github.com/jhlywa/chess.js), licença BSD em `chess.js.LICENSE`) |

O progresso fica salvo só no navegador do aparelho. Para levar o progresso para outro aparelho, use Ajustes → "Copiar meu progresso".
- Caderno de palavras (com sorteio de palavra nova no inglês, vira flashcards e aula) e Aula Música: você cola a letra e a tradução, o app cria a aula. Tudo fica só no aparelho.
