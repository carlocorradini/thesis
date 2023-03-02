# Thesis

[![ci](https://github.com/carlocorradini/thesis/actions/workflows/ci.yml/badge.svg)](https://github.com/carlocorradini/thesis/actions/workflows/ci.yml)

Master Thesis.

## Members

| Name  |  Surname  |     Username     |    MAT     |
| :---: | :-------: | :--------------: | :--------: |
| Carlo | Corradini | `carlocorradini` | **223811** |

## Development

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

> **Note**: Compiled PDF [`corradini_carlo_computer_science_2021_2022.pdf`](./corradini_carlo_computer_science_2021_2022.pdf)

```sh
npm run build
```

### Scripts

> **Note**: Execute with `npm run <NAME>`

| **Name** | **Description**  |
| -------- | ---------------- |
| `build`  | Build PDF        |
| `check`  | Check for errors |
| `clean`  | Clean            |
| `fix`    | Fix errors       |

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) License. \
See [LICENSE](./LICENSE) file for details.
