# Thesis

[![ci](https://github.com/carlocorradini/thesis/actions/workflows/ci.yml/badge.svg)](https://github.com/carlocorradini/thesis/actions/workflows/ci.yml)

Master Thesis.

## Members

| Name  |  Surname  |     Username     |    MAT     |
| :---: | :-------: | :--------------: | :--------: |
| Carlo | Corradini | `carlocorradini` | **223811** |

## :computer: Development

### Requirements

| **Name**   | **Homepage**                   |
| ---------- | ------------------------------ |
| `Node.js`  | <https://nodejs.org>           |
| `npm`      | <https://www.npmjs.com>        |
| `TeX Live` | <https://www.tug.org/texlive/> |

### Preparation

1. Clone

   ```sh
   git clone https://github.com/carlocorradini/thesis.git
   cd thesis
   ```

1. Install Dependencies

   ```sh
   npm ci
   ```

### Build

> **Warning**: On _Windows_, a script may fail to execute, run it directly

```sh
npm run build
```

### Scripts

> **Note**: Execute with `npm run <NAME>`

| **Name** | **Description**  |
| -------- | ---------------- |
| `build`  | Build PDF        |
| `check`  | Check for errors |
| `fix`    | Fix errors       |

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) License. \
See [LICENSE](./LICENSE) file for details.
