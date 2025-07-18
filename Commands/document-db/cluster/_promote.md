# [Command] _document-db cluster promote_

Promotes a replica mongo cluster to be primary.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vcHJvbW90ZQ==/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/promote 2024-07-01 -->

#### examples

- Promotes a replica Mongo Cluster resource to a primary role.
    ```bash
        document-db cluster promote --resource-group TestGroup --cluster-name myMongoCluster --promote-option Forced --mode Switchover
    ```
