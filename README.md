# Jogo da Forca em Java

> Jogo da forca para terminal com banco de palavras de times de futebol.

![status](https://img.shields.io/badge/status-concluído-success) ![java](https://img.shields.io/badge/Java-8-blue)

## Sobre
Exercício de introdução à programação orientada a objetos (2016). O jogador tenta descobrir uma palavra sorteada, letra a letra, com limite de erros.

## Estrutura de pastas
```text
IniciarJogo.java   laço de interação com o jogador
Logica.java        palavra sorteada, máscara com "#", palpites e contagem de erros
Repositorio.java   banco de palavras e histórico de palpites
```

## Como executar
```bash
mkdir -p bin && javac -d bin *.java && java -cp bin jogoforca.IniciarJogo
```

## Status
Concluído. Exercício; não recebe manutenção.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
