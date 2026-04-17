# Explicação sobre chave privada

O conceito de chave privada é fundamental na criptografia assimétrica.
A chave assimétrica é uma das chaves do par de chaves (pública e privada) que devemos manter em segredo. Ela é a única que consegue descriptografar o conteúdo que foi criptografado pela chave pública correspondente.

## Explicação do comando utilizado
O comando `sudo openssl genrsa -out aluno.key 2048` é utilizado para criar esse par de chaves.