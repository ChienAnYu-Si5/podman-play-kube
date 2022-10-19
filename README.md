# podman-play-kube
YAML file for easy building environment

## Generate YAML of a pod
```sh
podman generate kube $POD_NAME -f $YAML_FILENAME
```

## Play YAML to a pod
```sh
podman play kube $YAML_FILENAME
```
