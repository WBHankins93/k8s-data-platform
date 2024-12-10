## Installing Kind on macOS (Intel chip)

### Steps:

1. Download the binary:
   ```
   curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.20.0/kind-darwin-amd64
   ```

2. Make it executable :
    ```
    chmod +x ./kind
    ```

3. Move it to your PATH:
    ```
    sudo mv ./kind /usr/local/bin/kind
    ```

4. Verify the installation:
    ```
    kind version
    ```


### Cluster Creation
#### Ensure Docker is Running

1. Create cluster
    ```
    kind create cluster --name <cluster-name>
    ```