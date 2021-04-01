# resource-schema-workload

- resource-schema-workload json-schema management repo for tmax-cloud/resource-schema repo
- it manages json-schema workload files having $ref

- File Generation Example
    > files on this repo have been generated using [openapi2jsonschema pip tool](https://github.com/instrumenta/openapi2jsonschema)
    - Command Example:
    ```sh
    openapi2jsonschema https://raw.githubusercontent.com/kubernetes/kubernetes/v1.19.4/api/openapi-spec/swagger.json --kubernetes --expanded
    ```
