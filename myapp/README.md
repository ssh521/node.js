## 서버세팅에 관련된 내용은 아래 링크를 참조
[서버세팅](https://github.com/ssh521/node.js/wiki/Node.js-%EC%84%9C%EB%B2%84%EC%84%B8%ED%8C%85-%EB%B0%A9%EB%B2%95)

## 다른 컴퓨터에서 실행할때

#### 다음코드를 실행해서 버전정보가 나오도록 설치해둔다.
    >node -v
    >npm -v     

    // myapp 폴더 명령줄에서
    >npm install

    // backend 폴더 명령줄에서
    >npm install

    // myapp 폴더에서
    >npm start

<br>

## nodemon 적용시키기     

<br>

### 코드 변경시 즉시 코드내용을 적용시켜주는 모듈입니다.

    npm install -g nodemon

### package.json 파일내용 수정하기
    
    "scripts": {
        "start": "nodemon ./bin/www"
    },


### 서버실행하기

    npm start

    [nodemon] 2.0.14
    [nodemon] to restart at any time, enter `rs`
    [nodemon] watching path(s): *.*
    [nodemon] watching extensions: js,mjs,json
    [nodemon] starting `node ./bin/www`



