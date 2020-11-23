SISTEMA DE CONTROLE MERCADINHO 

Projeto – 2ª Avaliação 
					       Grupo: Black Mirror

1. CONTEXTO DE APLICAÇÃO 
Uma empresa que atua na área de vendas de produtos e utilidades em geral, tendo como foco satisfazer os clientes com as vendas de produtos da empresa. É uma empresa que atende a comunidade local e vizinhanças. Atualmente não possui qualquer sistema para atender as atividades operacionais ou gerenciais dos seus processos internos e externos. Os controles de cadastro de cliente, produto e vendas são feitos manualmente por intermédio de fichas de cadastros.  
As formas de armazenamento são feitas da seguinte maneira: a empresa coloca na ficha de cadastro de cliente o nome da pessoa, produto vendido, valor total e armazena em uma gaveta, a ficha de cadastro de produtos contém nome do produto, quantidade, valor de entrada e valor de saída, na qual é armazenada da
mesma forma. Não tem uma ficha em especial para o controle de vendas, pois ela é registrada na mesma ficha do cliente, contendo o nome do produto, quantidade e valor da venda. 
1.1. Levantamento de Requisitos e Riscos 
Será abordado também além dos requisitos, os riscos apresentados sob o domínio do problema da empresa. Estes riscos devem ser levantados e apontados, para contra pôr a não utilização de nenhum software que controle os processos e informações relevantes, além das necessidades apresentadas pelos usuários. Ou seja, o que você poderá apresentar como riscos? 
1.1.1 Problemas Existentes 
A empresa possui apenas o sistema manual para o controle de cadastro de cliente, produto e estoque. Esse cenário dificulta a gerência da empresa e gera perdas de tempo no atendimento dos clientes e dificuldades de controle das vendas. Todos os produtos vendidos são anotados na ficha do cliente ou em qualquer outro rascunho disponível, caso não exista uma ficha com seus dados cadastrais. Em determinados momentos, os funcionários esquecem-se de anotar as transações, tornando vulnerável a organização dos produtos da loja. Após a entrada e a saída de produtos, os funcionários atualizam o estoque manualmente, havendo dificuldades para realizar esse controle e desperdício de tempo na execução das tarefas. 
Os problemas existentes na empresa podem ser resumidos em: 
Falta de controle de estoque: a empresa vende um produto e tem a dificuldade de saber quantos produtos tem no estoque. 
Falta de controle de clientes: o cadastro é feito em fichas de papel, tendo assim, dificuldade para organizá-las. A possível perda de fichas é uma preocupação. 
Falta de controle com as transações dos produtos: não existe controle preciso de produtos no estoque no momento da compra ou venda.
Falta de relatórios: não existem formas de visualização de relatórios, com isso, a empresa fica vulnerável com relação às suas informações. 
1.1.2 Desejos do Cliente 
Durante o processo de levantamento de requisitos, o cliente manifestou alguns desejos, entre eles implantar um sistema que possa disponibilizar com maior facilidade a realização dos cadastros de clientes e produtos e ter um controle de
estoque, para saber o que existe na empresa de produtos. O cliente também gostaria de um sistema que gerasse relatórios da movimentação da empresa, de modo a fornecer maior confiança às suas negociações. 
Além de obter relatórios mais precisos e ágeis, esse sistema forneceria maior apoio aos processos de vendas da empresa, visto que controlará todas as movimentações de compras e vendas, aumentando assim a clareza de informações e auxiliando para o contínuo crescimento da empresa. A lista seguinte aponta um conjunto de desejos manifestados pelos usuários: 
Ter um controle de cadastro de clientes 
Ter um controle de cadastro de produtos 
Ter um controle de estoque 
Ter um controle nas transações de compra e venda 
Melhorar organização da empresa com relatórios precisos 
Tornar o trabalho mais fácil e rápido 

1.1.3 Soluções Alternativas 
Para solucionar os problemas da empresa foi sugerido criar várias planilhas no Microsoft Office Excel que ajudariam aos usuários do sistema na organização da empresa. Como analisa de sistemas, e com base nos seus conhecimentos técnicos sobre processos de requisitos e análise e engenharia de software. Após a execução da solução, deverá ser feita a migração dos dados para alimentar o sistema e assim executar um treinamento na empresa ensinando o funcionamento do sistema para os funcionários.
1.1.4 Solução Escolhida 
Considerando que, a primeira opção foi descartada, pois seria difícil a organização de toda empresa nas planilhas do Microsoft Office Excel, levando também em consideração que, para gerenciar uma empresa através de planilhas, possivelmente exigiria a manipulação de várias tabelas, podendo tornar o serviço mais complicado, moroso e confuso. Também existe a necessidade de se gerar relatórios de forma mais precisa e completa, fazendo esse trabalho no Microsoft Office Excel não seria tão eficaz conforme imaginado pelo cliente inicialmente. 
Desse modo, a maneira mais eficaz de resolver esse problema seria a implementação do sistema de uma forma simples, por enquanto, seria feita uma tela de armazenamento de planilhas excel, separando-as pelos seus títulos e disponibilizando ao usuário a busca por título ou assunto. Fazendo com que na hora do término do sistema seja mais eficiente a busca de uma determinada tabela excel e prático na montagem do banco de dados. 
1.1.5 Impactos do Sistema na Organização


