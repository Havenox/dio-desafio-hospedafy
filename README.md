# 🏨 Hospedafy

Um sistema de gerenciamento de hospedagens desenvolvido em **C# .NET**, como parte de um desafio da [DIO](https://dio.me/users/eduardonascto). O projeto simula o processo de reservas em um hotel, relacionando hóspedes, suítes e reservas.

---

## 📖 Descrição

O **Hospedafy** foi projetado para administrar reservas em um hotel. Ele permite:

* Cadastrar **hóspedes**.
* Cadastrar **suítes** disponíveis.
* Realizar **reservas** associando hóspedes a uma suíte.
* Validar se a suíte comporta a quantidade de hóspedes.
* Calcular corretamente o **valor da diária**, incluindo desconto de 10% para estadias de 10 dias ou mais.

Este projeto **não foi construído do zero**. Diferente de outros trabalhos, aqui eu apliquei as instruções do professor e completei o código já existente, implementando os trechos sinalizados com **TODO**. Essa prática foi essencial para aprimorar minha habilidade de **compreender e contribuir em projetos em andamento**, algo comum em equipes de desenvolvimento reais.

---

## ⚙️ Funcionalidades

* **Cadastrar hóspede**: registra o nome do cliente.
* **Cadastrar suíte**: define nome, capacidade e valor da diária.
* **Realizar reserva**: relaciona hóspedes e suíte, verificando regras de capacidade.
* **Obter quantidade de hóspedes**: retorna o número de pessoas incluídas na reserva.
* **Calcular valor da diária**:

  * Multiplica o valor da diária pelo número de dias.
  * Aplica **10% de desconto** em estadias com duração igual ou superior a 10 dias.

---

## 🛠️ Estrutura do Projeto

* **Pessoa.cs** → representa o hóspede.
* **Suite.cs** → representa a suíte do hotel.
* **Reserva.cs** → administra a lógica da reserva (hóspedes, quantidade, valores).
* **Program.cs** → fluxo principal para executar e testar as funcionalidades.

---

## 🚀 Tecnologias Utilizadas

* Linguagem: **C#**
* Plataforma: **.NET 6+**
* Paradigma: **Programação Orientada a Objetos (POO)**

---

## 📂 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/Havenox/dio-desafio-hospedafy.git
```

2. Acesse a pasta do projeto:

```bash
cd dio-desafio-hospedafy
```

3. Compile e execute:

```bash
dotnet run
```
---

## 🎯 Objetivos Atingidos

* Compreender e aplicar **POO em C#**.
* Exercitar **relacionamento entre classes** (Pessoa, Suíte, Reserva).
* Aprender a **lidar com código parcialmente pronto**.
* Praticar a leitura, entendimento e implementação de **trechos de código marcados como TODO**.
* Desenvolver a habilidade de **contribuir em projetos em andamento**, como ocorre no mercado de trabalho.

---

## 📌 Autor

👤 **[Eduardo Nascimento](https://www.instagram.com/eduardohavenox/)**
🔗 [GitHub](https://github.com/Havenox)
💼 [LinkedIn](https://www.linkedin.com/in/havenox)
🎓 [DIO](https://dio.me/users/eduardonascto)

---

## 🙏 Agradecimentos

Agradeço à DIO pela proposta do desafio e ao professor Leonardo Buta, pelas aulas que guiaram a prática e reforçaram a importância de saber **trabalhar em código já existente**.

---

## 🏆 Considerações

Este projeto marca uma evolução importante: além de aplicar os conceitos de C#, foi uma oportunidade de aprender a **dar continuidade a um código-base**, habilidade indispensável para desenvolvedores em projetos reais. O **Hospedafy** simboliza esse aprendizado prático e direto.
