# Projeto Santa Dallah :cake:

Esse projeto tem o propósito de desenvolver um sistema para uma empresa de confeitaria de Joinville chamada Santa Dallah. O projeto tem como objetivo exibir o catálogo de produtos da empresa, vender os produtos e oferecer para o usuário uma interface onde ele pode personalizar seu pedido.


Professor: [Marco André Mendes](github.com/marcoandre)

Equipe:
- [Ana Laura Manfron Dias](https://github.com/analauradias)
- [Isabelli Luisa Rosa](https://github.com/isabellirosa)
- [Júlia Fuck](https://github.com/fujulia)
- [Rafaela Barbieri da Cruz](https://github.com/rafaelabarbieric)
  
  
Links do projeto:

-   [Documentação (esse documento)](https://github.com/fujulia/Projeto-Integrador)
-   Backend: [Repositório](https://github.com/Projeto-Santa-Dallah/SantaDallah_BackEnd) e [Publicação](https://pi-backend.herokuapp.com/)
-   Frontend: [Repositório](https://github.com/Projeto-Santa-Dallah/SantaDallah_FrontEnd) e [Publicação](https://pi-frontend.herokuapp.com/)
  
  



# 1. Desenvolvimento

## Sistema de Vendas

O sistema planeja ter uma interface tanto para o usuário cliente quanto para o usuário administrador. Para o usuário cliente o sistema se apresenta como um site de vendas de bolos, tortas e brigadeiros, no qual o usuário pode selecionar, comprar, avaliar e personalizar seu próprio produto. O usuário cliente pode também  montar o seu pedido a partir das opções de sabores que a empresa oferece, por exemplo ele poderá montar um bolo escolhendo o sabor da massa e do recheio, além de escolher o peso, formato e decoração. Para o usuário administrador o sistema funcionará como uma interface de controle de produtos, clientes, pedidos e respostas de usuários. 
	
O motivo da escolha por esse tipo de sistema se deve ao fato do grupo possuir contato com uma empresa de confeitaria que tem interesse em modernizar sua gestão de vendas de pedidos.  


# 2. Situação Problema


![Ciclo da Venda](img/Usuário.png "Ciclo da Venda")

	
A empresa escolhida para o desenvolvimento do sistema não se trata de um negócio fictício, mas sim de um estabelecimento real localizado em Joinville. A empresa, chamada Santa Dallah, é uma confeitaria que produz bolos, tortas e brigadeiros e está no mercado desde 2019, tendo assim 6 anos de experiência.  Foi fundada por Anderson e Geisiane, um casal que busca trazer mais doçura e amor para os momentos especiais das pessoas, o Anderson é responsável pela criação e produção dos doces e a Geisiane pelo atendimento e todo o administrativo da empresa. Desse modo, eles são os únicos funcionários da empresa  e precisam de uma ferramenta tecnológica que os auxiliem a gerenciar seu processo de venda. 

Na maioria dos casos, o primeiro contato do cliente com a Santa Dallah ocorre por meio do Instagram. Em seguida, ele é direcionado para o WhatsApp, onde poderá concluir seu pedido. Nessa etapa, é essencial confirmar se o pedido está sendo realizado com, no mínimo, dois dias de antecedência ao evento. Após essa verificação, o cliente fornece suas informações pessoais, especifica o tipo de doce desejado e, se necessário, encaminha uma imagem ilustrativa como referência para a personalização do produto. Além disso, são definidos a forma de pagamento e os detalhes sobre a entrega.
 	
O processo de produção do doce ocorre conforme o tipo solicitado. Por exemplo, a montagem de bolos decorados é realizada em etapas: inicialmente, são preparados a massa e os recheios, geralmente com um dia de antecedência. No dia da entrega, é feita a montagem e decoração do bolo. Os mesmos métodos são aplicados aos brigadeiros, que são preparados no dia anterior e finalizados no dia da entrega. Já as tortas e os bolos vulcão são inteiramente produzidos no próprio dia da entrega.

No dia do evento, a entrega do doce pode ser realizada por um funcionários ou, caso prefira, o cliente pode retirá-lo diretamente no ateliê. Durante esse processo, também é efetuado o pagamento do produto.

Ao longo do processo de venda, identificamos diversos desafios que impactam tanto o trabalho dos funcionários quanto a experiência dos clientes. Com o objetivo de facilitar essa jornada, decidimos criar uma solução que integrasse todas as ferramentas utilizadas pela empresa em um único site. O Instagram, por exemplo, é uma plataforma essencial para apresentar o trabalho da empresa e gerar o interesse de compra. No entanto, no nosso sistema, substituiremos a necessidade do Instagram por diversas imagens que incentivem o usuário a realizar a compra, sempre destacando a qualidade dos produtos do estabelecimento.	

A página inicial do site será cuidadosamente desenvolvida para exibir informações detalhadas e fotos que mostrem a excelência dos produtos vendidos. Além disso, teremos uma seção dedicada a imagens de doces de casamento, oferecendo aos clientes a oportunidade de conhecer o trabalho do ateliê da empresa e se inspirar para o design do seu bolo.

Após o cliente conhecer a empresa por meio do Instagram, ele é direcionado para o WhatsApp da empresa, onde realiza seu pedido. Ao iniciar o contato, o funcionário responsável pelo atendimento envia um PDF com informações sobre a empresa, além de fotos, características e preços dos produtos. Para tornar essa etapa mais rápida e moderna (já que nem sempre o contato no WhatsApp ocorre de forma automática) , nosso site integrará todo o processo de compra.Haverá uma página de produtos com todas as informações do PDF, e os doces com sabores personalizados poderão ser montados conforme a escolha do cliente. Além disso, se o produto for um bolo, o cliente poderá enviar uma imagem de referência para a decoração. O pagamento será feito diretamente no site, e o cliente poderá escolher entre a entrega ou a retirada do produto.

Para facilitar o gerenciamento, será criada uma página de administração, onde os funcionários da Santa Dallah poderão acompanhar e gerenciar todos os pedidos de forma eficiente.


# 3. Descrição da proposta


O software tem como foco **automatizar** o processo de venda dos produtos da empresa Santa Dallah. Ele irá apresentar **dois níveis de usuários, cliente e administrador**, o usuário administrador tem acesso as páginas de administração do sistema e as páginas de venda, sendo assim possui acesso a todo o sistema, e o usuário cliente possui acesso apenas as páginas de venda. **Os usuários administradores são os donos da empresa e os usuários clientes são as pessoas no geral que usarem o sistema**. Nas páginas de administração será possível **adicionar, editar e excluir os produtos vendidos pela empresa, além de gerenciar os clientes e os pedidos**. Já nas páginas de venda será possível **visualizar, comprar e curtir produtos, comentar sobre os produtos, se cadastrar e realizar login, montar seu proprio bolo por meio de um formulário e mandar mensagens para a empresa**. 




