# learning-regex

## Exemplos de Regex
    - * o asterisco que serve para definir uma quantidade de chars, zero ou mais
    - a {3} letra a 3 vezes.
    - \d* um digito zero ou mais vezes

## Para buscar CPF
    - \d{3}\.\d{3}.\d{3}-\d{2} - ex: 151.150.419-60
    - \d{3}\.?\d{3}.?\d{3}-?\d{2} - ex: 15115041960
    - \d{3}\.?\d{3}.?\d{3}[-.]?\d{2} - ex: 151.150.419.60

## Para buscar IPv4, CEP e Telefone
    - \d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3} - Ex: 126.10.112.34
    - \d{5}-\d{3} - 89098-406
    - \(\d{2}\) \d{4}-\d{4} - (67) 6544-6543
