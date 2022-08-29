<!-- @format -->

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)]()
[![Version](https://img.shields.io/npm/v/progress-circle-react-native.svg)](https://www.npmjs.com/package/progress-circle-react-native)
[![npm](https://img.shields.io/npm/dt/progress-circle-react-native.svg)](https://www.npmjs.com/package/progress-circle-react-native)
[![Twitter Follow](https://img.shields.io/twitter/follow/cmichelio.svg?style=social&label=Follow)](https://twitter.com/randrul)

# Progress Circle React Native

![Progress Circles React Native](/README/featured.png?raw=true "Progress Circles React Native")

`This package was created to fix the dependency issues on the original package` [here](https://github.com/MrToph/react-native-progress-circle)

## Features

- Custom colors
- Custom size and border radius
- Light-weight: No other dependencies besides `react-native`

## Installation

`yarn add progress-circle-react-native`

or

`npm install --save progress-circle-react-native`

## Usage

```javascript
import ProgressCircle from 'progress-circle-react-native'

render() {
    return (
        <ProgressCircle
            percent={30}
            radius={50}
            borderWidth={8}
            color="#3399FF"
            shadowColor="#999"
            bgColor="#fff"
        >
            <Text style={{ fontSize: 18 }}>{'30%'}</Text>
        </ProgressCircle>
    )
}
```

## Props

| Name             | Description                                                                 | Type   | Required |                            Default Value                             |
| :--------------- | :-------------------------------------------------------------------------- | :----- | :------: | :------------------------------------------------------------------: |
| percent          | The percentage used for displaying the progress                             | Number |    ✓     |                                                                      |
| radius           | The radius in `px` of the component (including border)                      | Number |    ✓     |                                                                      |
| borderWidth      | The border width in `px`                                                    | Number |    ✓     |                                                                      |
| color            | The border color                                                            | String |          |     ![#f00](https://placehold.it/15/f00/000000?text=+) `'#f00'`      |
| shadowColor      | The background color of the border                                          | String |          |     ![#999](https://placehold.it/15/999/000000?text=+) `'#999'`      |
| bgColor          | The inner background color of the component                                 | String |          | ![#e9e9ef](https://placehold.it/15/e9e9ef/000000?text=+) `'#e9e9ef'` |
| children         | The children to render inside this component                                | Node   |          |                                `null`                                |
| containerStyle   | The custom styling which will be applied to the container of the `children` | Style  |          |                                `null`                                |
| outerCircleStyle | The custom styling which will be applied to the outer circle                | Style  |          |                                `null`                                |

## Author

Boma Amakiri

## License

MIT
