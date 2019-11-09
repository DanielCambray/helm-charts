


https://danielcambray.github.io/helm-charts

## Add chart

helm repo index --url https://danielcambray.github.io/helm-charts .

## Merge new chart 

helm repo index --url https://danielcambray.github.io/helm-charts --merge index.yaml .



## Add helm repo

helm repo add myhelmrepo  https://danielcambray.github.io/helm-charts/