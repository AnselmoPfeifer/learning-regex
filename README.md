# learning-regex

## Exemplos de Regex
    - * o asterisco que serve para definir uma quantidade de chars, zero ou mais
    - a {3} letra a 3 vezes.
    - \d* um digito zero ou mais vezes
    - [0-9] todos os numeros
    - [a-z] - Todos as caracteres minusculos
    - [A-Z] - Todos os caractres Maiusculos
    - [A-Za-z] significa A-Z ou a-z.

## Para buscar CPF
    - \d{3}\.\d{3}.\d{3}-\d{2} - ex: 151.150.419-60
    - \d{3}\.?\d{3}.?\d{3}-?\d{2} - ex: 15115041960
    - \d{3}\.?\d{3}.?\d{3}[-.]?\d{2} - ex: 151.150.419.60

## Para buscar IPv4, CEP e Telefone
    - \d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3} - Ex: 126.10.112.34
    - \d{5}-\d{3} - 89098-406
    - \(\d{2}\) \d{4}-\d{4} - (67) 6544-6543

## Datas e Hora
    - [1-3]?\d\s+de\s+[A-Z][a-zç]{1,8}\s+de\s+[12]\d{3} - Ex: 28 de Dexembro 2017
    - \d{2}h\d{2}min\d{2}s - Ex: 19h32min16s
    - [1-9]{2}:[1-9]{2}:[1-9]{2} - Ex: 19:32:12

## Sobre os quantifier
    - ? - zero ou uma vez.
    - * - zero ou mais vezes.
    - + - uma ou mais vezes.
    - {n} - exatamente n vezes.
    - {n,} - no mínimo n vezes.
    - {n,m} - no mínimo n vezes, no máximo m vezes.