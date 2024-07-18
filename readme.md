<h1 align="center">
  💻 Analisando Dados com Python
</h1>

Neste repositório você encontrará as informações do meu projeto📦 que elaborei em conjunto da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/curso-python/curso-online-python-validacao-dados), para reforçar os conhecimentos da aula de automação com python.

## Case - Cancelamento de Clientes

Fui contratado por uma empresa com mais de 800 mil clientes para um projeto de Dados. Recentemente a empresa percebeu que da sua base total de clientes, a maioria são clientes inativos, ou seja, que já cancelaram o serviço.

Precisando melhorar seus resultados ela quer conseguir entender os principais motivos desses cancelamentos e quais as ações mais eficientes para reduzir esse número.
 
### Em qualquer projeto, inicialmente precisamos planejar as etapas que iremos seguir, para facilitar o processo e otimizar nosso tempo.

Segue abaixo o passo a passo para análise de dados:
* Passo 1: Importar a base de dados (utilização de uma biblioteca)
* Passo 2: Visualizar a base de dados
  - Encontrar as cagadas da base de dados
  - Verificar Colunas inúteis (informações que não te ajuda, te atrapalha)
* Passo 3: Tratamento de dados (corrigir as cagadas da base de dados)
  - Informações no formato errado - (string or number)
* Passo 4: Análise inicial dos cancelamentos
* Passo 5: Análise de causas dos cancelamentos dos clientes
* Passo 6: resultado e sugestão da resolução dos cancelamentos
  - Filtrar a base de dados
 
      
OBS: Ao enviar todo os arquivos desse projeto, acabou excedendo o limite de tamanho de arquivo definido pelo GitHub. O GitHub impõe um limite de tamanho de arquivo de 100 MB para repositórios Git.

    Para resolver esse problema, usei o Git LFS (Git Large File Storage):  
    O Git LFS é uma extensão do Git que permite armazenar 
    arquivos grandes em servidores externos, como o próprio Git LFS ou serviços de armazenamento em nuvem. 

    Vou fornecer um exemplo de como foi usado o Git LFS para a pasta nesse projeto

Foi configurando o Git LFS para rastrear os arquivos na pasta " AnalisandodadoscomPython.ipynb" e armazená-los externamente. 

    //Inicializar o Git LFS
    git lfs install 

    //Rastrear a pasta "AnalisandodadoscomPython.ipynb" 
    git lfs track "AnalisandodadoscomPython.ipynb/*" 

  
**🚀Tecnologias:**
- [Python](https://developer.mozilla.org/pt-BR/docs/Glossary/Python)
- [Pandas](https://pandas.pydata.org/docs/getting_started/index.html)
- [openpyxl](https://pypi.org/project/openpyxl/)
- [numpy](https://numpy.org/doc/stable/)
- [plotly](https://plotly.com/python/)
- [ipykernel](https://pypi.org/project/ipykernel/)
- [Jupyter|nbformat](https://nbformat.readthedocs.io/en/latest/)
