# Explicação
O comando `openssl x509 -req -days 365 -in aluno.csr -signkey aluno.key -out aluno.crt` serve para criar um certificado autoassinado.
Esse comando usa a chave privada que criamos para assinar e validar sua identidade.