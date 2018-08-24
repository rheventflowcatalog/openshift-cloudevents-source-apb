# APB for k8s CloudEvent Source

Monitor the k8s system and emit CloudEvent messages containing monitoring information

## Development / Building

```bash
$ alias apb='docker run --rm --privileged -v $PWD:/mnt -v $HOME/.kube:/.kube -v /var/run/docker.sock:/var/run/docker.sock -u $UID docker.io/ansibleplaybookbundle/apb-tools:release-1.1'
```

```bash
$ apb prepare && apb build && apb push
```  