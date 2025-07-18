🏦 AgroPay Wallet

AgroCrypto Labs LLC | AgroNet Holding Company
Powered by: Blockchain + AI + Infraestrutura Bancária Real


---

AgroPay é a carteira digital oficial do ecossistema AgroCrypto e AgroNet Holding Company. Conectada a infraestrutura bancária real (via BaaS), blockchain institucional e com validação por IA (ATF), permite aos usuários:

Criar contas digitais com ou sem KYC completo

Consultar saldo e extrato

Transferir valores entre contas AgroPay (P2P)

Realizar transferências bancárias (ACH)

Recarregar a carteira com dinheiro em espécie (eCash)

Sacar em pontos autorizados (Cash Pickup)

Visualizar e gerenciar tokens institucionais (carbono, commodities, ISIN)



---

Tecnologias Utilizadas

Frontend: React Native (Android/iOS)

Backend: Node.js / Express (API Gateway)

BaaS API: OAuth2, REST JSON

Blockchain: AgroCrypto Chain (proof-of-truth)

IA: Validação via ATF (AgroCrypto Trust Framework)

CI/CD: GitHub Actions + Docker



---

Funcionalidades Ativas (v1.0 MVP)

[x] Autenticação de parceiro via OAuth2

[x] Criação de wallet com dados mínimos (Non-KYC)

[x] Consulta de saldo em tempo real

[x] Extrato de transações

[x] Transferências internas (P2P AgroPay)



---

Funcionalidades em Desenvolvimento

[ ] Integração com conta bancária (ACH transfers)

[ ] Depositar com código de barras (eCash)

[ ] Saques em espécie (Cash Pickup)

[ ] Tokenização para Apple/Google Pay

[ ] Painel de Tokens com ISIN, ATF e Custódia



---

Execução Local

# Clonar repositório
$ git clone https://github.com/agronet/agropay-wallet.git
$ cd agropay-wallet

# Instalar dependências
$ npm install

# Configurar variáveis de ambiente
$ cp .env.example .env

# Rodar backend
$ npm run dev


---

Estrutura de Pastas (Backend)

agropay-wallet/
├── controllers/
├── routes/
├── services/
├── middleware/
├── config/
├── utils/
├── .env
├── app.js
└── README.md


---

Licença

© 2025 AgroNet Holding Company LLC. Todos os direitos reservados.

