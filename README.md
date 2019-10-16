# PIBIC UFPB
Repositório do projeto de iniciação científica da UFPB que visa analisar quantitativamente e qualitativamente os clusters de empresas presentes no território Paraibano.


# DADOS
Os dados das empresas foram coletrados manualmente pelos integrantes do projeto, utilizando a plataforma [Resultys]"https://resultys.com.br" como fonte. Estes dados foram retirados da Receita Federal do Brasil e disponibilizados de forma paga pela Resultys. O CSV contido neste repositório contempla todas as empresas de PEQUENO PORTE até GRANDE PORTE, de todos os segmentos e mercados, presentes no Estado da Paraíba.

# TRATAMENTO DOS DADOS
Na coleta, foi utilizado o GOOGLE DOCS para armazenar os dados e, posteriormente, foram tratados utilizando o Jupyter Notebook, juntamente com Python, Pandas e Numpy.

# ANÁLISE DOS DADOS
Como o objetivo do projeto é encontrar clusters de empresas, a primeira ideia era utilizar o algoritmo de clusterização K-MEANS para ajudar neste processo. Mas, todos os dados coletados são variáveis categóricas, logo, a utilização do K-MEANS é comprometida.
Neste caso, utilizei o algoritmo de clusterização K-MODES, que funciona perfeitamente com variáveis categóricas e atendeu muito bem ao objetivo do projeto. 
Próximo passo, será encontrar uma maneira de padronizar o resultado do K-MODES para que sempre que chamemos a função de clusterização com os mesmos parâmetros e dados, ele retorne o mesmo resultado, pois atualmente, a cada chamada nova da função o algoritmo retorna um resultado diferente.

# VISUALIZAÇÃO DOS DADOS
O resultado da análise ainda está em andamento, mas pretendo utilizar o TABLEAU DESKTOP para visualizar os dados mais amigavelmente.
