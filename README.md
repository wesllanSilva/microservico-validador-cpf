"# microservico-validador-cpf" 

VS code
CTRL + SHIFT + p
- CREATE azure functions no AZURE
- Escolher nome global ex: fnwstackapp002
- Escolher tecnologia ex: .Net 8

## Criar Artefatos da Funciton.

- Criar uma diretório ex: httpValidaCpf
- Dentro da diretório 'httpValidaCpf' adicione o runtime 
    func init --worker-runtime dotnet
- Criar Função 
    func new
- Escolher opção httptrigger e dar nome ex: fnvalidacpf
- Iniciar função
    func start


 - Antes de publicar verificar "local.settings.json' e alterar a "FUNCTIONS_WORKER_RUNTIME" para "dotnetIsoloated"
 - publicar no Azure
  func azure functionapp publish fnwstackappdev002 