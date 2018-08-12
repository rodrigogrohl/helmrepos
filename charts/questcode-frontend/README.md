# QuestCode Helm

Iniciando um novo Chart:  
`helm create [chart-name]`  

Para instalar o frontend, aplique:  
`helm install . --namespace [namespace]`  

Listando releases:  
`helm ls`  

Checando Release:  
`helm status [release-name]`  

Excluindo release:  
`helm delete [release-name]`  

Rollback:  
`helm rollback [release-name] [release-version]`  

Purge, deleta todos resources e históricos:  
`helm delete --purge [release-name]`  

Debug, checando execução:  
`helm install . --dry-run --debug --set image.tag='0.1.2'`  


