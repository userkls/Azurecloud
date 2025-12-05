## Resource Group
An Azure Resource Group is a logical container in Microsoft Azure that holds related resources for an application or workload.
It helps organize, manage, and control access to resources like virtual machines, storage accounts, databases, and networking components.

### Example Use Cases
Web application deployment: Group VMs, databases, storage, and networking for one app.

Dev/Test environments: Create separate groups for testing and production workloads.

Cost tracking: Assign tags to resource groups to monitor spending by project or department.

Disaster recovery: Manage replication and failover resources together.

### Best Practices
Group by lifecycle: Put resources that share the same lifecycle in one group.

Use naming conventions: Make groups identifiable by project or environment.

Apply RBAC at group level: Simplifies permissions management.

Tagging: Use tags for cost allocation and governance.

## Azure Resource Manager (ARM) 
Azure Resource Manager (ARM) is the deployment and management service for Azure. 
It provides a consistent way to create, update, and delete resources in your Azure account. Think of it as the control plane that organizes and governs everything inside Azure.

### What Azure Resource Manager Does
Unified management layer: ARM is the interface through which all Azure resources are managed.

Declarative templates: You can define infrastructure as code using ARM templates or Bicep.

Access control: Supports Role-Based Access Control (RBAC) at resource, resource group, or subscription level.

Tagging & policies: Apply governance rules and metadata tags to resources for better organization.

Consistency: Ensures that all Azure services follow the same API and management model.

### Key Features
Deployment orchestration: Deploy resources together in a resource group with dependencies handled automatically.

Idempotency: Running the same template multiple times produces the same result, avoiding duplication.

Management APIs: Provides REST APIs, PowerShell, CLI, and SDKs for automation.

Monitoring & auditing: Integrates with Azure Monitor and Activity Logs for visibility.

### Example Use Cases
Infrastructure as Code (IaC): Define a Kubernetes cluster, VMs, networking, and storage in a single ARM template.

Governance: Apply policies to enforce naming conventions or restrict VM sizes.

Automation: Use ARM with CI/CD pipelines to deploy environments consistently.

Cost management: Apply tags to track spending by project or department.
