# Practical Assignments - Cryptographic Structures - 2022/2023
## Msc in Software Engineering - Cryptography and Information Security Specialization Profile

### TP1:

### TP2:
1.Construir uma classe Python que implemente um KEM - ElGamal. 

  1. Inicializar cada instância recebendo  o parâmetro de segurança (tamanho em bits da ordem do grupo cíclico) e gere as chaves pública e privada.
  2. Conter funções para encapsulamento e revelação da chave gerada.
  3. Construir,  a partir deste KEM e usando a transformação de Fujisaki-Okamoto, um PKE que seja IND-CCA seguro.


2. Construir uma classe Python que implemente o  EdCDSA a partir do “standard” FIPS186-5
    1. A implementação deve conter funções para assinar digitalmente e verificar a assinatura.
    2. A implementação da classe deve usar  uma das “Twisted Edwards Curves” definidas no standard e escolhida  na iniciação da classe: a curva  “edwards25519” ou “edwards448”.
    3. Por aplicação da transformação de Fiat-Shamir construa um protocolo de autenticação de desafio-resposta
   
### TP3:

### TP4:
Neste trabalho pretende-se implementar em Sagemath de algumas dos candidatos a “standartização” ao concurso NIST Post-Quantum Cryptography na categoria de esquemas de assinatura digital. Ver também a directoria com a documentação. Construa

1. Um protótipo Sagemath do algoritmo   Dilithium ,
2. Um protótipo Sagemath do algoritmo   Sphincs+.

TO-DO: Add detailed description and sections for each project.

## Group members:

- [Rodrigo Rodrigues](https://www.github.com/webst2r)  
- [Rui Guilherme Monteiro](https://www.github.com/rushmetra)  

## Final grade: 16/20
