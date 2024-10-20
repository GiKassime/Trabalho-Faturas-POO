# Atividades-2-Ano-IFPR
2- As concessionárias de energia calculam a fatura de luz com base no tipo de consumidor. 
De acordo com seu papel na sociedade, o custo do KWh é diferente. Neste sentido, 
implemente um programa com uma interface IConsumidorEnergia que definirá o método 
getValorFatura(). Após, declare as classes representando os tipos de consumidores para 
implementar a interface IConsumidorEnergia:
–Residencial: deve cobrar R$ 1,05 por KWh consumido.
–Comercial: deve cobrar R$ 1,45 por KWh consumido até 100 KWh, e R$ 1,60 ao que 
exceder 100 Kwh.
–Industrial: deve cobrar R$ 1,80 por Kwh consumido até 500 KWh e R$ 2,30 ao que 
exceder 500 KWh.
Todas as classes devem possuir um atributo denominado consumo.
Por fim, o programa a ser executado deve:
–Criar um objeto de uma das 3 classes para calcular o valor da fatura de energia. O tipo de 
consumidor deve ser lido para criar o objeto da classe correspondente;
–Ler o atributo consumo;
–Exibir o resultado do método getValorFatura().