# helm-charts

## Configuration

Add the chart repository.

``` bash
helm repo add azs-ecs https://raw.githubusercontent.com/msazurestackworkloads/helm-charts/master/repo/
```

## Chart source

All chart source material including chart readme files are found under the [src directory](/src/).

## Updating charts

``` bash
helm package src/CHART_NAME -d repo/
make index
```
