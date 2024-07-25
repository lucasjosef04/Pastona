Aluno: Lucas Jose da Silva 206.003
O que é um sistema de controle de versões
Um sistema de controle de versão tem uma finalidade de gerenciar diferentes versões de um documento. O sistema também é muito utilizado em empresas de tecnologia e desenvolvimento de software, o sistema também ajuda muito as equipes de software a gerenciar as alterações ao código-fonte, com isso o sistema ajudam as equipes a trabalhar de forma mais rápida e inteligente.  O software de controle de versão também mantem o registro de todas as modificações no código em um tipo especial de banco de dados, assim quando houver algum erro cometido, os desenvolvedores podem voltar no tempo e comparar as versões anteriores e corrigir o código errado enquanto diminuem interrupções para os membros da equipe. 
Vantagens de se utilizar um VCS
1:Ramificação de projeto: a maioria das implementações possibilita a divisão do projeto em várias linhas de desenvolvimento, que podem ser trabalhadas paralelamente, sem que uma interfira na outra.
2:Segurança: Cada software de controle de versão usa mecanismos para evitar qualquer tipo de invasão de agentes infecciosos nos arquivos. Além do mais, somente usuários com permissão poderão mexer no código.
3:Rastreabilidade: Com a necessidade de sabermos o local, o estado e a qualidade de um arquivo; o controle de versão traz todos esses requisitos de forma que o usuário possa se embasar do arquivo que deseja utilizar.
4:Organização: Alguns softwares disponibilizam uma interface visual onde podem ser vistos todos os arquivos controlados, desde a origem até o projeto por completo.
5:Confiança: O uso de repositórios remotos (na nuvem) ajuda a não perder arquivos por eventos inesperados. Além disso, e possível fazer novos projetos sem danificar o desenvolvimento do atual.
Exemplos de VCS
1.	Git: Um VCS distribuído amplamente conhecido por sua velocidade,eficiência e suporte a ramificação e fusões complexas
2.	Subversion: Um VCS centralizado que é popular em muitos projetos, conhecido por sua simplicidade e suporte a operações atômicas.
3.	Mercurial: Outro VCS distribuído, similar ao Git, conhecido por sua facilidade de uso e uso e desempenho eficiente em projetos de todos os tamanhos
Protocolo de comunicação

O HTTP funciona desta maneira: o cliente inicia uma solicitação ao servidor web, digitando-a na barra de endereço do navegador. Este, por sua vez, responde inicialmente com um código de status, que consiste em três dígitos. Ele contém a informação se a solicitação pode ser respondida com sucesso ou não.

O REST: se baseia em um estilo arquitetural que consiste de um conjunto coordenado de restrições arquiteturais aplicadas a componentes, conectores e elementos de dados dentro de um sistema de hipermídia distribuído. O HTTP é o principal protocolo para a transferência de dados nesse estilo arquitetural.

APIs Web: e REST são usadas para construir aplicativos que fornecem recursos e se comunicam através de HTTP. Enquanto REST descreve restrições arquitetônicas sobre uma interface uniforme, as Web APIs são geralmente um conceito que pode ser RESTful, dependendo da implementação.

Listagem de HTTP e Rest

•  GET: Solicita a representação de um recurso específico. É seguro (não deve alterar o estado do servidor) e idempotente (múltiplas requisições idênticas produzem o mesmo resultado).
•  POST: Submete dados para serem processados por um recurso específico. Geralmente usado para criar novos recursos, realizar operações de processamento de dados ou submeter formulários.
•  PUT: Substitui todas as representações atuais do recurso de destino pelos dados enviados na requisição. É idempotente.
•  PATCH: Aplica modificações parciais a um recurso. Diferente do PUT, que substitui completamente o recurso, o PATCH é usado para atualizações parciais e específicas.
•  DELETE: Remove o recurso especificado.
•  HEAD: Solicita apenas os cabeçalhos de resposta, sem retornar o corpo da resposta. Usado para obter informações sobre um recurso sem transferir o corpo da resposta.
•  OPTIONS: Retorna os métodos HTTP suportados pelo servidor para o URL especificado, ou descreve a comunicação opcional disponível para um recurso (geralmente usado para Cross-Origin Resource Sharing - CORS).
•  TRACE: Ecoa de volta a requisição recebida para que o cliente possa ver quais alterações ou adições foram feitas pelo servidor ou intermediários.
•  CONNECT: Estabelece um túnel para o servidor identificado pelo URI fornecido.

Claro, vou definir as responsabilidades de cada uma das camadas em um típico padrão de arquitetura de software, como geralmente são entendidas:

1. **Entity (Entidade)**:
   - Responsabilidade: Representa uma estrutura de dados ou objeto dentro do domínio do negócio. 
   - Descrição: Esta camada normalmente contém classes ou estruturas de dados que modelam as entidades principais do sistema, como usuários, produtos, pedidos, etc. Elas geralmente refletem diretamente as tabelas do banco de dados em um sistema de persistência de dados.

2. **Repository (Repositório)**:
   - Responsabilidade: Gerencia a camada de acesso aos dados, abstraindo as operações de persistência.
   - Descrição: Esta camada fornece uma interface para acesso aos dados armazenados (geralmente um banco de dados, mas pode ser qualquer fonte de dados). Ela encapsula a lógica de consulta e persistência de dados, permitindo que outras partes do sistema interajam com os dados sem precisar conhecer detalhes da implementação de armazenamento.

3. **Service (Serviço)**:
   - Responsabilidade: Implementa a lógica de negócios e coordena a execução das operações do sistema.
   - Descrição: Os serviços contêm a lógica de aplicação do sistema. Eles são responsáveis por orquestrar as operações que não pertencem diretamente às entidades ou aos repositórios, mas sim à lógica de negócios. Isso pode incluir validações complexas, operações que envolvem várias entidades ou transações, regras de negócio específicas, etc.

4. **Controller (Controlador)**:
   - Responsabilidade: Gerencia as requisições HTTP, controla o fluxo de dados entre a camada de visão (front-end) e o backend.
   - Descrição: Nos sistemas web, os controladores recebem requisições dos clientes (por exemplo, navegadores ou aplicativos móveis), processam essas requisições, e coordenam a execução dos serviços necessários para cumprir as requisições. Eles lidam com a entrada e a saída de dados, convertendo dados de requisições em chamadas para os serviços apropriados e convertendo as respostas desses serviços em respostas HTTP para o cliente.

Essas definições são bastante genéricas e podem variar dependendo do contexto e das especificações de um projeto específico. No entanto, essas camadas são comumente encontradas em arquiteturas de software que seguem padrões como MVC (Model-View-Controller) ou arquiteturas mais modernas baseadas em serviços (como microservices).