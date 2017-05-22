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
Realizar fechamento de caixa com histórico de vagas. 

- ### RNG15
Necessário estar logado no sistema para cadastrar veículos. 

***

## 2. Mensagens do Sistema Controle de Vagas 

- ### MSG01:
Sinal Verde: vaga disponível. (**Notificação**)

- ### MSG02:
Sinal Vermelho: Vaga ocupada. (**Notificação**)

- ### MSG03:
A meta de valor bruto definida no sistema foi atingida. (**Notificação**)

- ### MSG04: 
Registro salvo!  (**Confirmação**)

- ### MSG05:
Vaga Liberada! (**Notificação**)

- ### MSG06:
Vaga ocupada! (**Alerta**)

- ### MSG07:
Veiculo nao encontrado! (**Alerta**)

- ### MSG08:
Cliente não encontrado! (**Alerta**)

- ### MSG09:
Não há vagas! (**Erro**)

- ### MSG10:
A as fileiras que estão mais vazias são... (**Notificação**)
Exemplo: A as fileiras que estão mais vazias são A(12), D(7), B(4). 

- ### MSG11:
Não há vagas disponíveis! (**Alerta**)

- ### MSG12:
Veículo guinchado! (**Alerta**)

- ### MSG13:
Veículo ultrapassou tempo limite! (**Notificação**)

