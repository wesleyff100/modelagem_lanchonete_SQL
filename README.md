# modelagem_lanchonete_SQL

Este é o momento de unirmos todos os conhecimentos adquiridos ao longo da semana para uma entrega mais encorpada. Fique tranquilo: não será algo extremamente complexo. A sugestão é a de dividir a atividade em pequenas partes e fazer um passo de cada vez, com a devida calma. Se tiver alguma dúvida, não espere até a última hora: converse nos fóruns ou com o seu professor-tutor, beleza? Vamos lá!

Uma lanchonete trabalha com o sistema delivery e possui um cardápio com seus sanduíches, cujos dados são: código do item, nome do sanduíche, e preços. Um cliente deve ser cadastrado com nome, telefone, código e endereço e pode realizar um pedido de um ou mais sauduíches, informando as quantidades desejadas. Cada pedido possui um código, um status (0 – em preparação, 1 – em entrega e 2 – entregue) e uma data de emissão, além dos dados do cliente que solicitou o pedido. Os pedidos quando prontos são passados para os entregadores realizarem entrega de um ou mais pedidos. Os entregadores são cadastrados com nome, código e o número do telefone celular.

A partir dos requisitos acima, faça o seguinte:

Construa o modelo conceitual (no BrModelo).
Construa o modelo lógico (no MySQL Workbench)
Construa o modelo físico.
Crie uma inserção de um pedido mantendo as integridades referenciais e monte uma consulta para listar os pedidos em preparação.
Entrega
Pedimos para que, em grupos, crie o modelo conceitual para que vocês não tenham grandes problemas na hora de desenvolver os modelos lógico e físico. Sendo assim, a sua entrega deverá conter somente dois arquivos (em zip). São eles:

Uma imagem: o modelo lógico (o diagrama feito dentro do MySQL Workbench) exportado como uma imagem;
Um único arquivo de texto (extensão .txt): um único arquivo contendo o modelo físico (ex.: CREATE TABLE), as inserções de dados (ex.: INSERT INTO), e a consulta (ex.: SELECT)
