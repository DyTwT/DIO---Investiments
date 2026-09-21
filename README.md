# 📈 Simulador de Investimentos Financeiros

Simulador de investimentos financeiros desenvolvido em **Excel** como parte de um desafio do bootcamp **Santander - Excel com IA e Claude**, promovido pela **DIO (Digital Innovation One)**.
O projeto foi desenvolvido com o apoio e orientação do especialista **Felipe Aguiar**, aplicando conceitos de Excel para criar uma ferramenta capaz de auxiliar o usuário na simulação de investimentos, projeção de patrimônio e análise de possíveis rendimentos.

---

## 🎯 Sobre o Projeto

O objetivo do projeto é criar uma ferramenta simples e interativa para ajudar o usuário a visualizar como seus investimentos podem evoluir ao longo do tempo.
O simulador permite inserir informações como:

* Salário;
* Rendimento mensal da carteira;
* Valor que deseja investir mensalmente;
* Período do investimento em anos;
* Taxa de rendimento mensal;
* Perfil de investidor.

A partir dessas informações, a planilha realiza os cálculos e apresenta uma projeção do **patrimônio acumulado** e dos **dividendos mensais**.
> **Importante:** Os resultados são projeções baseadas nos valores informados pelo usuário e não representam garantia de rentabilidade futura ou recomendação de investimento.

---

## 🧮 Funcionalidades

### 💰 Configuração financeira

O usuário informa seu salário e o rendimento esperado da carteira.
A planilha também calcula automaticamente uma **sugestão de investimento mensal equivalente a 30% do salário**, servindo como referência para o usuário.

### 📊 Simulação de investimentos

É possível definir:

* Quanto investir por mês;
* Por quantos anos realizar os aportes;
* Qual será a taxa de rendimento mensal.

Com esses dados, o simulador calcula o patrimônio que poderá ser acumulado ao final do período.

### 💵 Estimativa de dividendos

Após calcular o patrimônio acumulado, a planilha estima o valor dos **dividendos mensais**, utilizando o rendimento definido para a carteira.

### 📅 Cenários de longo prazo

O simulador apresenta diferentes cenários para facilitar a visualização da evolução dos investimentos.
São apresentados períodos de:

* 2 anos;
* 5 anos;
* 10 anos;
* 20 anos;
* 30 anos.

Para cada período, são demonstrados o patrimônio acumulado e a estimativa de dividendos mensais.

### 👤 Perfil do investidor

A planilha também permite selecionar um perfil de investidor:

* **Conservador**
* **Moderado**
* **Agressivo**

De acordo com o perfil selecionado, a distribuição percentual sugerida para diferentes tipos de **Fundos de Investimento Imobiliário (FIIs)** é alterada.

### 🏢 Distribuição entre tipos de FII

A planilha apresenta sugestões de distribuição percentual entre diferentes categorias de FIIs:

* Papel;
* Tijolo;
* Híbridos;
* FOFs;
* Desenvolvimento;
* Hotelarias.

Dessa forma, o usuário consegue visualizar uma possível composição de carteira de acordo com o perfil selecionado.

---

## 🛠️ Tecnologias e Recursos Utilizados

* **Microsoft Excel**
* Fórmulas financeiras do Excel
* Função `FV` para projeção do valor futuro
* Referências entre células e planilhas
* Organização de dados por perfil de investidor
* Tabelas de distribuição percentual
* Recursos de automação e organização de cálculos

---

## 📂 Estrutura da Planilha

O arquivo possui duas principais planilhas:

### `DIO - Investiments`

É a página principal do simulador, onde estão:

* Configurações;
* Salário;
* Rendimento da carteira;
* Sugestão de investimento;
* Investimento mensal;
* Período de investimento;
* Taxa de rendimento;
* Patrimônio acumulado;
* Dividendos mensais;
* Cenários de investimento;
* Perfil do investidor.

### `Perfis Porcentagem`

Contém a estrutura utilizada para definir a distribuição percentual dos diferentes tipos de FIIs de acordo com cada perfil:

| Perfil      | Tipos de FII                                                |
| ----------- | ----------------------------------------------------------- |
| Conservador | Papel, Tijolo, Híbridos, FOFs, Desenvolvimento e Hotelarias |
| Moderado    | Papel, Tijolo, Híbridos, FOFs, Desenvolvimento e Hotelarias |
| Agressivo   | Papel, Tijolo, Híbridos, FOFs, Desenvolvimento e Hotelarias |

Essa separação permite organizar os dados utilizados pelo simulador e facilitar a alteração das porcentagens.

---

## 📌 Exemplo de Funcionamento

O usuário pode informar, por exemplo:

**Salário:** R$ 3.500,00
**Investimento mensal:** R$ 560,00
**Período:** 5 anos
**Taxa de rendimento mensal:** 1,079%

A partir desses valores, o Excel utiliza os dados para projetar o patrimônio acumulado e calcular uma estimativa de dividendos mensais.
Também é possível comparar o resultado considerando períodos maiores, como 10, 20 ou 30 anos, permitindo visualizar o impacto dos aportes e dos juros compostos ao longo do tempo.

---

## 📚 Objetivos de Aprendizado

Este projeto teve como principais objetivos:

* Praticar a utilização do Excel para resolução de problemas;
* Aplicar fórmulas financeiras em uma situação prática;
* Trabalhar com projeções de longo prazo;
* Utilizar referências entre diferentes planilhas;
* Criar uma ferramenta interativa para entrada e análise de dados;
* Aplicar conceitos relacionados a investimentos e juros compostos;
* Desenvolver uma solução prática utilizando Excel como ferramenta de análise.

---

## 🎓 Bootcamp

Projeto desenvolvido como desafio do bootcamp:

**Santander - Excel com IA e Claude**
**Plataforma:** DIO — Digital Innovation One
**Especialista:** Felipe Aguiar

O desafio proporcionou a aplicação prática dos conhecimentos adquiridos durante o bootcamp, utilizando o Excel para desenvolver uma ferramenta de análise e simulação financeira.

---

## ⚠️ Aviso

Os valores apresentados pelo simulador são baseados nas informações inseridas pelo usuário e em premissas utilizadas nos cálculos da planilha. Rentabilidades reais podem variar devido às condições do mercado, taxas, impostos, inflação e outros fatores.
As informações apresentadas **não constituem recomendação ou orientação financeira**.

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**.
Você pode utilizar, estudar, modificar e distribuir o projeto, desde que mantenha os avisos de copyright e a licença original.
Para mais detalhes, consulte o arquivo [`LICENSE`](LICENSE) deste repositório.

---

## 👩‍💻 Autora

**Andressa Barreto**

Projeto desenvolvido durante o bootcamp **Santander - Excel com IA e Claude | DIO**.
