Este código é um programa em C# que simula um sistema de gerenciamento de estacionamento. Abaixo está uma descrição detalhada de suas funcionalidades:

Configuração Inicial:

1 - Define a codificação de saída do console como UTF-8 para garantir a exibição correta de caracteres acentuados.
Solicita ao usuário que insira o preço inicial do estacionamento e o preço por hora, convertendo as entradas para valores decimais.
Instanciação da Classe Estacionamento:

2 - Cria uma instância da classe Estacionamento passando o preço inicial e o preço por hora obtidos do usuário.
Loop do Menu:

3 - Exibe um menu no console com as opções: cadastrar veículo, remover veículo, listar veículos e encerrar.
O menu é exibido em um loop while que continua até que o usuário escolha encerrar (opção 4).
Operações de Estacionamento:

4- Dependendo da escolha do usuário, chama os métodos apropriados na instância de Estacionamento:
AdicionarVeiculo(): Provavelmente cadastra um novo veículo no estacionamento.
RemoverVeiculo(): Provavelmente remove um veículo do estacionamento.
ListarVeiculos(): Provavelmente lista todos os veículos atualmente no estacionamento.
Exibe uma mensagem de erro se a opção escolhida for inválida.
Encerramento do Programa:

5 - Quando o usuário escolhe a opção 4, o loop é interrompido e o programa exibe uma mensagem informando que o programa se encerrou.
