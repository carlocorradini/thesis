<!-- markdownlint-disable MD024 -->
<!-- markdownlint-disable MD033 -->

# Scripts

Scripts.

## :bookmark_tabs: [`init.sh`](./init.sh)

Initialization script.

```sh
./init.sh
```

### Arguments

> **Note**: Type `--help` for more information

> **Note**: [commons arguments](#commons-arguments) available

| **Name** | **Description**            | **Default** | **Values** |
| -------- | -------------------------- | ----------- | ---------- |
| `--help` | Show help message and exit |

## :bookmark_tabs: [`__commons.sh`](./__commons.sh)

> **Warning**: Included (`. path/to/__commons.sh`) by other scripts

Common functions and helpers.

<h3 id="commons-arguments">Arguments</h3>

| **Name**              | **Description** | **Default** | **Values**                                                                                                                          |
| --------------------- | --------------- | ----------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| `--disable-color`     | Disable color   | `false`     |
| `--log-level <LEVEL>` | Logger level    | `info`      | `fatal` Fatal level <br/> `error` Error level <br/> `warn` Warning level <br/> `info` Informational level <br/> `debug` Debug level |
