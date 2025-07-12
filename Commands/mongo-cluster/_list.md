# [Command] _mongo-cluster list_

List all the mongo clusters in a given resource group.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnM=/2024-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.documentdb/mongoclusters 2024-07-01 -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters 2024-07-01 -->

#### examples

- Lists the Mongo Cluster resources in a resource group.
    ```bash
        mongo-cluster list --resource-group TestResourceGroup
    ```

- Lists the Mongo Cluster resources in a subscription.
    ```bash
        mongo-cluster list
    ```
