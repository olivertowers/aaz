# [Command] _mongo-cluster private-endpoint-connection delete_

Delete the private endpoint connection

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vcHJpdmF0ZWVuZHBvaW50Y29ubmVjdGlvbnMve30=/2024-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/privateendpointconnections/{} 2024-07-01 -->

#### examples

- Delete a private endpoint connection on a Mongo Cluster resource.
    ```bash
        mongo-cluster private-endpoint-connection delete --resource-group TestGroup --mongo-cluster-name myMongoCluster --private-endpoint-connection-name pecTest.5d393f64-ef64-46d0-9959-308321c44ac0
    ```
