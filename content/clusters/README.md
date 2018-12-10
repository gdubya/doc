## Clusters

### Prod GKE
Production environment in GKE   
Istio enabled environment for applications that have implemented [Azure AD token flow](/content/authnz/)   
Token enabled applications in FSS are available from this cluster

| Domains                    | Purpose            |
| :------------------------- | :----------------- |
| *.prod-gke-int.nais.io     | Internal ingress   |
| *.prod-gke.nais.io         | Public ingress     |

### Prod FSS
Production environment in FSS   
For applications with sensitive information that need access to legacy systems in FSS

| Domains                    | Purpose            |
| :------------------------- | :----------------- |
| *.prod-fss.nais.io         | Internal ingress   |
| *.nais.adeo.no             | Legacy internal    |
| *.prod-fss-pub.nais.io     | Public ingress     |

### Prod SBS
Production environment in SBS   
For applications on nav.no

| Domains                    | Purpose            |
| :------------------------- | :----------------- |
| *.prod-sbs.nais.io         | Internal ingress   |
| *.nais.oera.no             | Legacy internal    |

### Dev GKE
Non-Production environment in GKE   
Istio enabled environment for applications that have implemented [Azure AD token flow](/content/authnz/)   
Token enabled applications in FSS are available from this cluster

| Domains                    | Purpose            |
| :------------------------- | :----------------- |
| *.dev-gke-int.nais.io      | Internal ingress   |
| *.dev-gke.nais.io          | Public ingress     |

### Dev FSS
Non-Production environment in FSS   

| Domains                    | Purpose            |
| :------------------------- | :----------------- |
| *.dev-fss.nais.io          | Internal ingress   |
| *.nais.preprod.local       | Legacy internal    |
| *.dev-fss-pub.nais.io      | Public ingress     |

### Dev SBS
Non-Production environment in SBS   

| Domains                    | Purpose            |
| :------------------------- | :----------------- |
| *.dev-sbs.nais.io          | Internal ingress   |
| *.nais.oera-q.local        | Legacy internal    |