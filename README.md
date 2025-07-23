# Power BI P to F SKU Capacity Migration

This repository provides tools and guidance for migrating Power BI Premium (P) SKU capacities to Fabric (F) SKU capacities.

## Overview

Power BI Premium P SKUs are being transitioned to Microsoft Fabric F SKUs as part of Microsoft's unified analytics platform strategy. This repository contains scripts, documentation, and best practices to help organizations smoothly migrate their Power BI Premium capacities to Fabric capacities.

## What's Included

- **Migration Scripts**: Automated tools to assist with the capacity migration process
- **Documentation**: Step-by-step guides and best practices for P to F SKU migration
- **Jupyter Notebooks**: Interactive analysis and migration planning tools
- **Success Examples**: Real-world migration results and outcomes

## P vs F SKU Comparison

| Feature | Premium P SKU | Fabric F SKU |
|---------|---------------|--------------|
| Workload Support | Power BI focused | Full Fabric workloads (Power BI, Data Factory, Synapse, etc.) |
| Pricing Model | Premium per user/capacity | Unified Fabric pricing |
| Management | Power BI Admin Portal | Fabric Admin Portal |
| Integration | Power BI ecosystem | Full Microsoft Fabric ecosystem |

## Prerequisites

Before starting the migration process:

- Administrative access to Power BI Premium capacity
- Permissions to create Fabric capacities in your tenant
- Understanding of current workload requirements and usage patterns
- Backup of critical Power BI content and configurations

## Getting Started

1. **Assessment Phase**
   - Review current P SKU usage and requirements
   - Identify workspaces and content to migrate
   - Plan capacity sizing for F SKUs

2. **Migration Planning**
   - Use the provided Jupyter notebooks for analysis
   - Review migration timeline and dependencies
   - Coordinate with stakeholders

3. **Execution**
   - Follow the step-by-step migration guides
   - Use automation scripts where applicable
   - Monitor migration progress and validate results

## Key Benefits of Migration

- **Enhanced Capabilities**: Access to full Fabric workloads beyond Power BI
- **Unified Platform**: Single platform for all analytics needs
- **Cost Optimization**: Potential cost savings with unified Fabric pricing
- **Future-Ready**: Access to latest Microsoft analytics innovations

## Support and Resources

- [Microsoft Fabric Documentation](https://docs.microsoft.com/fabric/)
- [Power BI Premium Migration Guide](https://docs.microsoft.com/power-bi/admin/service-premium-what-is)
- [Fabric Capacity Planning](https://docs.microsoft.com/fabric/admin/capacity-planning)

## Contributing

Contributions to improve migration tools and documentation are welcome. Please submit pull requests with detailed descriptions of changes.

## License

This project is provided as-is for educational and migration assistance purposes.

## Assign Workspace to Capacity Test Results
[success results](docs/success-results.png)
