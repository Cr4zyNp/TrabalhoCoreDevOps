# TrabalhoCoreDevOps
Trabalho de DevOps utilizando o GitHub Actions e o Azure Web App (Conta FIAP).

Existe um workflow criado para a branch de dev e outro para a master.

Após ação na branch os passos do WorkFolow são executados:
 
 - Projeto .Net C# é Buildado dentro do GitHub 
 - Roda Unit Test (Se existir)
 - É Criado um artefato 
 - Verificação de código utilizando o SonarCloud
 - Deploy no Azure Web App com url especifica para cada Branch utilizando o artefato criado
    - Master 
      - https://trabalhodevops15dvp.azurewebsites.net 
    - dev 
      - https://trabalhodevops15dvp-dev.azurewebsites.net
 
