## Deployment

To deploy this project run

```bash
  npm i color-in-terminal
```


## Demo

![](https://media.discordapp.net/attachments/876815323549028392/1006619355502608394/Capture_decran_2022-08-09_a_20.45.48.png)
## Usage/Examples

```javascript
const { Color } = require('color-in-terminal')

console.log(`${Color.Underscore}${Color.FgCyan}Task:${Color.Reset}${Color.FgGreen} Ok for today !${Color.Reset}`);
```

#### Output :
![](https://media.discordapp.net/attachments/876815323549028392/1006618717544787978/Capture_decran_2022-08-09_a_20.43.15.png)
## Documentation

```javascript
const { Color } = require('color-in-terminal')

console.log(`
    ${Color.Bright}Bright${Color.Reset}
    ${Color.Dim}Dim${Color.Reset}
    ${Color.Underscore}Underscore${Color.Reset}
    ${Color.Blink}Blink${Color.Reset}
    ${Color.Reverse}Reverse${Color.Reset}
    ${Color.Hidden}Hidden${Color.Reset}
`)

// 'Fg' prefix for foreground
console.log(`
    ${Color.FgBlack}FgBlack${Color.Reset}
    ${Color.FgRed}FgRed${Color.Reset}
    ${Color.FgGreen}FgGreen${Color.Reset}
    ${Color.FgYellow}FgYellow${Color.Reset}
    ${Color.FgBlue}FgBlue${Color.Reset}
    ${Color.FgMagenta}FgMagenta${Color.Reset}
    ${Color.FgCyan}FgCyan${Color.Reset}
    ${Color.FgWhite}FgWhite${Color.Reset}
`)

// 'Bg' prefix for background
console.log(`
    ${Color.BgBlack}BgBlack${Color.Reset}
    ${Color.BgRed}BgRed${Color.Reset}
    ${Color.BgGreen}BgGreen${Color.Reset}
    ${Color.BgYellow}BgYellow${Color.Reset}
    ${Color.BgBlue}BgBlue${Color.Reset}
    ${Color.BgMagenta}BgMagenta${Color.Reset}
    ${Color.BgCyan}BgCyan${Color.Reset}
    ${Color.BgWhite}BgWhite${Color.Reset}
`)
```

#### Output :
![](https://media.discordapp.net/attachments/876815323549028392/1006629164385837137/Final_2.png)



## Authors

- [@69Nesta](https://www.github.com/69Nesta)

