# Neumorphism_Progress

一Neumorphism Progress design for OpenHarmony.

## Download & Install

Install using npm

```npm i hmos-neumorphism ```
Details about OpenHarmony NPM environment configuration, see at [here](https://gitee.com/openharmony-tpc/docs/blob/master/OpenHarmony_npm_usage.md)


# Progress

<img src="sample_images/progressbar.png" width="" height="">

Import:
```html
<element name='neuprogress' src='hmos-neumorphism/progress/progress.hml'></element>
```

Usage:
```html
<neuprogress progress="80%" width="300px" color="" height="20px" border="50px"></neuprogress>
```

## Compatibility
Supports OpenHarmony API version 6 

## Directory Structure
````
|---- Neumorphism  
|     |---- entry  # sample app usage
|     |---- Neumorphism  # Neumorphism library
|           |---- progress  # Progress Component
|                 |---- progress.css  # Progress style component
|                 |---- progress.hml  # Progress hml file
|     |---- README.MD  # installation and usage                   
````
## Code Contribution
If you find any problems during usage, you can submit an [Issue](https://gitee.com/openharmony-sig/progress/issues) to us. Of course, we also welcome you to send us [PR](https://gitee.com/openharmony-sig/progress/pulls).

## Open source License
This project is based on [Apache License 2.0](https://gitee.com/openharmony-sig/progress/blob/master/LICENSE.txt) ，please enjoy and participate in open source freely.

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>
