#App

Gympass Style App.

## RFs (Requisitos funcionais)

- [ ] Deve ser possivel se cadastrar;
- [ ] Deve ser possivel se autenticar;
- [ ] Deve ser possivel obter o perfil de um usuario logado;
- [ ] Deve ser possivel obter o numero de check-ins realizados pelo usuario logado;
- [ ] Deve ser possivel o usuario obter seu historico de check-ins;
- [ ] Deve ser possivel o usuario buscar academia proximas;
- [ ] Deve ser possivel o usuario buscar academia pelo nome;
- [ ] Deve ser possivel o usuario realizar check-in em uma academia;
- [ ] Deve ser possivel validar o check-in de um usuario;
- [ ] Deve ser possivel cadastrar uma academia;

## RNs (Regras de Negocios)

- [ ] O usuario nao deve poder se cadastrar com um e-mail duplicado;
- [ ] O usuario nao pode fazer 2 check-ins no mesmo dia;
- [ ] O usuario nao pode fazer check-in se nao estiver perto (100m) da academia;
- [ ] O check-in so pode ser validade ate 20 minutos após criado;
- [ ] O check-in só pode ser validado por admnistradores;
- [ ] A academia só pode ser cadastrada por admnistradores;

## RNFs (Requisitos nao-funcionais)

- [ ] A senha do usuario precisa estar criptograda;
- [ ] Os dados da aplicacao precisam estar persistindo em um banco PostgreSQL;
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por pagina;
- [ ] O usuario deve ser identificado por um JWT (JSON Web Token);
- [ ] 

