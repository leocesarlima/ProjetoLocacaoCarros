# Projeto para Locacao de Carros

Projeto básico de iniciativa para estudos de uma equipe de QA's.

# [Ferramentas e Tecnologias]:
_Windows 10;
_Visual Studio 2017;
_C#;

# [Conceitos/Metodologias]:
_TDD;
_BDD:

# [Frameworks]:
_.NET Core 2.0;
_XUnit 3.0;

# [Escopo do Projeto]:

Preciso de uma aplicação para controlar o aluguel de carros da minha empresa.

Dados importantes:
- Placa do carro
- Tem ar? Sim ou Nao
- Ano do carro
- Marca do carro
- Quantidade de portas
- Para alugar um carro eu preciso do Cpf, Nome, Data nascimento, Fumante (s/n) e Sexo do locatário
- Para alugar um carro eu preciso da Data de entrada, Data de saída e o numero da placa do carro escolhido
- A locação para mulher sai com 20% de desconto
- A locação por mais de 10 dias sai por 30% de desconto
- Valor da diária para carro 2 portas sem ar: R$ 100,00
- Valor da diária para carro 2 portas com ar: R$ 120,00
- Valor da diária para carro 4 portas sem ar: R$ 160,00
- Valor da diária para carr0 4 portas com ar: R$ 180,00

# [Diagrama de Classe UML]:
- CARRO                        
_ placa (PK);
_ temArCond (s/n);
_ ano;
_ marca;
_ qtePortas;

- LOCACAO       
_ dataEntrada;
_ dataSaida;
_ cpf (FK);
_ placa (PF);

- PESSOA        
_ cpf (PK);
_ nome;
_ dataNasc;
_ fumante (s/n);
_ sexo (masc/fem);
