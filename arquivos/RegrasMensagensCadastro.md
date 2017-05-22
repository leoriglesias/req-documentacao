# Especificações de Regras de Negócio e Mensagens do Sistema 

## 1. Regras de Negócio Cadastrar Veículo 

- ### RNG001 
É obrigatório que seja informada a placa e o chassi do veículo.

- ### RNG002 
É permitido uma pessoa ter mais de um carro.

- ### RNG003 
É permitido um carro ter mais de uma pessoa responsável, mas no máximo duas pessoas.

- ### RNG004 
A cada 30 dias será necessário confirmar com o cliente se ele possui os mesmos veículos (pois a pessoa pode vender o carro e ficar 
cadastrado no sistema no nome de outra pessoa).

- ### RNG005 
Ao cadastrar um veículo o sistema deve verificar em "algum site" se o veículo é roubado.

- ### RNG006 
Deve constar na ficha de cadastro qual funcionário do estabelecimento cadastrou o veículo.

- ### RNG007 
Deve haver um verificador de chassi para ver se as informações informadas na hora do cadastro como por exemplo,
marca, modelo e ano do veículo estão de acordo com a numeração do chassi.

***

## 2. Mensagens do Sistema Cadastrar Veículo

- ### MSG001:
Obrigatório informar a placa e o chassi do veículo. (**Erro**)

- ### MSG002:
Este veículo está perto da data de expirar seu cadastro. (**Alerta**)

- ### MSG003:
Obrigatório preencher o campo de captcha. (**Erro**)

- ### MSG004:
Veículo já cadastrado no sistema. (**Erro**)

- ### MSG005:
Veículo furtado! Contate imediatamente a polícia: 190. (**Alerta**)

- ### MSG006:
Você não tem permissão para cadastrar veículos. Contate o administrador do sistema. (**Erro**)

- ### MSG007:
Número de chassi inválido. (**Erro**)

- ### MSG008:
Você tem certeza de que os dados estão corretos? (**Confirmação**)


