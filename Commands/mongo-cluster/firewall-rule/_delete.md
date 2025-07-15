# [Command] _mongo-cluster firewall-rule delete_

Delete a mongo cluster firewall rule.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vZmlyZXdhbGxydWxlcy97fQ==/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/firewallrules/{} 2024-07-01 -->

#### examples

- Deletes a firewall rule on a Mongo Cluster resource.
    ```bash
        mongo-cluster firewall-rule delete --resource-group TestGroup --mongo-cluster-name myMongoCluster --rule-name rule1
    ```
