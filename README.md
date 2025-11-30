# 💻 Projeto de Programação Orientada a Objetos (POO) em Java - FATEC São Caetano do Sul

Este repositório contém implementações em Java de exercícios práticos da disciplina de Programação Orientada a Objetos (POO) da FATEC São Caetano do Sul. O objetivo é aplicar e demonstrar os pilares e conceitos fundamentais de POO, incluindo herança, agregação, composição, encapsulamento e o uso de coleções.

---

## 📚 Conceitos Abordados

Os exercícios implementados cobrem os seguintes tópicos:

### 1. Herança e Polimorfismo

**Tema:** Implementação de um sistema simples de produtos para farmácia.

- **Classe Base:** `Produto`
- **Subclasses:** `Medicamento` e `Higiene` (herdam de `Produto`)
- **Polimorfismo:** Sobrescrita do método `aumento(valor: float): void` na classe `Medicamento`, onde o cálculo de aumento é diferente (valor informado + 10% sobre o resultado).
- **Requisito:** Instanciar 1 objeto `Medicamento` e 1 objeto `Higiene` no método `main()`, com entrada de dados via teclado.

### 2. Agregação e Composição

**Tema:** Modelagem de um sistema de consoles e jogos.

- **Composição:** A classe `Console` possui um `Fabricante` (parte essencial do console).
- **Agregação:** A classe `Console` pode ter vários `Jogos` (relacionamento opcional).
- **Encapsulamento:** Uso de getters, setters e métodos construtores.
- **Método `dados()`:** Exibe todas as informações do `Console` e do seu `Fabricante`.
- **Requisito:** Entrada de dados manual utilizando a classe `Scanner`.

### 3. Coleções e Tipos Genéricos (Generics)

**Tema:** Gerenciamento de veículos de um proprietário.

- **Coleção `Set`:** Utilizada para armazenar os objetos `Veiculo` dentro da classe `Proprietario`, garantindo que não haja veículos duplicados.
- **Generics:** Uso de tipagem genérica para a coleção de veículos.

**Métodos Específicos:**

- `addVeiculo()`: Adiciona veículos, solicitando confirmação do usuário (via `JOptionPane`) caso a coleção ultrapasse 5 veículos.
- `valorBens()`: Calcula o valor total dos veículos, utilizando `for-each`.
- `removeVeiculo()`: Remove um veículo da coleção pela placa.
- **Requisito:** Demonstração final com 6 veículos, listando-os (usando `foreach` e expressão lambda) e exibindo o total de bens.

---

## 🚀 Tecnologias e Ferramentas

- **Linguagem de Programação:** Java
- **Conceitos:** Programação Orientada a Objetos (POO)
- **Ferramentas de Entrada/Saída:** `Scanner` (console) e `JOptionPane` (interface gráfica)
- **Estruturas de Dados:** `Set` (Coleções)

---
