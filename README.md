# React-Reproduction5

**"React-Reproduction5"** は create-react-app の練習作成です

## 作成環境

- npm 6.14.13
- prettier 2.8.3
- eslint 8.33.0

## 使い方

1. `$ npm start` とターミナルにて入力で起動します
2. ブラウザにて "http://localhost:3000/" を開くと表示されます
3. ターミナルにて **"Crtl + c"** または **"cmd + c"** で停止します

## インストール

```
$ git clone https://github.com/kamiyakoh/react-reproduction5  
$ cd react-reproduction5  
$ npm install
```

## eslint

`$ npm init @eslint/config` を用いて以下の設定内容で設定しました

> How would you like to use ESLint? · style  
> What type of modules does your project use? · esm  
> Which framework does your project use? · react  
> Does your project use TypeScript? · No  
> Where does your code run? · browser  
> How would you like to define a style for your project? · guide  
> Which style guide do you want to follow? · airbnb    
> What format do you want your config file to be in? · JSON  
> 
> Would you like to install them now? · Yes  
> Which package manager do you want to use? · npm

- parser に "babel-eslint" を指定しました
- extends に "prettier" を指定し prettier との競合を抑制しました

## prettier

エディタがVSCodeの場合、拡張機能に ***"Prettier - Code formatter"*** をインストールし有効化すると保存時に自動成形を行います  
prettier の設定は以下の設定です

- "tabWidth": 2, //インデントのスペースの数 2  
- "singleQuote": true, //ダブルクォートの代わりにシングルクォートを使用するを有効に  
- "semi": true //文末にセミコロンを追加する
