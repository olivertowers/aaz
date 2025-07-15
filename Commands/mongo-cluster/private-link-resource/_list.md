# [Command] _mongo-cluster private-link-resource list_

List private links on the given resource

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vcHJpdmF0ZWxpbmtyZXNvdXJjZXM=/2024-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/privatelinkresources 2024-07-01 -->

#### examples

- Lists the private link resources available on a Mongo Cluster resource.
    ```bash
        mongo-cluster private-link-resource list --resource-group TestGroup --mongo-cluster-name myMongoCluster
    ```
