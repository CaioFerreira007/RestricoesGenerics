# RestricoesGenerics
Projeto: Restrições com Generics em C#
Este projeto demonstra o uso de Generics com restrições (constraints) em C#, aplicando conceitos de programação orientada a objetos e interfaces para encontrar o maior elemento de uma lista genérica.
📌 Objetivo
O programa lê uma lista de produtos (nome e preço) inseridos pelo usuário e determina qual produto tem o maior preço, utilizando uma classe de serviço genérica com restrição where T : IComparable.

RestriçõesGenerics/
│
├── Program.cs
├── Entities/
│   └── Product.cs
└── Services/
    └── CalculationService.cs
