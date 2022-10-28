# HedgeDocs template
## DRAFT

To test this, one must, login in Rahti and create a project:

```sh
$ oc create -f hedgedoc-template.yml
```

This adds the template to the internal catalog of the project, and it could be then deployed from the webinterface or using `oc`.

## Files

* This `README.md` file
* A `docker-compose.yml` file, taken from <https://docs.hedgedoc.org/setup/docker/>.
* A `hedgedoc-template.yml` template file. The initial conversion is done using the `kompose` tool.

