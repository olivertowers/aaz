# [Command] _docdb cluster firewall-rule update_

Update a new firewall rule or updates an existing firewall rule on a Document DB cluster.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL21vbmdvY2x1c3RlcnMve30vZmlyZXdhbGxydWxlcy97fQ==/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.documentdb/mongoclusters/{}/firewallrules/{} 2024-07-01 -->

#### examples

- Updates a firewall rule on a cluster resource.
    ```bash
        docdb cluster firewall-rule update --resource-group TestGroup --cluster-name myCluster --rule-name rule1 --start-ip-address 0.0.0.0 --end-ip-address 255.255.255.255
    ```
