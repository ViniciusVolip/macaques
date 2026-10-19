# Macaquês

**Macaco vê, macaco fala.** App de estudos com o Volipe, o macaco de três olhos.

Abra no celular: **https://viniciusvolip.github.io/macaques/**
No Chrome do Android, toque em ⋮ e depois em **Instalar app**.

## O que tem

- **Idiomas:** inglês, espanhol, francês e mandarim, com exercícios de montar frases, escrever, ouvir e ligar pares, além da unidade "Minhas aulas".
- **Matemática para o Enem**, **Programação (Python)**, **Dados** e **IA e prompts**.
- **Xadrez:** exercícios e partidas contra o Volipe em três níveis.
- **Flashcards** com repetição espaçada.
- XP, sequência de dias, vidas e revisão de erros.
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
