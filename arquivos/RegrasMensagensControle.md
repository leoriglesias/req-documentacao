# Especificações de Regras de Negócio e Mensagens do Sistema 

## 1. Regras de Negócio Controle de Vagas

- ### RNG000 
(Depois excluimos esta mensagem. Serve apenas como modelo.)  

- ### RNG001 
Deve existir gráficos mostrando quantos carros há no estacionamento.

- ### RNG002 
Gráficos exibindo o número de marcas e modelos de carros.

- ### RNG003 
O sistema deve, a partir da Regra de Negócio 2, gerar um gráfico com porcentagens dos valores dos veículos de acordo com tabela FIPE.

- ### RNG004 
Deve apresentar um mapa com as vagas disponíveis organizados por fileiras de A-Z e vagas de 1-n. 
Exemplo: O veículo Marca Modelo placa XXX-1234 está fileira K vaga número 3 (K-3).

- ### RNG005 
O sistema deve possuir uma espécie de sinaleira na parte superior indicando: luz verde (de 70% a 100% de vagas disponíveis),
luz amarela (de 30% a 69% de vagas disponíveis), luz vermelha (29% a 1% de vagas disponíveis).

- ### RNG006 
Gráficos exibindo o valor bruto obtido durante o dia, semana e mês.

- ### RNG007
Deve exibir uma mensagem exibindo que a meta de valor bruto obtido no dia foi alcançada.

***

## 2. Mensagens do Sistema Controle de Vagas

- ### MSG000:
(Depois excluimos esta mensagem. Serve apenas como modelo.)  
Mensagem a ser apresentada ao usuário (Selecione **Confirmação, Erro, Notificação ou Alerta.**]  

- ### MSG001:
Sinal Verde: O estacionamento está com bastante vagas disponíveis. (**Notificação**)

- ### MSG002:
Sinal Amarelo: O estacionamento está parcialmente lotado. (**Notificação**)

- ### MSG003:
Sinal Vermelho: O estacionamento está com poucas vagas. (**Notificação**)

- ### MSG004:
A meta de valor bruto definida no sistema foi atingida. (**Notificação**)

- ### MSG005:
A as fileiras que estão mais vazias são... (**Notificação**)
Exemplo: A as fileiras que estão mais vazias são A(12), D(7), B(4). 

- ### MSG006:
Não há vagas disponíveis! (**Alerta**)



