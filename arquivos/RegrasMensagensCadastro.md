# Especificações de Regras de Negócio e Mensagens do Sistema  
  
## 1. Regras de Negócio Cadastrar Veículo  
  
- ### RNG01  
É obrigatório que seja informada a placa.  
  
- ### RNG02  
É permitido uma pessoa ter mais de um carro.  
  
- ### RNG03  
É permitido um carro ter mais de uma pessoa responsável, mas no máximo duas pessoas.  
  
- ### RNG04  
A cada 30 dias será necessário confirmar com o cliente se ele possui os mesmos veículos (pois a pessoa pode vender o carro e ficar 
cadastrado no sistema no nome de outra pessoa).  
  
- ### RNG05  
Ao cadastrar um veículo o sistema deve verificar no site do DENATRAN se o veículo é roubado e informar caso verdadeiro.  
  
- ### RNG06  
Caso o veículo seja roubado, o atendente deve acionar a policia.  
  
- ### RNG07  
Deve constar na ficha de cadastro qual funcionário do estabelecimento cadastrou o veículo.  
  
- ### RNG08  
Após o cadastro o sistema deve verificar junto ao site do DENATRAN se os dados informados são verdadeiros.  
  
- ### RNG09  


- ### RNG10  


- ### RNG11  


- ### RNG12  


- ### RNG13  


- ### RNG14  


- ### RNG15  


***  

## 2. Mensagens do Sistema Cadastrar Veículo  

- ### MSG01:  
Obrigatório informar a placa do veículo. (**Erro**)  
   
- ### MSG02:  
Este veículo está perto da data de expirar seu cadastro. (**Alerta**)  
  
- ### MSG03:  
Obrigatório preencher o campo de captcha. (**Erro**)  
  
- ### MSG04:  
Veículo já cadastrado no sistema. (**Erro**)  
  
- ### MSG05:  
Veículo furtado! Contate imediatamente a polícia: 190. (**Alerta**)  
  
- ### MSG06:  
Você não tem permissão para cadastrar veículos. Contate o administrador do sistema. (**Erro**)  
  
- ### MSG07:  
Número de chassi inválido. (**Erro**)  
  
- ### MSG08:  
Você tem certeza de que os dados estão corretos? (**Confirmação**)  
  
- ### MSG09:  
Número da placa inválido. Deve respeitar o padrão XXX-0000 (**Erro**)
  
- ### MSG10:  


