# [Command] _docdb cluster list-connection-strings_

List Document DB cluster connection strings. This includes the default connection string using SCRAM-SHA-256, as well as other connection strings supported by the cluster.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vbGlzdGNvbm5lY3Rpb25zdHJpbmdz/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/listconnectionstrings 2024-07-01 -->

#### examples

- List the available connection strings for the cluster resource.
    ```bash
        docdb cluster list-connection-strings --resource-group TestGroup --cluster-name myCluster
    ```
