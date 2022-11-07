# Arya: FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Arya](https://fonts.google.com/specimen/Arya/about).


## How To Use This Font In Your FPM Package:

Include fifthtry.github.io/roboto package into `FPM.ftd` file:

```ftd
-- fpm.dependency: fifthtry.github.io/roboto
```

Inside your `FPM/config.ftd` use the font:

```ftd
-- import: fifthtry.github.io/roboto

-- fpm.type.headline-small.font: $roboto.fonts.Roboto
```

Now if in any file you do:

```ftd
-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `roboto` font.

[Read the docs](https://fifthtry.github.io/arya-font)

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

These fonts are licensed under the [Open Font Licence](https://fonts.google.com/specimen/Arya/about).

## About Original Project

Arya is a Devanagari and Latin type family. It originated with Modular InfoTech's 1201, and was made more smooth. The 
new and original Latin design is intended to match the Devanagari in weight and and size with an unusual high-contrast 
sans serif design.

Designers: Eduardo Tunni, Principal design


