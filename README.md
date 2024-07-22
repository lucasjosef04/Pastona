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

