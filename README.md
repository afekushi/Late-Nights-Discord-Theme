# Late Nights
</div>

**For BD and Vencord:**

Download the theme file from [our official support server](https://clearvision.github.io/join), [the BetterDiscord Website](https://betterdiscord.app/theme/ClearVision) or [releases](https://github.com/ClearVision/ClearVision-v6/releases) and move it into your injector's themes folder:

- BetterDiscord: `%appdata%\betterdiscord\themes`
- Vencord: `%appdata%\vencord\themes`

## Building from source

To build the theme from source, you can simply run `npm install` to install all missing dependencies and `npm run build` to compile the theme into the `/public` folder.

### Dependencies

- [NodeJS/npm](https://nodejs.org/)
- [sass](https://www.npmjs.com/package/sass)
- [PostCSS Autoprefixer](https://www.npmjs.com/package/autoprefixer)
- [PostCSS CLI](https://www.npmjs.com/package/postcss-cli)
- [rimraf](https://www.npmjs.com/package/rimraf) (for cleanup)
- [Prettier](https://www.npmjs.com/package/prettier) (code formatting)

## Contributing

You can run `npm run test` to compile the theme.
The `main.css` file will be in the `/test` directory, which can then be copied into BetterDiscord's Custom CSS.