Nesse ponto, como vimos anteriormente, será feita uma tela para ajudar a armazenar as informações que os usuários obtêm no dia-a-dia, criando assim uma tela para armazenar os registros e poder buscar esses registros de forma eficiente. O importante é buscar o que o cliente mais necessita no momento para assim poder ir desenvolvendo o sistema de maneira organizada e de fácil entendimento para o usuário.
1.2. Elaboração e Especificação 
Essas atividades focam o desenvolvimento de um modelo técnico com características e restrições do software. Uma análise abrangente e correta para que ao final do desenvolvimento e, consequentemente, durante a entrega do software exista o mínimo de erros possíveis no sistema. Além do mais, iremos mostrar detalhes das características do sistema e seu funcionamento, a partir da definição de atores, eventos, diagramas de casos de uso e diagrama de classes. A modelagem dos diagramas de análise foi realizada por intermédio da linguagem UML (Unified Modeling Language). É importante salientar a natureza simples do sistema, que é desta maneira por design. Como a empresa contratante está tratando de uma operação de baixa escala, é interessante manter a complexidade do sistema relativamente baixa, diminuindo assim o tempo de treinamento dos atores que prestam serviço à empresa.
1.2.1 Definição dos Atores 
Os atores representam entidades que irão interagir com o sistema, onde temos o Cliente, Caixa, Gerente  e Conta Bancária:
Cliente: Como o nome sugere é o cliente comum, que entra no mercado e interage minimamente com o sistema, tendo sua interação limitada ao momento do checkout.
Caixa: É o empregado comum, com a credencial mais baixa. Geralmente se trata de um caixa dedicado. Tem a maior parcela de interação com o sistema, podendo realizar cadastro de clientes e sendo responsável pelo checkout.
Gerente: Não interage tanto quanto o Caixa, no entanto carrega uma responsabilidade grande, tendo credenciais absolutas, podendo realizar vendas em modalidade fiado assim como negociar o pagamento dessas dívidas.
Conta Bancária: Interage com o sistema apenas na transferência de dinheiro no ato de quaisquer pagamentos.

1.2.2 Lista de Requisitos 
Durante as entrevistas com o cliente foram coletados os desejos do cliente. Estas informações somadas ao estudo realizado pelo grupo deu origem aos requisitos que moldam o sistema, são estes:


Requisitos não funcionais:

O sistema deve ser desenvolvido em linguagem Java.

A interface deve ser agradável e de fácil utilização.

O sistema deve ser mantido em um computador local.

O banco de dados será mantido no computador local, assim como automaticamente mantido e atualizado na nuvem (google drive).

	
Requisitos funcionais:

O sistema permitirá que pessoas sejam cadastradas, classificando-os como: cliente, caixa e gerente.

O sistema permitirá que o caixa possa cadastrar clientes no entanto somente o gerente pode fazer alterações no cadastro dos clientes.

O sistema permitirá o acesso dos caixas e gerentes através de login e senha.

O sistema trabalhará com operações de venda chamados de checkout.

O sistema fará o controle de estoque através de classes de Produto e ArrayLists de Produto.

O sistema permitirá que produtos sejam cadastrados, armazenando atributos como preço e quantidade.

O sistema terá compatibilidade com softwares externos de cartões de cobrança e pagamentos.

O sistema irá gerar identificadores únicos para cada operação de checkout realizado.

1.2.3 Diagrama de Caso de Uso 
O diagrama de caso de uso irá relata toda interação entre os atores e o sistema, cada evento gera ações de interação entre os atores e o software desenvolvido. 

1.2.4 Diagrama de Classes 
O diagrama de classes será de fundamental importância nesse software, onde o diagrama mostra o comportamento das classes dentro do sistema.

2. CONCLUSÃO 

O trabalho desenvolvido visou desde o começo tentar satisfazer os desejos do cliente de uma maneira simples e com baixa complexidade. O principal motivo para essa escolha  foi o fato do contratante dirigir uma operação de baixa escala, uma empresa que fornece produtos para a comunidade local, ficando claro que não seria de interesse do cliente gastos excessivos em treinamento e a possibilidade de problemas decorrentes de mau uso do sistema.
Com essa visão em mente, foram criados diagramas de caso de uso e de classes simples e sem muitas funcionalidades extra. 

