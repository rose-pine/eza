<p align="center">
    <img src="https://github.com/rose-pine/rose-pine-theme/raw/main/assets/icon.png" width="80" />
    <h2 align="center">Rosé Pine for eza</h2>
</p>

<p align="center">All natural pine, faux fur and a bit of soho vibes for the classy minimalist</p>

## Usage

eza reads its theme from `theme.yml` inside `$EZA_CONFIG_DIR`, which defaults to
`~/.config/eza`. Copy the variant you want into place:

```sh
mkdir -p ~/.config/eza
curl -o ~/.config/eza/theme.yml \
  https://raw.githubusercontent.com/quentinlintz/rose-pine-eza/main/dist/rose-pine-moon.yml
```

Swap `rose-pine-moon.yml` for `rose-pine.yml` or `rose-pine-dawn.yml` to taste.

Colours apply immediately — no shell restart needed. Verify with:

```sh
eza --long --git
```

> [!NOTE]
> `LS_COLORS` and `EZA_COLORS` take precedence over `theme.yml`. If filenames
> still look wrong, unset them or drop the entries that overlap.

> [!IMPORTANT]
> eza considers `theme.yml` unstable and may change the schema between releases.
> Built and tested against eza v0.23.5.

## Gallery

### Rosé Pine

<img width="256" alt="Rosé Pine with eza" src="" />

### Rosé Pine Moon

<img width="256" alt="Rosé Pine Moon with eza" src="" />

### Rosé Pine Dawn

<img width="256" alt="Rosé Pine Dawn with eza" src="" />

## Thanks to

- [You, it's you!](https://github.com/quentinlintz)

## Contributing

<!-- BLOOM_BUILD_START -->
This theme was built using [bloom](https://github.com/rose-pine/rose-pine-bloom):

```sh
bloom build template.yml --output dist --prefix $ --format hex
```
<!-- BLOOM_BUILD_END -->

Edit `template.yml` and rebuild — never edit `dist/` by hand.
