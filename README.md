<p align="center">
    <img title="Zaimea Docs" height="100" src="https://raw.githubusercontent.com/zaimea/zaimea/abbd74370cc1d48272a9d2dbeecc79b82b16b53b/.github/logo-light.svg?token=A6OCZM3JHYFMHBZK5I7ANB3GFICZS" />
</p>


## Zaimea Docs Website

This is the source of the official [Zaimea Docs website](https://docs.zaimea.com).

## Local Development

If you want to work on this project on your local machine, you may follow the instructions below. These instructions assume you are serving the site using Laravel Valet out of your `~/Sites` directory:

1. Fork this repository 
2. Open your terminal and `cd` to your `~/Sites` folder
3. Clone your fork into the `~/Sites/docs.zaimea.com` folder, by running the following command *with your username placed into the {username} slot*:
    ```bash
    git clone https://github.com/{username}/docs.zaimea.com docs.zaimea.com
    ```
4. CD into the new directory you just created:
    ```bash
    cd docs.zaimea.com
    ```
5. Run the `setup.sh` bin script, which will take all the steps necessary to prepare your local install:
    ```bash
    ./bin/setup.sh
    ```

### Syncing Upstream Changes Into Your Fork 

This [GitHub article](https://help.github.com/en/articles/syncing-a-fork) provides instructions on how to pull the latest changes from this repository into your fork.

### Updating After Remote Code Changes

If you pull down the upstream changes from this repository into your local repository, you'll want to update your Composer and NPM dependencies, as well as update your documentation branches. For convenience, you may run the `bin/update.sh` script to update these things:

```bash
./bin/update.sh
```
