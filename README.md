# BDD

# Funcionalidade: Sistema de Locação de Carros
  Como um cliente
  Eu quero alugar um carro
  Para que eu possa viajar

# Cenário: Reserva antecipada de um carro de luxo
  Dado que o cliente deseja alugar um carro de luxo
  E o cliente realiza a reserva com antecedência de pelo menos uma semana
  Quando o sistema processa a reserva
  Então o sistema deve oferecer um desconto especial no valor total da locação

# Cenário: Locação de última hora de um carro utilitário
  Dado que o cliente necessita alugar um carro utilitário de última hora
  E o cliente não tem qualquer reserva prévia
  Quando o sistema processa a locação
  Então o sistema deve encontrar um veículo disponível
  E o sistema deve processar a locação rapidamente
  E o sistema deve informar que o custo é um pouco mais elevado devido à demanda urgente
