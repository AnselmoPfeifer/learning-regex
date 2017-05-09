# learning-regex

- . o "ponto" que significa qualquer char
- * o asterisco que serve para definir uma quantidade de chars, zero ou mais
- a {3} letra a 3 vezes.
- \d* um digito zero ou mais vezes
- \d{3}\.\d{3}.\d{3}-\d{2} - Buscar um CPNJ 222.345.567-00
- \d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3} - Buscar um endereco IP ex: 126.10.112.34
- \d{5}-\d{3} - Buscar um CEP
- \(\d{2}\) \d{4}-\d{4} - Buscar numero de telefone
