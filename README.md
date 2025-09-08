```mermaid
flowchart LR
  subgraph AWS [Amazon Web Services]
    AProv[Provider<br/>- Physical DCs and Facilities<br/>- Network and Hypervisor<br/>- Managed Services]
    ACust[Customer<br/>- Data and Identity (IAM)<br/>- OS, Apps, Configs (IaaS)<br/>- Access Controls and Keys<br/>- Compliance in Cloud]
  end

  subgraph AZ [Microsoft Azure]
    ZProv[Provider<br/>- Physical DCs and Facilities<br/>- Network and Hypervisor<br/>- PaaS and SaaS Runtime]
    ZCust[Customer<br/>- Data and Identity (Entra ID)<br/>- Workloads and Configs (IaaS)<br/>- RBAC, Policies, Keys<br/>- Compliance in Cloud]
  end

  subgraph GCP [Google Cloud Platform]
    GProv[Provider<br/>- Physical DCs and Facilities<br/>- Network and Hypervisor<br/>- Global Control Plane]
    GCust[Customer<br/>- Data and Identity (IAM)<br/>- Workloads and Configs (IaaS)<br/>- Org Policies and Keys<br/>- Compliance in Cloud]
  end
```
