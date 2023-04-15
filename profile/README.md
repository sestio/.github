# Sestio

Um ERP simplificado para a prática de tecnologias de desenvolvimento.  
Algumas tecnologias e metodologias aplicadas:
- .NET Core
- Typescript, 
- React
- SGBD variados
- TDD
- DevOps
- Microsserviços
- Kubernetes + Helm charts
- RabbitMQ

## Sobre o nome

"Gestio" é uma das formas em latim para "gestão" ou "gerenciamento".  
O nome `Sestio` toma o termo `Gestio` e troca o "G" pelo "S" de `Simplificado`.

## Sobre os repositórios

A maioria dos repositórios nessa organização são mantidos privados por dois motivos:
1. Os workflows responsáveis pelo CI/CD utilizam [runners privados](https://docs.github.com/en/actions/hosting-your-own-runners/about-self-hosted-runners) e repositórios publicos representariam um risco de segurança;
1. Muito do código nesses repositórios é experimental, portanto não é a coisa mais elegante para se mostrar ao público.

Tendo isso dito, eu ainda pretendo utilizar esse projeto como uma forma de "portifólio" então alguns repositórios
vão receber, ao longo do tempo, uma versão pública.  
Essas versões públicas serão repositórios próprios contendo uma cópia exata do branch *master* do repositório real (privado).  
É esperado que algumas coisas não funcionem corretamente nas cópias públicas. A mais óbvia delas sendo os workflows (pipelines)
que falham em repositórios públicos devido ao fato de runners privados não aceitarem *jobs* de repositórios públicos (por motivos de segurança).

