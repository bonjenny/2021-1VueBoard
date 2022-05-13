## 시작 2021.3.30. ~ ing
- 참고1: Vuejs로 게시판 만들기, 개린이르라나
- 참고링크1: https://youtu.be/s1lXVr65KZg
- 참고2: node.js로 서버 만들기, 개린이르라나
- 링크2: https://youtu.be/4SUGu3YBZ_A
> 실행 방법: 해당 폴더로 이동, npm run dev 또는 yarn start

# npm 시작 (Node 설치되어있어야 함)
cd [PROJECT 폴더 경로]
npm install vue
npm -g add vue
npm -g add @vue/cli-init
vue init webpack vue-board
[Enter]
[Enter]
[Enter]
[Enter]
y
n
y
Jest
n
Yes, use NPM

-- To get started:
cd vue-board
npm run dev

-- Bootstrap-Vue
cd [PROJECT 폴더 경로]
vue init webpack bootstrap-bbs
[Enter]
[Enter]
[Enter]
y
n
y
Jest
n
Yes, use NPM

-- Bootstrap-Vue import
npm i vue bootstrap-vue bootstrap

-- src/main.js에 추가
import BootstrapVue from 'bootstrap-vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
Vue.use(BootstrapVue)

-- To get started:
cd bootstrap-bbs
npm run dev


# 7/20 - Module not Found 오류 해결
== module not found 오류 -> yarn으로 재시도 ==
$ npm install -g yarn
$ yarn --version

cd [PROJECT 폴더 경로]
yarn global add vue
yarn global add @vue/cli-init
vue init webpack vue-board
[Enter]
[Enter]
[Enter]
[Enter]
y
n
y
Jest
n
Yes, use Yarn

-- To get started:
cd vue-board
yarn start

-- Bootstrap-Vue
cd [PROJECT 폴더 경로]
vue init webpack bootstrap-bbs
[Enter]
[Enter]
[Enter]
y
n
y
Jest
n
Yes, use Yarn

-- Bootstrap-Vue import
yarn global add vue bootstrap-vue bootstrap

-- src/main.js에 추가
import BootstrapVue from 'bootstrap-vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
Vue.use(BootstrapVue)

-- To get started:
cd bootstrap-bbs
yarn start


# 8/20 - Command not Found 오류 해결
== webpack-dev-server: command not found 오류 -> webpack-dev-server 설치 후 재시도 ==

npm install webpack-dev-server --save-dev
-- To get started:
cd bootstrap-bbs
yarn start

# 8/26 - 참고할만한 문서 (Vue.js에 관해)
https://joshua1988.github.io/
