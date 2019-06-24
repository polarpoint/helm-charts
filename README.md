# helm-charts

Create a helm chart repo in github



$ In the repository containing the Helm chart
$ helm package .
Successfully packaged chart and saved it to: /Users/surjitbains/Documents/git/SCM/polarpoint/thanos-helm-chart/thanos/thanos-0.5.1.tgz
$ copy it here . 
$ helm repo index . # create or update the index.yaml for repo
$ git add .
$ git commit -m 'Added Thanos Helm Chart'
$ git push
