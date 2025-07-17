# [Command] _mongo-cluster create_

Create a mongo cluster. Update overwrites all properties for the resource. To only modify some of the properties, use PATCH.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30=/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{} 2024-07-01 -->

#### examples

- Creates a new Mongo Cluster resource.
    ```bash
        document-db cluster create --resource-group TestResourceGroup --cluster-name myMongoCluster --location westus2 --administrator-name mongoAdmin --administrator-password password --server-version 5.0 --storage-size-gb 128 --compute-tier M30 --shard-count 1 --high-availability-mode ZoneRedundantPreferred
    ```
