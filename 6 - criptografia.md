# Entendendo a criptografia
## O que é?

Criptografia é a **arte de proteger informações** transformando dados legíveis (texto claro) em um formato incompreensível (texto cifrado), para que apenas pessoas autorizadas possam entender.

## Para que serve?

Ela serve para garantir a **segurança da informação**, com foco em 4 objetivos principais:

* **Confidencialidade:** somente quem tem a chave certa pode ler os dados.
* **Integridade:** garante que os dados não foram alterados.
* **Autenticidade:** confirma a identidade do remetente.
* **Não repúdio:** impede que alguém negue que enviou uma informação.

## Quando usar?

Você deve usar criptografia sempre que precisar proteger dados, como:

* Enviar e-mails confidenciais
* Armazenar senhas em bancos de dados
* Proteger transações bancárias e compras online
* Em aplicativos de mensagens (como WhatsApp)
* Ao acessar sites com HTTPS

## Tipos de Criptografia

Existem dois tipos principais:

#### Criptografia Simétrica

* Usa **uma única chave** para **criptografar e descriptografar**.
* A chave precisa ser compartilhada com quem vai receber os dados.
* Rápida, mas exige cuidado com o envio da chave.
* **Exemplo:** AES, DES

#### Criptografia Assimétrica

* Usa **duas chaves diferentes**, chamadas:

  * **Chave pública**: para criptografar
  * **Chave privada**: para descriptografar
* Mais segura para comunicação entre desconhecidos.
* **Exemplo:** RSA, ECC


### Conceitos de Chave Simétrica vs Assimétrica

| Conceito                    | Chave Simétrica          | Chave Assimétrica              |
| --------------------------- | ------------------------ | ------------------------------ |
| Número de chaves            | 1                        | 2 (pública e privada)          |
| Velocidade                  | Mais rápida              | Mais lenta                     |
| Segurança na troca de chave | Menor                    | Maior                          |
| Exemplos de uso             | Criptografia de arquivos | Comunicação segura na internet |


### Principais Algoritmos de Criptografia

#### Criptografia Simétrica

* **AES (Advanced Encryption Standard):** Padrão moderno, muito seguro.
* **DES (Data Encryption Standard):** Mais antigo, hoje considerado inseguro.
* **3DES (Triple DES):** Mais seguro que o DES, mas mais lento.

#### Criptografia Assimétrica

* **RSA (Rivest-Shamir-Adleman):** Um dos mais usados no mundo.
* **ECC (Elliptic Curve Cryptography):** Usa curvas elípticas, mais eficiente.
* **DSA (Digital Signature Algorithm):** Foco em assinaturas digitais.

## Resumo

* **Criptografia:** proteção de dados com codificação.
* **Serve para:** garantir segurança, autenticidade e privacidade.
* **Quando usar:** sempre que quiser proteger dados.
* **Tipos:** Simétrica (1 chave) e Assimétrica (2 chaves).
* **Principais algoritmos:** AES, RSA, ECC, DES, 3DES, DSA.

