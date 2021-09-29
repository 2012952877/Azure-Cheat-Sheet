# Azure Kubernetes介绍

官方文档：https://docs.microsoft.com/zh-cn/azure/aks/

Azure Kubernetes 服务 (AKS) 通过将操作开销卸载到 Azure，简化了在 Azure 中部署托管 Kubernetes 群集的过程。 作为一个托管的 Kubernetes 服务，Azure 可以自动处理运行状况监视和维护等关键任务。 **由于 Kubernetes 主节点由 Azure 管理，因此你只需要管理和维护代理节点。 因此，AKS 是免费的，你只需支付群集中的代理节点费，不需支付主节点的费用。**

当你部署 AKS 群集时，系统会为你部署和配置 Kubernetes 主节点和所有节点。 在部署过程中，可以配置**高级网络、Azure Active Directory (Azure AD) 集成、监视和其他功能。**

AKS 还支持 Windows Server 容器

此服务支持 [Azure Lighthouse](https://docs.microsoft.com/zh-cn/azure/lighthouse/overview)；通过它，服务提供商可登录自己的租户来管理客户委托的订阅和资源组。

## 创建方法

可使用以下方式创建 AKS 群集：

- [Azure CLI](https://docs.microsoft.com/zh-cn/azure/aks/kubernetes-walkthrough)
- [Azure 门户](https://docs.microsoft.com/zh-cn/azure/aks/kubernetes-walkthrough-portal)
- [Azure PowerShell](https://docs.microsoft.com/zh-cn/azure/aks/kubernetes-walkthrough-powershell)
- 使用模板驱动的部署选项，例如 [Azure 资源管理器模板](https://docs.microsoft.com/zh-cn/azure/aks/kubernetes-walkthrough-rm-template)和 Terraform

> Terraform的使用较为重要，partner 联蔚采取该方案给客户费列罗部署

## 访问权限、安全性和监视

要改善安全性和管理，AKS 允许集成 Azure AD 来实现以下目的：

- 使用 Kubernetes 基于角色的访问控制 (Kubernetes RBAC)。
- 监视群集和资源的运行状况。



# OpenHack 容器部分 - 帮助更好理解和学习AKS



