# charm-skelton

This is the skeleton of an [operator framework](https://github.com/canonical/operator) charm.

## Usage

To get the charm:

```bash
git clone https://github.com/AdamIsrael/charm-skeleton
cd charm-skeleton

# Install the submodules
git submodule update --init
```

To deploy to juju:
```
juju deploy .
```

```
# Make sure the charm is in an Active state
juju status
```

