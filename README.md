# 🥛 MilkyFlix

Bem-vindo ao projeto MilkyFlix, onde você organiza sua lista de filmes e séries para assistir. **MilkyFlix** é um aplicativo web desenvolvido com o objetivo de permitir que os usuários gerenciem facilmente sua lista pessoal de filmes e séries, marcando o que desejam assistir e o que já assistiram.

## 🎬 Visão Geral

MilkyFlix é inspirado no nome da minha gatinha, Milky, e no conceito de organizar suas preferências de entretenimento em um único lugar. A aplicação é projetada para ser intuitiva e eficiente, oferecendo uma experiência simplificada de gerenciamento de watchlist.

## 🏛 Arquitetura

MilkyFlix é composto por vários componentes que trabalham juntos para fornecer uma experiência completa:

### Componentes

- **🖥️ Frontend Web**
   - Repositório: [milkyflix-web](https://github.com/gizellysteffanny/milkyflix-web)
   - Descrição: Interface web para gerenciamento da lista de filmes e séries.

- **🔧 Backend For Frontend (BFF)**
   - Repositório: [milkyflix-bff](https://github.com/gizellysteffanny/milkyflix-bff)
   - Descrição: Serviço intermediário que consome APIs do backend e fornece dados formatados para o frontend web.

- **🔑 Microserviço de Autenticação**
   - Repositório: [milkyflix-auth-service](https://github.com/gizellysteffanny/milkyflix-auth-service)
   - Descrição: Serviço responsável pela autenticação de usuários.

- **🎥 Microserviço de Gerenciamento de Filmes/Séries**
   - Repositório: [milkyflix-movie-service](https://github.com/gizellysteffanny/milkyflix-movie-service)
   - Descrição: Serviço para adicionar, editar, listar e remover filmes e séries da watchlist.

### Tecnologias Utilizadas

- **Frontend (Angular 17)**
   - Angular 17: Framework utilizado para construir o frontend web do MilkyFlix.
   - Angular Material: Componentes UI para um design consistente e moderno.

- **Backend**
   - Java com Spring Boot: Backend que suporta a lógica de negócios e APIs RESTful.
   - MongoDB: Banco de dados utilizado para armazenamento de dados flexível.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests, relatar problemas ou sugerir melhorias para qualquer um dos componentes do MilkyFlix.

## 📄 Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE), o que significa que você pode utilizá-lo livremente em seus próprios projetos.

---
Este README organiza claramente os diferentes componentes do MilkyFlix, facilitando a compreensão de como cada parte contribui para a funcionalidade geral do aplicativo. Certifique-se de explorar os repositórios individuais para obter detalhes técnicos específicos e instruções de configuração.
