# PaymentProcessor Tests

Este projeto demonstra o uso de Dummies, Stubs e Mocks em testes unitários com `NUnit` e `Moq` para a classe `PaymentProcessor`. O objetivo é ilustrar como cada técnica pode ser utilizada para isolar e testar diferentes aspectos de um sistema.

## Estrutura do Projeto

- **PaymentProcessor**: Classe principal que processa pagamentos, aplica descontos e envia notificações.
- **INotificationService** e **IDiscountService**: Interfaces para serviços de notificação e desconto.
- **Order**: Classe que representa um pedido.
- **Tests**: Contém os testes unitários utilizando Dummies, Stubs e Mocks.

## Tecnologias Utilizadas

- **C#**: Linguagem de programação.
- **NUnit**: Framework de testes unitários.
- **Moq**: Biblioteca para criação de Mocks.
