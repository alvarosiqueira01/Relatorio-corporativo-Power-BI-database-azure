# Relatorio-corporativo-Power-BI-database-azure
Desafio de projeto "Criando um Dashboard corporativo com integração com MySQL e Azure" do curso "Processamento de dados com Power BI" da DIO.

Relatório criado a partir de banco de dados SQL remotamente hospedado na Azure, cuja criação se deu segundo os documento .sql aí colocados. Tais documentos foram fornecidos em: https://github.com/julianazanelatto/power_bi_analyst/tree/main/M%C3%B3dulo%203/Desafio%20de%20Projeto.

Criado o banco de dados, foi feita a transformação dos dados com o Power Query, seguindo o passo a passo do desafio:

"1. Verifique os cabeçalhos e tipos de dados

2. Modifique os valores monetários para o tipo double preciso

3. Verifique a existência dos nulos e analise a remoção

4. Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente

5. Verifique se há algum departamento sem gerente

6. Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas

7. Verifique o número de horas dos projetos

8. Separar colunas complexas

9. Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção

10. Neste processo elimine as colunas desnecessárias.

11. Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.

12. Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores

13. Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.

14. Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.

15. Agrupe os dados a fim de saber quantos colaboradores existem por gerente

16. Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela

Assim, aplicando a visualização gráfica do Power BI a alguns dados, o relatório culminou em:

Página 01:
<img src="Captura de tela 2024-06-18 202008.png">


Página 02:
<img src="Captura de tela 2024-06-18 202019.png">
