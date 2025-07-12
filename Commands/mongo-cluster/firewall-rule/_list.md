# [Command] _mongo-cluster firewall-rule list_

List all the firewall rules in a given mongo cluster.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vZmlyZXdhbGxydWxlcw==/2024-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/firewallrules 2024-07-01 -->

#### examples

- List the firewall rules on a Mongo Cluster resource.
    ```bash
        mongo-cluster firewall-rule list --resource-group TestGroup --mongo-cluster-name myMongoCluster
    ```
