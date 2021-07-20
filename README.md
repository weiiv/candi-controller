# candi-controller

From within the [docker](./docker) folder:
    - run `./manage build` to assemble the runtime images for the services
    - when the build completes, run `./manage start`

Once started, the services will be exposed on localhost at the following endpoints:

- `api`: http://localhost:5000

- `db`: http://localhost:27017
