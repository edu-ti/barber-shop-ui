# Barber Shop UI

## Descrição
Este projeto é uma interface para um sistema de cadastro de clientes e agendamento em uma barbearia. Desenvolvido em **Angular 19**, o objetivo é fornecer uma experiência intuitiva e moderna para os clientes da barbearia.

## Tecnologias Utilizadas
- **Angular 19**
- **TypeScript**
- **Node.js 22**
- **PostgreSQL** (via Docker)
- **Docker**

## Funcionalidades
- Cadastro de clientes
- Lista de clientes
- Agendamento de serviços

## Instalação e Execução
1. Clone o repositório:
   ```sh
   git clone https://github.com/edu-ti/barber-shop-ui.git
   ```
2. Acesse o diretório do projeto:
   ```sh
   cd barber-shop-ui
   ```
3. Instale as dependências:
   ```sh
   npm install
   ```
4. Suba o banco de dados com Docker:
   ```sh
   docker-compose up -d
   ```
5. Execute o servidor de desenvolvimento:
   ```sh
   ng serve
   ```
6. Acesse no navegador:
   ```
   http://localhost:4200
   ```

## Estrutura do Projeto
```
barber-shop-ui/
│-- src/
│   │-- app/
│   │   │-- components/  # Componentes reutilizáveis
│   │   │-- pages/       # Páginas principais
│   │   │-- services/    # Serviços e chamadas HTTP
│   │   └-- models/      # Modelos de dados
└-- angular.json         # Configurações do Angular
```

## Contribuição
Sinta-se à vontade para contribuir! Para isso:
1. Fork o repositório
2. Crie uma branch (`feature/nova-funcionalidade`)
3. Commit suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Envie um PR para análise

## Contato
Desenvolvido por **Eduardo Cabral de Souza**
- 📧 edu_ti@outlook.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/eduardo-cabral-21733221/)

---
## PROJETO REALIZADO PARA O BOOTCAMP DECOLATECH DA DIO EM PARCERIA COM AVANADE BRASIL
