# DarkBloods

[![code style: prettier][prettier-badge]][prettier-link]
[![Language: Sass][sass-badge]][sass-link]
[![Releases][release-badge]][release-link]
[![License][license-badge]][license-link]
[![Discord Server][discord-badge]][discord-link]
[![Issues][issues-badge]][issues-link]
[![Pull Requests][prs-badge]][prs-link]

![v6 Sapphire]()

</div>

## Installing

Note: ClearVision doesn't actively support plugins (as in, we don't seek out and actively theme fixes to every new plugin). However, when a plugin is widely used, we try our best to stay compatible.

**For BD and Vencord:**

Download the theme file from, [the BetterDiscord Website](https://betterdiscord.app/theme/ClearVision) or [releases](https://github.com/ClearVision/ClearVision-v6/releases) and move it into your injector's themes folder:

- BetterDiscord: `%appdata%\betterdiscord\themes`
- Vencord: `%appdata%\vencord\themes`

**For Replugged:**

Check out our replugged theme [here!](https://github.com/ClearVision/CV-Replugged)

**For using the theme online:**

There are multiple ways to do this if your client offers using an online version. The suggested two are `https://clearvision.github.io/ClearVision-v6/main.css` or `https://raw.githubusercontent.com/ClearVision/ClearVision-v6/master/ClearVision_v6.theme.css`

For customizing the theme from there, you'll want to use custom css and add any variables you'd like to change. It should look something like this

```
:root {
  --main-color: red;
  --hover-color: yellow;
}
```

## Building from source

To build the theme from source, first install npm from the dependecies below, then you can run `npm install` to install all missing dependencies and `npm run build` to compile the theme into the `/public` folder.

### Dependencies

- [NodeJS/npm](https://nodejs.org/)
- [sass](https://www.npmjs.com/package/sass)
- [PostCSS Autoprefixer](https://www.npmjs.com/package/autoprefixer)
- [PostCSS CLI](https://www.npmjs.com/package/postcss-cli)
- [rimraf](https://www.npmjs.com/package/rimraf) (for cleanup)
- [Prettier](https://www.npmjs.com/package/prettier) (code formatting)

## Contributing

You can run `npm run test` to compile the theme.
The `main.css` file will be in the `/test` directory, which can then be copied into BetterDiscord's Custom CSS, or placed in the themes folder and enabled in settings, make sure any other theme's are disabled for testing.
