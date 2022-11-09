# Arya: FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Arya](https://fonts.google.com/specimen/Arya/about).

Arya is a Devanagari and Latin type family. It originated with Modular InfoTech's 1201, and was made more smooth. The 
new and original Latin design is intended to match the Devanagari in weight and and size with an unusual high-contrast 
sans serif design.

Designers: Eduardo Tunni, Principal design

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/arya-font).

TLRD:

Include fifthtry.github.io/roboto package into `FPM.ftd` file:

```ftd
-- fpm.dependency: fifthtry.github.io/roboto
```

Inside your `FPM/config.ftd` use the font:

```ftd
-- import: fifthtry.github.io/roboto

-- fpm.type.headline-small: $roboto.fonts.Roboto
```

Now if in any file you do:

```ftd
-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `roboto` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Arya Font is under [Open Font Licence](https://fonts.google.com/specimen/Arya/about), this FPM wrapper is also
under [Open Font License](LICENSE).




