# AWS S3 Encryption Lab

## Sobre o laboratório

Laboratório prático utilizando Amazon S3 com foco em criptografia server-side e proteção de objetos armazenados em buckets S3.

---

# Objetivo

Explorar os recursos de criptografia do Amazon S3 utilizando diferentes modelos de Server-Side Encryption para proteção de dados em cloud.

---

# Serviços utilizados

- Amazon S3
- SSE-S3
- SSE-KMS
- DSSE-KMS
- Bucket Key

---

# Cenário do laboratório

## Bucket utilizada

lab-juridico-bucket

## Região

us-east-1

---

# Etapas realizadas

- Acesso às configurações de Default Encryption
- Configuração de criptografia padrão do bucket
- Exploração das opções SSE-S3
- Exploração das opções SSE-KMS
- Visualização do modelo DSSE-KMS
- Habilitação de Bucket Key
- Análise das opções de criptografia server-side

---

# Prints do laboratório

## Tela de configuração de criptografia

![Default Encryption](images/01-default-encryption.png)

---

## SSE-S3 selecionado

![SSE-S3](images/02-sse-s3-selected.png)

---

## Opções SSE-KMS

![SSE-KMS](images/03-sse-kms-option.png)

---

## Bucket Key habilitado

![Bucket Key](images/04-bucket-key-enabled.png)

---

# Conceitos praticados

- Amazon S3
- Server-Side Encryption
- SSE-S3
- SSE-KMS
- DSSE-KMS
- Bucket Key
- Proteção de dados em cloud
- Criptografia de armazenamento

---

# Resultado

O laboratório validou com sucesso:

- configuração de criptografia padrão no S3
- entendimento dos modelos de encryption da AWS
- gerenciamento de proteção de objetos armazenados
- utilização de criptografia server-side

---

# Estrutura do laboratório

```txt
s3-encryption-lab/
│
├── README.md
│
└── images/
    ├── 01-default-encryption.png
    ├── 02-sse-s3-selected.png
    ├── 03-sse-kms-option.png
    └── 04-bucket-key-enabled.png
```

---

# Autor

Lucas Mello

Analista de Suporte Pleno Nível 2  
Estudando AWS Cloud Computing e Infraestrutura Cloud.
