# MonacoWebAppPublic

## DESCRIÇÃO CURTA
Aplicação WEB de agendamento de serviços automotivos desenvolvido para o Projeto Integrador I [2021/2] da UNIVESP.

## IMAGENS DA APLICAÇÃO

![index](/images/mwa_index.png)

## TECNOLOGIAS UTILIZADAS
#### 🟣 BOOTSTRAP

Em edição

#### 🟢 DJANGO

Para o backend do projeto, utilizamos Django, um framework PYTHON de alto nível, que possibilita 
agilidade no desenvolvimento de um projeto web.
O Django utiliza a arquitetura MVC (Model, Template, View), onde o modelo é responsável pelo 
mapeamento das estruturas do banco de dados do projeto, o template é responsável pela organização 
das visualizações dos nossos dados, ou seja do front-end da aplicação, e por último temos a estrutura de 
views, que é responsável pelo desenvolvimento lógico da nossa aplicação, fazendo a ponte e 
processamento de dados entre front-end e banco de dados.
Além disso o Django conta nativamente com um sistema de administração dos nossos modelos, 
possibilitando assim, de forma rápida e eficiente, a construção de um portal para revisão, consulta, adição 
e deleção de dados por parte do administrador da aplicação.

#### 🔵 POSTGRESS

Para a nossa aplicação, escolhemos utilizar o PostgreSQL, um banco de dados relacional gratuito, e de 
código de aberto, que possui foco escalabilidade e conformidade de dados armazenados. O POSTGRES é 
um banco muito utilizado para desenvolvimento de aplicações PYTHON, bem como seus frameworks que 
compartilham a ideia de código livre, além disso este banco de dados possui integração nativa com a 
plataforma escolhida para hospedagem do projeto.

#### 🟣 HEROKU

A HEROKU é uma plataforma de nuvem como serviço, com suporte a várias linguagens de programação, 
utilizamos tal plataforma para implantar a nossa aplicação e disponibilizá-la para ser acessada em 
qualquer lugar do mundo, no qual se possua conexão livre com a internet, a HEROKU também é uma 
ótima escolha para hospedagem, pois conta com um sistema de gerenciamento de projeto voltado ao 
controle de versionamento, garantindo assim um controle e gestão do desenvolvimento e evolução da 
aplicação através do tempo.

#### 🟠 GIT

Durante todo o ciclo de desenvolvimento do projeto, utilizamos o GIT, um software de código aberto, 
utilizado para gerenciamento e rastreamento das alterações do nosso projeto, a fim de garantir agilidade, 
integridade de dados, e disponibilidade da nossa aplicação, inicialmente utilizamos o provedor GITHUB 
para hospedar nosso versionamento do projeto, e então migramos para o versionamento da HEROKU, a 
plataforma de nuvem utilizada na publicação da nossa aplicação.

## CONCLUSÃO

CONSIDERAÇÕES FINAIS
https://www.istoedinheiro.com.br/com-pandemia-comercio-online-mais-que-dobra-e-ja-chega-a-21-
das-vendas/
https://biblioteca.ibge.gov.br/visualizacao/livros/liv101794_informativo.pdf
O processo de digitalização, seja por vendas online ou presença de marca no cotidiano das pessoas, 
mostra-se hoje ser indispensável para o crescimento de um negócio, principalmente num momento de 
enfrentamento a uma pandemia, onde tal processo foi acelerado, pois este é um meio que busca 
minimizar o impacto negativo da diminuição das visitas físicas de pessoas em estabelecimentos, além de 
buscar maximizar o conhecimento da marca, ao ter seu acesso facilitado. 

Segundo o Isto É Dinheiro, o comércio online mais que dobrou durante a pandemia, por este motivo, 
buscando aumentar a competitividade de um negócio utilizando de ferramentas digitais, foi desenvolvido 
inicialmente neste projeto, uma aplicação Web para a oficina Mônaco Auto Peças, que expõe a marca a 
livre acesso, e possibilita a realização do agendamento de serviços, por meio de qualquer dispositivo com 
acesso livre a internet, como computadores, tablets, ou celulares, desta forma, o cliente conhece o 
negócio, os serviços e valores da oficina, aumentando a confiança na marca, e podendo então solicitar 
seus serviços sem necessidade de exposição aos riscos enfrentados durante a pandemia. Porém o sistema 
falhava em ter uma comunicação clara com o cliente, acerca da solicitação dos seus serviços, por este 
motivo foi desenvolvido na solução final um sistema de administração que permite com que a oficina 
gerencie os agendamentos de serviços realizados via WEB, integrando também um sistema de notificação 
via email, que garante um canal de comunicação direto com o cliente, avisando-o sobre a confirmação de 
recebimento da sua solicitação e conclusão de serviço, além de oferecer um formulário para contato, este 
último, buscando facilitar sobretudo, a comunicação com usuários que estarão tendo seu primeiro 
contato com a marca, e portanto tendo um canal direto para eventuais dúvidas, sugestões ou 
reclamações.

Buscando também maior acessibilidade, foi realizada na versão final, melhoria no acesso da aplicação via 
dispositivos móveis, uma vez que, segundo o IBGE em 2019 o celular era utilizado para acesso a internet 
por 98,6 % das pessoas com 10 anos ou mais, sendo assim, foi realizada uma adequação de visualização 
específica para dispositivos celulares e tablets, além de modernização da aparência da aplicação, 
garantindo uma melhor experiência ao usuário.

Com as melhorias realizadas, levando em consideração o cenário de pandemia e rápida transformação
digital, a versão final trata de melhorias de alguns pontos mais importantes de uma aplicação utilizada em 
um negócio de serviços, que é a experiência do cliente, pois o sucesso de satisfação de um usuário em 
relação a um serviço, é de grande forma impactada pela sua experiência durante o processo, contudo, há 
ainda vários pontos que devem ser explorados com esse mesmo intuito, como desenvolver um sistema 
para que não só a administração da oficina, mas também o cliente, possa acompanhar o andamento da 
sua solicitação de serviço, histórico de serviços realizados, cadastro de informações, como veículos, 
endereços, entre outras informações que facilitem o agendamento de um novo serviço. Além de
melhorias voltadas aos clientes, pode-se melhorar também as ferramentas utilizadas pela administração, 
como por exemplo, o desenvolvimento de uma integração entre a aplicação WEB e o sistema local atual, 
garantindo que os dados estejam sincronizados em ambos os sistemas, evitando assim retrabalho, e 
divergência de dados.
