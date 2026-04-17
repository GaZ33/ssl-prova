# Explicação do csr
O CSR (Certificate Signing Request) é um pedido de assinatura de certificado.
É um formulário que você preenche para provar quem é você.
O arquivo CSR contém:
- Nome do dominio
- dados da organização
- Sua chave pública
- Assinatura digital

## Explicação do comando utilizado
O comando `openssl req -new -key aluno.key -out aluno.csr` inicia o processo de identificação.
Ao executar ele, algumas perguntas no terminal irão surgir