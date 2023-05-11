# petclinic-postgres

TAP deployment of Spring PetClinic

Create the service `ClassClaim` to be consumed by the workload that references your PostgreSQL instance:

```sh
tanzu service class-claim create petclinic-database --class postgresql-unmanaged -n <workload-namespace>
```
