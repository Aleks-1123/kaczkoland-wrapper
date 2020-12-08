<h1 align="center">Welcome to kaczkoland-wrapper 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/kaczkoland-wrapper" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/kaczkoland-wrapper.svg">
  </a>
  <a href="https://github.com/Aleks-1123/kaczkoland-wrapper#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/Aleks-1123/kaczkoland-wrapper/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/Aleks-1123/kaczkoland-wrapper/blob/master/LICENSE" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/github/license/Aleks-1123/kaczkoland-wrapper" />
  </a>
</p>

> A kaczkoland.pl minecraft server API wrapper

### 🏠 [Homepage](https://github.com/Aleks-1123/kaczkoland-wrapper#readme)

## Install

```sh
npm install kaczkoland-wrapper --save
```

## Demo

```javascript
/* Creating a API variable */
const API = require("kaczkoland-wrapper");
/* Getting a user from username */
const user = await API.get("Aleksio1123");
/* Getting a user rank */
const rank = user.primary_rank;
/* Output */
console.log(rank);
```

## Author

👤 **Aleks1123**

* Website: http://aleks.ovh
* Github: [@Aleks-1123](https://github.com/Aleks-1123)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Aleks1123](https://github.com/Aleks-1123).<br />
This project is [ISC](https://github.com/Aleks-1123/kaczkoland-wrapper/blob/master/LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_