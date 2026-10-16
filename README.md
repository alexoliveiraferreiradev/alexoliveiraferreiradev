# Alex Oliveira Ferreira

**Desenvolvedor Back-end Pleno · .NET & C# · Microsserviços**

Pós-graduando em **Arquitetura de Sistemas .NET** na FIAP. Modelo domínios com Event Storming (Miro) e aplico **DDD**, **Clean Architecture** e **CQRS** em sistemas distribuídos.

### 🚀 Projeto atual: FIAP Cloud Games (Tech Challenge)

* **Fase 2: do monolito aos microsserviços.** Refatorei um monolito em serviços orientados a eventos (`Usuários`, `Catálogo`, `Pagamentos`, `Notificações`) com **MassTransit/RabbitMQ**, **EF Core** e **Dapper**, com imagens Docker por serviço e manifestos **Kubernetes** validados no Minikube.
* **Fase 3: gateway e persistência poliglota.** Coloquei o **Kong** como API Gateway (roteamento, validação de JWT e rate limit), passei a usar **MongoDB** e **Elasticsearch** e criei os domínios `PedidoAPI` e `BibliotecaAPI`.
* **Fase 4 (em andamento): rumo ao Azure.**
  * Troquei a mensageria de RabbitMQ para **Azure Service Bus** (filas e tópicos gerenciados). Como os serviços já falam via MassTransit, a mudança ficou concentrada na configuração do transporte, sem reescrever produtores nem consumidores. [confirmar]
  * Publico as imagens no **Azure Container Registry** e faço o deploy no **AKS**. [confirmar]
  * Guardo segredos e connection strings no **Azure Key Vault**. [confirmar]
  * Pipeline de CI/CD com **GitHub Actions**: build, testes, push das imagens e deploy. [confirmar]
  * Front-end em **React + TypeScript** que consome todo o ecossistema pelo Kong.

**Back-end:** .NET · C# · EF Core · Dapper · MassTransit

**Dados:** SQL Server · MongoDB · Elasticsearch · Redis

**Mensageria:** Azure Service Bus · RabbitMQ

**Cloud e infra:** Azure · Docker · Kubernetes · Kong



## 🌐 Como me achar
<p align="left">
  <a href="https://github.com/alexoliveiraferreiradev"><img  src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"></a>  
  <a href= "https://www.linkedin.com/in/alex-oliveira-ferreira-493196193/"><img src ="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link="></a>
</p>


## 🛠️ Tecnologias e Ferramentas

<div>  
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dot-net/dot-net-plain-wordmark.svg" />
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" />
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-plain-wordmark.svg" /> 
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rabbitmq/rabbitmq-original.svg" />     
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original-wordmark.svg" />
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-plain.svg" />
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kubernetes/kubernetes-plain-wordmark.svg" />   
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-plain-wordmark.svg" />  
<img height="50" width= "60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/visualstudio/visualstudio-plain.svg" />  
<img height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" />
<img height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/elasticsearch/elasticsearch-original.svg" />
<img height="50" width="60" src="https://img.shields.io/badge/Kong-003459?style=for-the-badge&logo=kong&logoColor=white" />
<img height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azure/azure-original.svg" />
</div>


---
⭐️ *Sinta-se à vontade para explorar meus repositórios e deixar uma estrela nos projetos que achar interessantes!*
