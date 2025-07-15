# [Command] _mongo-cluster private-endpoint-connection list_

List existing private connections

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vcHJpdmF0ZWVuZHBvaW50Y29ubmVjdGlvbnM=/2024-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/privateendpointconnections 2024-07-01 -->

#### examples

- Lists the private endpoint connection resources on a Mongo Cluster resource.
    ```bash
        mongo-cluster private-endpoint-connection list --resource-group TestGroup --mongo-cluster-name myMongoCluster
    ```
