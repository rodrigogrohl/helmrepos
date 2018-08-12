# helm-repos

## Add a new Chart or Version
```
$ helm package $YOUR_CHART_PATH/ # build the tgz file and copy it here
$ helm repo index . # create or update the index.yaml for repo
$ git add .
$ git commit -m 'New chart version'
```  

## Use this repos

```
$ helm repo add sample 'https://raw.githubusercontent.com/kmzfs/helm-repo-in-github/master/'
$ helm repo update
$ helm search questcode
```
Or use token:  
`helm repo add sample 'https://MY_PRIVATE_TOKEN@rodrigogrohl/repos/master'

