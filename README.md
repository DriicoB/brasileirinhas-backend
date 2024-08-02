# brasileirinhas-backend

## Requisitos
1. Requisitos Funcionais:
    - Autenticação e Autorização:
    Usuários devem poder se registrar e fazer login.
    Diferentes níveis de acesso (administradores, visitantes).
    - Gerenciamento de Conteúdo:
    CRUD (Create, Read, Update, Delete) para artigos sobre o Brasil.
    Upload e gerenciamento de imagens e vídeos.
    - Pesquisa e Filtragem:
    Pesquisa de artigos por palavras-chave.
    Filtragem por categorias, data de publicação, regiões do Brasil, etc.
    - API Pública:
    Endpoints para acesso aos dados do site .

2. Requisitos Não Funcionais:
    - Performance:
    Respostas rápidas às solicitações dos usuários.
    Capacidade de lidar com um grande número de acessos simultâneos.
    - Segurança:
    Proteção contra ataques comuns.
    Armazenamento seguro de senhas (hashing).
    - Escalabilidade:
    Arquitetura que permita a fácil adição de novos recursos.
    Capacidade de escalar horizontalmente.
    - Disponibilidade e Confiabilidade:
    Backup e recuperação de dados.
    Mecanismos de failover.

 ## Tarefas

 - [ ] Implementar o endpoint para criar usuários
 - [ ] Implementar a verificação do perfil do usuário em todos os endpoints
 - [ ] Limitar o acesso ao endpoint de criar usuários
 - [ ] Criar filtragem por categorias
