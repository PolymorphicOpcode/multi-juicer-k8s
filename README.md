# OWASP Juice Shop Scalable Kubernetes Clusters (Multi-Juicer)
## For Educational & Training Competitions
![cybersecurity association logo](https://raw.githubusercontent.com/BYUI-CSA/byui-csa.github.io/main/assets/images/logo.svg)

### Implemented by Brigham Young University - Idaho's Cyber Security Association for college-wide "Web Application Security Hackathon"

```git clone https://github.com/iteratec/multi-juicer```

```helm repo add multi-juicer https://iteratec.github.io/multi-juicer/```

```helm install multi-juicer multi-juicer/multi-juicer```

```helm install -f values.yaml multi-juicer ./multi-juicer/helm/multi-juicer/```

Set Up Load Balancer Service (To Expose our Balancer Server)

```https://raw.githubusercontent.com/iteratec/multi-juicer/master/guides/k8s/k8s-juice-service.yaml```

```kubectl apply -f k8s-juice-service.yaml```


### Deinstallation

```helm delete multi-juicer```


## References

[https://github.com/iteratec/multi-juicer](https://github.com/iteratec/multi-juicer)
[https://github.com/iteratec/multi-juicer/blob/master/guides/k8s/k8s.md](https://github.com/iteratec/multi-juicer/blob/master/guides/k8s/k8s.md)
