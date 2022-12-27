# Thesis

[![ci](https://github.com/carlocorradini/thesis/actions/workflows/ci.yml/badge.svg)](https://github.com/carlocorradini/thesis/actions/workflows/ci.yml)

Master Thesis.

## :busts_in_silhouette: Members

| Name  |  Surname  |     Username     |    MAT     |
| :---: | :-------: | :--------------: | :--------: |
| Carlo | Corradini | `carlocorradini` | **223811** |

## :file_folder: Directories

> **Note**: Refer to the `README.md` of each directory for more information

| **Name**                | **Description**                                                   |
| ----------------------- | ----------------------------------------------------------------- |
| [`.github`](./.github/) | [GitHub](https://github.com) configuration                        |
| [`.husky`](./.husky/)   | [husky](https://typicode.github.io/husky) configuration           |
| [`.vscode`](./.vscode/) | [Visual Studio Code](https://code.visualstudio.com) configuration |
| [`scripts`](./scripts/) | `Shell` scripts                                                   |

## :computer: Development

### Requirements

| **Name**  | **Homepage**            |
| --------- | ----------------------- |
| `Node.js` | <https://nodejs.org>    |
| `npm`     | <https://www.npmjs.com> |

### Preparation

1. Clone

   ```sh
   git clone https://github.com/carlocorradini/thesis.git
   cd thesis
   ```

1. Scripts permissions

   ```sh
   find ./scripts -type f -name "*.sh" -exec chmod +x {} \;
   ```

1. Execute [initialization](./scripts/init.sh) script

   ```sh
   ./scripts/init.sh
   ```

### Scripts

> **Note**: Execute with `npm run <NAME>`

| **Name** | **Description**  |
| -------- | ---------------- |
| `check`  | Check for errors |
| `fix`    | Fix errors       |

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) License. \
See [LICENSE](./LICENSE) file for details.
