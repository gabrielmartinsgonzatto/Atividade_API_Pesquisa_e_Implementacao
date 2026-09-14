# Gerador de Conselhos - Advice Slip API

1. **Qual API você usou:**  
Advice Slip JSON API (https://api.adviceslip.com).

2. **O que ela devolve:**  
Devolve um objeto JSON contendo um ID e uma frase com um conselho aleatório em inglês.

3. **O endereço que você chamou:**  
`https://api.adviceslip.com/advice`

4. **Como rodar:**  
Basta abrir o arquivo `index.html` diretamente em qualquer navegador de sua preferência, sem a necessidade de um servidor web ou instalação de dependências.

5. **Um print da tela funcionando:**  
![Print da Aplicação](./print-tela.png)

6. **Uma dificuldade que você teve:**  
A API por padrão faz cache da resposta e repetia o mesmo conselho em cliques seguidos. Resolvi o problema adicionando um parâmetro dinâmico com a hora atual na URL para forçar novas requisições.
