# Caderno

### Camadas do Server
    Service: Tudo que é regra de negocios ou processamento
    Controller: Intermedi a camada de apresentação e a caada de negócio
    Routes: Camadas de apresentação
    Server: responsavél por criar o servidor (mas não instancia)
    index: instancia o servidor e expoe para a web (lado de infraestrutura)
    config: tudo que for estático no projeto

**OBS:** A routes nunca pode chamar um service diretamente


## Stacks
- pino@7.8.0: á umm biblioteca de logs
- fileURLToPath: transforma a URL em um path (está em config) 


##  Pesquisar
- NodeJS strings