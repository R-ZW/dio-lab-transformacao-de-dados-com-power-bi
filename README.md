# Extração e transformação de dados com Power BI

***
### Disclaimer: Aviso de limitação de projeto
Este projeto foi desenvolvido sob certas limitações impostas por restrições externas. Lamento informar que não foi possível seguir a proposta original do projeto devido à incapacidade de criar uma conta na plataforma Azure. Esta limitação surgiu devido à ausência de um cartão de crédito válido para a criação da mesma.

Como solução alternativa, o projeto foi adaptado para utilizar um banco de dados MySQL hospedado localmente. Embora essa mudança possa afetar algumas funcionalidades e recursos previstos inicialmente, fiz o melhor possível para manter a integridade e a eficiência do projeto dentro das novas circunstâncias.

Agradeço sua compreensão e estou disponível para esclarecer qualquer dúvida ou fornecer informações adicionais sobre as adaptações realizadas.


***
### Sobre o repositório

Repositório de resolução da atividade de extração e transformação de dados e criação de relatório com Power BI. O repositório conta com duas pastas, a *db_config* e *docs*. A primeira conta com os arquivos de configuração da base de dados e a outra com a resolução da atividade.

A pasta *docs* com um arquivo ".pbit" que pode ser aberto com o Power BI e um ".pdf" para ser acessado nativamente. Além disso, há também o **parecer de resolução da atividade**, constando desde a criação do banco e a transformação dos dados (com todos os 16 passos de resolução descritos com imagens [e a resposta da questão 14, que também está contida nesse readme]).


***
### Resolução da questão 14
Quando se mescla os nomes de departamentos e localizações, cria-se uma relação entre as duas tabelas com base em uma coluna comum, como um identificador único para cada departamento e localização. Isso garante que cada combinação departamento-local seja única, pois estará associada a um único registro na tabela resultante da mesclagem. Além de que, mesclar as tabelas de departamentos e localizações permite manter os relacionamentos entre elas. Enquanto a operação de atribuir valores geralmente é utilizada para adicionar uma coluna com valores estáticos a uma tabela existente. No entanto, se tentássemos apenas atribuir valores para os nomes de departamentos e localizações, perderíamos informações importantes, como os relacionamentos entre os departamentos e suas respectivas localizações.
***

### Versão final do Relatório
![image](https://github.com/R-ZW/dio-lab-transformacao-de-dados-com-power-bi/assets/102392654/0b7dd3c0-85b0-41be-82df-e8ed743ab0d7)
