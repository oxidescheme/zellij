<div align="center">

# oxide for Zellij

</div>

<h6 align="center">
Where function meets form.
</h6>

<p align="center">
  <a href="https://github.com/oxidescheme/zellij/stargazers"><img src="https://img.shields.io/github/stars/oxidescheme/zellij?colorA=161616&colorB=00a6ff&style=for-the-badge"></a>
  <a href="https://github.com/oxidescheme/zellij/issues"><img src="https://img.shields.io/github/issues/oxidescheme/zellij?colorA=161616&colorB=ff5655&style=for-the-badge"></a>
  <a href="https://discord.gg/p8GcbBH5MR"><img src="https://img.shields.io/discord/1450777325267456097?style=for-the-badge&color=00baaa&labelColor=161616&logo=discord&logoColor=white"></a>
</p>

*oxide* for [Zellij](https://zellij.dev/) brings the oxide colorscheme to your terminal workspace with OKLCH precision.
A minimalist dark theme built around clarity and restraint, using a deep near-black background, crisp white foregrounds, and vibrant accent colors to emphasize structure without visual noise.

## Design Philosophy

oxide is built on three core principles:

- **Function first**: Every color exists to convey information
- **Visual silence**: Elegance emerges from what is intentionally omitted
- **Systematic harmony**: Every color relates predictably to the others

The full design philosophy and color system are documented in the [main oxide repository](https://github.com/oxidescheme/oxide).

## Installation

1. Download the `oxide.kdl` file from this repository
2. Copy it to your Zellij themes directory: `~/.config/zellij/themes/`
3. Add the theme to your Zellij configuration file (`~/.config/zellij/config.kdl`):

```kdl
theme "oxide"
```

4. Reload or restart Zellij

### Themes Directory

You can find the exact location of the themes directory with:

```bash
zellij setup --check
```

## Contributing

We follow the same philosophy as the main oxide project: minimalism doesn't mean stagnation.

- Report issues through [GitHub Issues](https://github.com/oxidescheme/zellij/issues)
- PRs that improve clarity and consistency are welcome
- Ensure changes align with oxide's functional aesthetic

## Credits

- **Port Creator:** [@jakmaz](https://github.com/jakmaz)
- **Current Maintainer:** [@jakmaz](https://github.com/jakmaz)
- **Contributors:** See [contributors list](https://github.com/oxidescheme/zellij/graphs/contributors)

## License

MIT License - see [LICENSE](LICENSE) for details.

<p align="center">
Copyright &copy; 2026-present oxidescheme
</p>