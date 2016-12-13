# frontendDevelopment  
フロントエンド開発のテンプレート  
  
  
## Feature  
*HTMLHint  
*SASS  
*autoprefixer  
*coffeeScript  
*typeScript  
*css,jsのminify  
*画像の圧縮  
*スプライト画像の生成  
  
  
## フォルダ構成  
/_dev  
┣ Gulpfiles.js - gulpファイル  
┣ package.json - npmパッケージ設定ファイル  
┣ .htmlhintrc  - htmlhint設定ファイル  
┣ /cs          - coffeeScript  
┣ /ts          - typeScript  
┣ /sass        - sass  
┣ /sprite      - sprite元画像  
  
/htdocs  
┣ /_inc - 読み込み用フォルダ  
┣ /img  - 画像フォルダ  
┣ /js   - jsフォルダ  
┣ /css  - cssフォルダ  
  
  
## how to use  
### set up  
npm install  

### watch  
gulp  
  
### css,js,img minify  
gulp min  
  
### img sprite  
gulp sprite  
/htdocs/img に画像生成  
/_dev/sass/base/ にsassが生成  
  
  