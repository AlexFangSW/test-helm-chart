# Helm Repo test
## Update
* Clone this repo
* Packege a helm chart directory
    ```bash
    helm packege {chart dir}
    ```
* Move `.tgz` file into this repo
* Update `index.yaml`
    ```bash
    helm index {directory for this repo}
    ```
* Push repo
