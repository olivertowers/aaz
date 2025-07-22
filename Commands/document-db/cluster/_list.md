# [Command] _docdb cluster list_

List all the Document DB clusters in a given subscription.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnM=/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.documentdb/mongoclusters 2024-07-01 -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters 2024-07-01 -->

#### examples

- Lists the cluster resources in a subscription.
    ```bash
        docdb cluster list
    ```

- Lists the cluster resources in a resource group.
    ```bash
        docdb cluster list --resource-group TestResourceGroup
    ```
