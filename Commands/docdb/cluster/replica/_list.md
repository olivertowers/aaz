# [Command] _docdb cluster replica list_

List all the replicas of a Document DB cluster.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vcmVwbGljYXM=/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/replicas 2024-07-01 -->

#### examples

- List the replicas linked to a cluster resource.
    ```bash
        docdb cluster replica list --resource-group TestGroup --cluster-name myCluster
    ```
