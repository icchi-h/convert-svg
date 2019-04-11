# Install
`npm install`だとサブディレクトリ内のパッケージをインストールできないため、ローカルにダウンロードしてインストールする流れ。


```
# setup convert-svg-to-jpeg module for local
cd <module path>
git clone https://github.com/icchi-h/convert-svg.git
cd convert-svg/packages/convert-svg-to-jpeg
yarn # or npm install
yarn link

# install on asahi-map
cd <asahi-map module path>
yarn link convert-svg-to-jpeg
```
