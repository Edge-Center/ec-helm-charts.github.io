# EdgeCenter Helm Charts

Публичный репозиторий Helm-чартов для EdgeCenter.

## Установка

```bash
helm repo add edgecenter https://edge-center.github.io/ec-helm-charts.github.io/
helm repo update
```

## Доступные чарты 
ec-csi 

### EdgeCenter CSI Driver для интеграции с облачным хранилищем. 

```bash
helm install csi edgecenter/ec-csi
```

### ec-ccm 

EdgeCenter Cloud Controller Manager для управления облачной инфраструктурой. 

```bash
helm install ccm edgecenter/ec-ccm
```