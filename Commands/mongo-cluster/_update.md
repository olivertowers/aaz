# [Command] _mongo-cluster update_

Update a mongo cluster resource.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30=/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{} 2024-07-01 -->

#### examples

- Updates the disk size on a Mongo Cluster resource.
    ```bash
        document-db cluster update --storage-size-gb 256
    ```

- Disables public network access on a Mongo Cluster resource with a private endpoint connection.
    ```bash
        document-db cluster update --public-network-access Disabled
    ```
