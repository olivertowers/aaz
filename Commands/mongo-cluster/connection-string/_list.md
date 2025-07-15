# [Command] _mongo-cluster connection-string list_

List mongo cluster connection strings. This includes the default connection string using SCRAM-SHA-256, as well as other connection strings supported by the cluster.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vbGlzdGNvbm5lY3Rpb25zdHJpbmdz/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/listconnectionstrings 2024-07-01 -->

#### examples

- List the available connection strings for the Mongo Cluster resource.
    ```bash
        mongo-cluster connection-string list --resource-group TestGroup --mongo-cluster-name myMongoCluster
    ```
