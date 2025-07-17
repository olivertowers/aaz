# [Command] _mongo-cluster check-name-availability_

Check if mongo cluster name is available for use.

## Versions

### [2024-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kb2N1bWVudGRiL2xvY2F0aW9ucy97fS9jaGVja21vbmdvY2x1c3Rlcm5hbWVhdmFpbGFiaWxpdHk=/2024-07-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.documentdb/locations/{}/checkmongoclusternameavailability 2024-07-01 -->

#### examples

- Checks and confirms the Mongo Cluster name is availability for use.
    ```bash
        document-db cluster check-name-availability --location westus2 --name newmongocluster
    ```
