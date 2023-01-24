typescript

npm init 
npm i typescript
npm i ts-node --save-dev


tsconfig.json 생성 -> src 폴더 생성 -> index.tx 생성 

npx tsc 명령어 실행 하면 js로 컴파일 됨 

node dist/index.js

컴파일후 바로 실행
npx ts-node src/index.ts

자동화
package.json
"scripts": {
    "start" : "tsc & node dist/index.js"
}

