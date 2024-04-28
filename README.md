# Projeto-conceitual-para-e-commerce
--Modelo ER-para-e-commerce--

Desafio de projeto realizado para o Bootcamp "Formação SQL Database Specialist". Neste projeto conceitual, foram feitas refinações do esquema com o propósito de melhor atender às necessidades do suposto e-commerce, criado apenas para fins de aprendizado. Pontos explorados:


O tipo de identificação (CPF ou CNPJ) foi representado como atributo da tabela "Cliente", tendo em vista que a criação de uma tabela própria para a informação se mostraria irrelevante;
A tabela "Pagamento" possui relacionamento N:M com o pedido, já que é possível a realização de mais de um tipo de pagamento a depender da preferência do cliente;
Em relação à entrega, optou-se por anexar as informações de status e código de rastreio diretamente à entidade "Pedido".
