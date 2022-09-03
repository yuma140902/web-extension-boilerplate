# Web Extension Boilerplate

<div align="center">
  <img width="300" src="https://user-images.githubusercontent.com/6290720/118306393-5ab20b80-b524-11eb-9d70-ac7ed740397b.png" />
  <br />
  <br />
</div>

This boilerplate provides a skeleton to start developing cross-browser web extensions.

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[![jest](https://jestjs.io/img/jest-badge.svg)](https://github.com/facebook/jest) [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/davidnguyen179/web-extension-boilerplate/pulls)
![ci/cd](https://github.com/davidnguyen179/web-extension-boilerplate/workflows/ci/cd/badge.svg)

## Development Build

```bash
npm i
```

**Chrome**

```bash
npm run build:chrome
```

**Edge**

```bash
npm run build:edge
```

**Firefox**

```bash
npm run build:firefox
```

## Production Build

```bash
npm i
```

```bash
npm run build:chrome-prod
```

**Edge**

```bash
npm run build:edge-prod
```

**Firefox**

```bash
npm run build:firefox-prod
```

## Load package to browsers

**Chrome**

1. Go to the browser's URL address bar
2. Enter `chrome://extensions/`
3. Switch to "**Developer mode**"
4. Load extension by clicking "**Load unpacked**"
5. Browse to `dist/` in source code
6. Done!

Check here for more detail: [https://developer.chrome.com/extensions/getstarted](https://developer.chrome.com/extensions/getstarted)

**Edge**

1. Go to the browser's URL address bar
2. Enter `edge://extensions/`
3. Turn on `Developer mode`
4. Load extension by clicking "**Load unpacked**"
5. Browse to `dist/` in source code
6. Done!

**Firefox**

```bash
npm start
```

Check here for more details: [https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/](https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/)

## How to keep devtool appears when developing

Simple, just open chrome extension as a page. To do that, follow below steps:

1. Open extension management page
<img width="333" alt="Screen Shot 2021-05-27 at 14 44 56" src="https://user-images.githubusercontent.com/6290720/119772790-b011f380-befa-11eb-9ab2-f49c1858206b.png">

2. Copy extension id

<img width="712" alt="Screen Shot 2021-05-27 at 14 45 20" src="https://user-images.githubusercontent.com/6290720/119773037-0b43e600-befb-11eb-8887-1696816026d0.png">

3. Open extension as a page `chrome-extension://<extension-id>/popup.html`

- For example: [chrome-extension://npjcjlkchmiidojhockoecphakigbaej/popup.html](chrome-extension://npjcjlkchmiidojhockoecphakigbaej/popup.html)

<img width="792" alt="chrome-extension://npjcjlkchmiidojhockoecphakigbaej/popup.html" src="https://user-images.githubusercontent.com/6290720/120733663-90925080-c522-11eb-8b92-8bc34def4333.png">

## Privacy Policy file

Web stores require you to describe what the extension is or if you collect data of users. You also need to describe why you do that.

Make sure you include this file when you publish an extension, the web store may ask you to upload it.

**Note:** If you don't know how to write a privacy policy file, you can look at the [existing one](https://github.com/davidnguyen179/web-extension-boilerplate/blob/main/PRIVACY_POLICY.txt) attached on this repository.

## Badges

You can add badges to your project to indicate the version or to show how many users use your extension here:

- [https://shields.io/](https://shields.io/)

## CI/CD with github action

You can modify the `.github/workflows` to show the CI/CD flow.

- [https://docs.github.com/en/free-pro-team@latest/actions/guides/building-and-testing-nodejs](https://docs.github.com/en/free-pro-team@latest/actions/guides/building-and-testing-nodejs)

## How to publish web extension

| Browsers       | Web store                                                                                                                                                                                      |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Chrome         | [https://developer.chrome.com/webstore/publish](https://developer.chrome.com/webstore/publish)                                                                                                 |
| Microsoft Edge | [https://docs.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/publish-extension](https://docs.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/publish-extension) |
| Firefox        | [https://extensionworkshop.com/documentation/publish/submitting-an-add-on](https://extensionworkshop.com/documentation/publish/submitting-an-add-on)                                           |

## References

- Develop your first Chrome extension & Chromium Edge: [https://developer.chrome.com/extensions](https://developer.chrome.com/extensions)
- Develop your first Firefox add-on: [https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension)
- If you have any Chrome extension issues, you can post it here: [https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions)
- [Jack and Amy Dev youtube channel](https://www.youtube.com/channel/UCVj3dGw75v8aHFYD6CL1tFg), which explains some common mistakes made when developing Chrome extensions.

## Showcase

- [Spotify Web Extension](https://spotify-extension.netlify.app/)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://www.dzungnguyen.dev"><img src="https://avatars.githubusercontent.com/u/6290720?v=4?s=100" width="100px;" alt=""/><br /><sub><b>David Nguyen</b></sub></a><br /><a href="https://github.com/davidnguyen179/web-extension-boilerplate/commits?author=davidnguyen179" title="Code">💻</a> <a href="https://github.com/davidnguyen179/web-extension-boilerplate/commits?author=davidnguyen179" title="Documentation">📖</a> <a href="#design-davidnguyen179" title="Design">🎨</a> <a href="#maintenance-davidnguyen179" title="Maintenance">🚧</a> <a href="https://github.com/davidnguyen179/web-extension-boilerplate/pulls?q=is%3Apr+reviewed-by%3Adavidnguyen179" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/davidnguyen179/web-extension-boilerplate/commits?author=davidnguyen179" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://github.com/immint023"><img src="https://avatars.githubusercontent.com/u/38607460?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Minh Ngo</b></sub></a><br /><a href="https://github.com/davidnguyen179/web-extension-boilerplate/commits?author=immint023" title="Code">💻</a> <a href="https://github.com/davidnguyen179/web-extension-boilerplate/commits?author=immint023" title="Tests">⚠️</a></td>
    <td align="center"><a href="http://benlee3.com"><img src="https://avatars.githubusercontent.com/u/35267414?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ben Harned</b></sub></a><br /><a href="https://github.com/davidnguyen179/web-extension-boilerplate/commits?author=3BenLee" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
