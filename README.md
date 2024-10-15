# Análise de Atrito de Funcionários da IBM

## Introdução

Este projeto utiliza dados do RH da IBM, disponibilizados no site [Kaggle](https://www.kaggle.com), para analisar o perfil de funcionários que deixam a empresa. O objetivo é entender os fatores que contribuem para o atrito, visando prevenir demissões, reduzir custos e aumentar a satisfação dos empregados.

## Insights da Análise

- A maioria dos funcionários está entre 25 e 45 anos.
- Muitos funcionários recebem um salário base, o que pode gerar insatisfação e aumentar o número de demissões.
- Funcionários com salário de até R$ 5.000 apresentam um maior nível de atrito.
- O número de demissões é mais alto na faixa etária de 20 a 30 anos.
- A maior parte dos desligamentos ocorre entre os que estão há pouco tempo na organização e recebem salários baixos.

## Recomendações

Para melhorar a retenção de funcionários, recomenda-se:

- Implementar programas de integração e desenvolvimento profissional para novos funcionários.
- Realizar análises salariais regulares para garantir equidade de remuneração, especialmente entre os jovens.

## Estrutura do Projeto

1. **Carregamento de Bibliotecas**
   - `pandas`, `numpy`, `seaborn`, `matplotlib`.

2. **Carregamento do Dataset**
   - Importação e visualização inicial dos dados.

3. **Análise Univariada**
   - Análise da idade, salários e outras variáveis.

4. **Análise Bivariada**
   - Exploração de relações entre diferentes variáveis e o atrito.

## Conclusão

A análise revelou correlações significativas entre idade, tempo na empresa e salário com o atrito de funcionários. A adoção de estratégias para aumentar a satisfação e retenção é fundamental.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

