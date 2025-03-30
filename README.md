# Lista1
ATIVIDADE AVALIATIVA Lista de Exercícios 1

1. Quais protocolos (os principais) são usados em uma comunicação realizada na web? Descreva muito brevemente o papel de cada um deles.
2. Alguns autores usam o termo “arquitetura da web” para se referir a como as camadas tecnológicas da web estão organizadas e aos princípios que definem a troca de informações entre essas camadas.
Por questões didáticas e de simplificação, convencionou-se chamar essa arquitetura de “arquitetura cliente x servidor” ou arquitetura “requisição x resposta”. Explique de forma simplificada como funciona essa arquitetura.
3. Em uma arquitetura web, qual o papel desempenhado pelo protocolo HTTP?
4. O HTTP possui padrões uniformes para requisição e para resposta.
a) Dê ao menos três exemplos métodos de requisição e suas
características;
b) Dê ao menos três exemplos status de respostas e quando ocorrem;

1. O protocolo HTTP da camada de aplicação tem o papel de realizar a comunicação entre software (navegador e servidor web), descobrir o endereço IP do site, então fazer uma requisição DNS para converter em IP e enviar uma requisição HTTP GET. O protocolo TCP da camada de transporte tem o papel de garantir que os dados cheguem completos e na ordem correta, abrir uma conexão TCP com o servidor na porta 80, e estabelecer a conexão e enviar a requisição HTTP GET ao servidor. O protocolo IP da camada internet, tem o papel de rotear os pacotes até o servidor correto e o navegador encapsula a requisição HTTP dentro de pacotes IP, que são enviados pela internet passando por roteadores que os direcionam ao destino. 

2. A arquitetura cliente x servidor funciona com o cliente, que pode ser um navegador web, que solicita uma requisição ao servidor, e o servidor, que é onde o site está hospedado, recebe a requisição, e envia uma resposta de volta.

3. Definir uma série de interfaces de requisição e resposta, a requisição é padronizada por meio de verbos (GET, POST, PUT) que indicam a ação principal e a resposta é padronizada por meio de códigos (200, 301, 404) que indicam o status da solicitação.

4.
a) GET - solicita dados, POST - envia dados, DELETE - remove dados do servidor. 
b) 404 - não encontrado, 200 - requisição aceita, 500 - erro interno do servidor
