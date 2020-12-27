<h1 align="center">Welcome to course-se 👋</h1>
<p>
</p>

> Get our codes for this course from ONE repo!

Since this is a complex application which contains varieties of languages, **there is no pre-built binary or out-of-box stuff for you Profs or TAs.** You are expected to build & deploy on your own.

However, **an online preview is available** [here](http://uniqs.cc:20202).

If the link above expired, please contact us.

## Fetch Repositories

WARNING: you may encounter "permission denied" because some of our repos are private. Just use the equivalent compress archive instead.

```shell
git clone --recurse-submodules --remote-submodules --depth 1 https://github.com/course-se/course-se
```

## Usage

### sudoku-arena

Front-end prototype, written in TypeScript with `Taro`.

Shipped with well-designed UI and support for multi-typed mini apps.

To build, make sure you have `node` and `yarn` installed.

```shell
# install all dependencies
yarn
# build a production bundle for browsers
yarn build:h5
# build a production for wechat mini apps
yarn build:miniapp
# or simply start a dev server
yarn dev:h5 # yarn dev:miniapp
```

## sudoku-master

Front-end implement for browsers, written in `Vue.js`. 

To build, make sure you have `node` and `yarn` installed.

```shell
# install all dependencies
yarn
# build a optimized production for browsers
yarn build
# or simply start a dev server
yarn serve
# you can also check lintings
yarn lint
```

## sudokuApi

Back-end services, written in Java with Spring Boot.

To build, test and deploy, please make sure you have `openjdk` installed and do follow Spring Boot's instructions.

## Sudoku-generation

Generate serialized Sudoku puzzles of different difficulties along with solutions.

`python` is required to run these scripts.

```shell
# generate 9x9 Sudoku puzzles
python create.py 
# generate serialized Sudoku puzzles for web transmission
python main.py 
```

## Show your support

Give a ⭐️ if this project helped you!