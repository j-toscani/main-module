# main-module
Main Repo to test git submodules

## Fetching submodule

In order to fetch the submodule use the following command:

```sh
# When cloning the project
git clone --recurse-submodules <url>

# Update and init when project already exists
git submodule update --init

# To update, fetch and init all submodules when project already exists
git submodule update --init --recursive
```