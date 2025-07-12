# [Command] _mongo-cluster promote_

Promotes a replica mongo cluster to a primary role.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vcHJvbW90ZQ==/2024-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/promote 2024-07-01 -->

#### examples

- Promotes a replica Mongo Cluster resource to a primary role.
    ```bash
        mongo-cluster replica promote --resource-group TestGroup --mongo-cluster-name replicaMongoCluster --promote-option Forced --promote-mode Switchover
    ```
