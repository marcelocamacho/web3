A aplicação FloodHelp é pensada na necessidade de criação de fundos para ajuda humanitária em casos de enchentes e alagamentos, tais como os casos vivenciados pelo Estado do Rio Grande do Sul. Os principais programas de assistência e ajuda não disponibilizam canais de doação utilizando cripto-moedas, perdendo uma valiosa possibilidade de recepção de fundos para assistência tanto nacionais, quanto internacionais.

O projeto prevê a possibilidade de criação de requisições de doação, assim uma comunidade poderá requisitar fundos para implementação de projetos específicos, por exemplo, instalação de abrigos, compra de agasalhos infantis, reconstrução de pontes e estradas etc. Cada requisição terá uma meta cadastrada (goal).

RF
1 - Criação de uma requisição (open request)
Uma nova campanha de agariação de fundos será cadastrada no sistema. O autor deverá fornecer um título, uma descrição, um contato (caso alguém queira dar algum outro tipo de ajuda financeira ou não) e um objetivo/meta a ser alcançada.
Além desses campos, todas as campanhas terão que armazenar o autor, o status, o valor já arrecadado (balance) e um timestamp.

2- Fechar a requsição (close request)
Toda requisição será fechada automaticamente quando alcançar o seu objetivo. Ou caso o seu autor julgue necessário o fechamento, nesse caso, apenas o autor poderá executar essa ação.

3 - Doar (donate)
As contas poderão fornecer doação para uma requisição, fornecendo o valor da doação e o id da campanha específica.

4 - Listar requisições
As pessoas devem verificar quais são as campanhas em andamento que ainda estejam abertas (não tenham atingido a meta). Caso existam várias requisições abertas, o sistema deve permitir a paginação dos resultados.


