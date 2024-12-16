<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/alexpasmantier/television">television</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/television/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/television?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/television/issues"><img src="https://img.shields.io/github/issues/catppuccin/television?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/television/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/television?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

1. Download your preferred flavor and accent combination from [`themes/`](./themes/).
2. Move the downloaded file to the `themes/` folder of your television configuration directory (see https://github.com/alexpasmantier/television/blob/main/README.md#configuration).
3. Add the following to your television configuration file (`config.toml`), replacing `<flavor>` and `<accent>` with the flavor and accent you chose.

```toml
[ui]
theme = "catppuccin-<flavor>-<accent>.toml"
```

In other words, the value of the `ui.theme` key should match the filename of the file downloaded previously.

4. If you have a [catppuccin/bat](https://github.com/catppuccin/bat) theme installed, add the following again to your television configuration file:

```toml
[previewers.file]
theme = "Catppuccin <flavor>"
```

Where `<flavor>` is the name of the catppuccin/bat flavor you would like to use, such as "Mocha".

## Contributing

This repository uses [Whiskers](https://github.com/catppuccin/whiskers) to generate theme files. Edit the `television.tera` template, and run either `whiskers television.tera` or `just build` (if you have [just](https://github.com/casey/just) installed) to update the files in `themes/`.

## 💝 Thanks to

- [uncenter](https://github.com/uncenter)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
