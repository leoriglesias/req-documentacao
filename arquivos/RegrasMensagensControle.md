# Especificações de Regras de Negócio e Mensagens do Sistema 

## 1. Regras de Negócio Controle de Vagas

- ### RNG01
Obrigatório informar a placa do veiculo.  

- ### RNG02 
Obrigatório informar a CPF do cliente.  

- ### RNG03 
Obrigatório selecionar o tipo de vaga.  

- ### RNG04
Sistema deve listar vagas e a opção de mapa com as vagas organizados por fileiras de A-Z e vagas de 1-n. 
Exemplo: O veículo Marca Modelo placa XXX-1234 está fileira K vaga número 3 (K-3).

- ### RNG05 
O sistema deve possuir uma espécie de sinaleira na parte superior da vaga indicando luz verde - vaga livre - e luz vermelha - vaga ocupada.

- ### RNG06
Sistema deve manter histórico de vagas.

- ### RNG07
Deve exibir uma mensagem mostrando que a meta do dia foi obtida.

- ### RNG08
Ao selecionar uma vaga, o sistema deverá emitir um ticket para controle de pagamento.

- ### RNG09
Caso veículo permaneça por mais de 24Hrs no estabelecimento estará sujeito a multa. 

- ### RNG10
Necessário estar logado no sistema para cadastrar veículos. 

- ### RNG11
Informar saida do veículo. 

- ### RNG12
Caso veículo permaneça por mais de 48Hrs no estabelecimento estará sujeito a guincho. 

- ### RNG13
O sistema deverá informar quando todas as vagas estiverem ocupadas. 

- ### RNG14
Necessário estar logado no sistema para cadastrar veículos. 

- ### RNG15
Necessário estar logado no sistema para cadastrar veículos. 

***

## 2. Mensagens do Sistema Controle de Vagas 

- ### MSG001:
Sinal Verde: vaga disponível. (**Notificação**)

- ### MSG002:
Sinal Vermelho: Vaga ocupada. (**Notificação**)

- ### MSG003:
A meta de valor bruto definida no sistema foi atingida. (**Notificação**)

- ### MSG004: 
Registro salvo!  (**Confirmação**)

- ### MSG005:
Vaga Liberada! (**Notificação**)

- ### MSG006:
Vaga ocupada! (**Alerta**)

- ### MSG007:
Veiculo nao encontrado! (**Alerta**)

- ### MSG008:
Cliente não encontrado! (**Alerta**)

- ### MSG009:
Não há vagas! (**Erro**)

- ### MSG0010:
A as fileiras que estão mais vazias são... (**Notificação**)
Exemplo: A as fileiras que estão mais vazias são A(12), D(7), B(4). 

- ### MSG0011:
Não há vagas disponíveis! (**Alerta**)



