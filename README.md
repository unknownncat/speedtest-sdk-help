# speedtest-sdk

### ONLY ESM!!

- yarn
```
yarn add speedtest-sdk
```
<br />

- npm
```
npm i speedtest-sdk
```

Como usar?

## sem formatação
```js
import {SpeedTest} from "speedtest-sdk";

(async () => {
  const data = await SpeedTest()
})()
```

## com formatação
OBS: não contém todos os items que o modo sem formatação disponibiliza 

```js
import {SpeedTest} from "speedtest-sdk";

(async () => {
  const data = await SpeedTest(true)
})()
```
