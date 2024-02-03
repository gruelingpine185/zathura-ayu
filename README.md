# Ayu Themes for Zathura

<p align="center">
  <a href="https://github.com/gruelingpine185/zathura-ayu/issues">
    <img alt="Github Repo Issues" src="https://img.shields.io/github/issues/gruelingpine185/zathura-ayu?style=for-the-badge&labelColor=1F2430&color=FFAD66">
  </a>
  <a href="https://github.com/gruelingpine185/zathura-ayu/stargazers">
    <img alt="GitHub Repo Stars" src="https://img.shields.io/github/stars/gruelingpine185/zathura-ayu?style=for-the-badge&labelColor=1F2430&color=FFCC66">
  </a>
</p>

## Installation

These themes can be installed using Git and without it. Using the shell commands below, your themes will be installed to `~/.config/zathura/themes/ayu/`.

__Using Git__

```sh
mkdir ~/.config/zathura/themes
git clone https://github.com/gruelingpine185/zathura-ayu ~/.config/zathura/themes/ayu
```

__Without Using Git__

```sh
mkdir -p ~/.config/zathura/themes/ayu
curl https://raw.githubusercontent.com/gruelingpine185/zathura-ayu/main/{ayu_mirage} -o "${HOME}/.config/zathura/themes/ayu/#1"
```

The last step is to pick a theme being one of:  

- ayu_mirage

and include it within your `zathurarc` file.

```zathurarc
include themes/ayu/<theme>

# other config settings ...
```

## Contributing

Contributions are welcomed and encouraged. If you find any issues, feel free to create an [Issue](https://github.com/gruelingpine185/zathura-ayu/issues) or a [Pull Request](https://github.com/gruelingpine185/zathura-ayu/pulls).
