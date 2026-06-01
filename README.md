# README
## Praticando Java: Challenge conversor de moedas
### ALURA-ONE ORACLE NEXT EDUCATION
### Especialização Back-End

#### Conversor de Moedas
Bem-vindo ao Conversor de Moedas! Este projeto foi desenvolvido por *Daiane* como parte do desafio "Praticando Java" oferecido pela Oracle e Alura. Desenvolvido em Java, este conversor obtém taxas de câmbio em tempo real de uma API e oferece um menu interativo para várias opções de conversão de moedas.

#### Funcionalidades
* Consumo de uma API de taxas de câmbio em tempo real.
* Análise e manipulação de dados JSON.
* Filtro e exibição de moedas de interesse.
* Menu interativo com 6 opções de conversões de moedas.
* Exibição das taxas de câmbio disponíveis.
* Conversão de valores entre diferentes moedas.

#### API Utilizada
Este projeto utiliza a ExchangeRate-API para obter taxas de câmbio em tempo real. A API fornece informações precisas e atualizadas sobre as taxas de câmbio de várias moedas, facilitando a conversão de valores.

#### Estrutura do Projeto
O projeto está dividido nas seguintes classes principais:
* **Main:** Gerencia a interação inicial com o usuário, exibe o menu e executa a lógica de conversão.
* **ApiRequest:** Responsável por fazer as requisições HTTP à API de taxas de câmbio e retornar os dados em JSON.
* **CurrencyConverter:** Realiza a conversão entre moedas usando as taxas de câmbio obtidas.
* **ApiResponse:** Modela a resposta da API, facilitando a extração de dados relevantes.

#### Como Executar o Projeto
1. **Configuração do Ambiente Java:** Certifique-se de ter o Java configurado em sua máquina.
2. **Criação do Projeto:** Clone este repositório e importe o projeto para sua IDE.
3. **Consumo da API:** A classe ApiRequest já está configurada para fazer as requisições necessárias.
4. **Análise e Filtro de Moedas:** As moedas são filtradas e exibidas no menu interativo para facilitar a seleção.
5. **Exibição de Resultados:** A taxa de câmbio e o valor convertido são exibidos ao usuário.

---
**Desenvolvedora**
Daiane M. Horbach
