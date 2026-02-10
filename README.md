# Anti-testportal

Minimalistic Chrome extension - bypass for blur check on testportal.pl(net).

🈹🐀💥 Changing pages will not display a warning about leaving the page.

[![forthebadge](https://forthebadge.com/images/badges/made-with-typescript.svg)](https://forthebadge.com)

Join our Discord! https://discord.gg/HPecVXeQrF

[<img width="250" src="https://i.imgur.com/ZeD4O9a.png" alt="anti-testportal">](https://i.imgur.com/ZeD4O9a.png)

## Compile from source
> [!WARNING]
> I have little to no experience with TypeScript so all that in this section was a result of like 18 minutes of research... I made it work for me but i have no idea how universal/correct that is
1. Make sure you have webpack installed `sudo npm install -g webpack`
2. Also install [yarn](https://yarnpkg.com/) however you do on your distro; for arch it's `sudo pacman -S yarn`
3. now run `npm run build` in the root directory
4. If you get an error that looks like this `Error: error:0308010C:digital envelope routines::unsupported
` it might help to do `export NODE_OPTIONS=--openssl-legacy-provider` and re run the npm command
5. Now all files you need will be in `./dist/` so do what [Usage](#usage) section tells you, starting from step 3

## Usage

[Unofficial extension in Chrome web store](https://chrome.google.com/webstore/detail/anti-testportal/dpgfbfopkfdfmlfdpmoanamopdnibhkl)
(thanks to szoppracz07.ovh)

1. **Go to the Releases page** (`then download newest version (.zip)`).
2. **Unpack** ZIP file.
3. **Go to the extensions page** (`chrome://extensions or Chrome menu -> More tools -> Extensions`).
4. Enable **Developer mode** (`upper right corner`).
5. Click **Load unpacked** (`or drag the folder anywhere on the page`).
6. **Indicate the folder** you unpacked.

## Made using:

- [TypeScript](https://www.typescriptlang.org/)
- [Webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)

## Contributing

Pull requests are welcome.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Motivation

I got few negative grades at school because of this website, because I am too busy to learn :]