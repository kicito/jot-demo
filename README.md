# jot example

Note:
at the moment, steps to adding jot
1. `npm init jolie` to create a jolie project
2. `jpm add @jolie/jot` to add jot as a dependency
3.  copy `assertions` package from jot to local's package
4.  create symlink to jot.sh, place in .bin file for node to recognize  `ln -s ../../packages/@jolie/jot/bin/jot.sh ./node_modules/.bin/jot`
5.  add test script to package.json `"test": "jot"`
6.  run `jot` with `npm run test -- -p ./jot.json`

TODO:
- Move `assertions` to jpm?
- `jpm` reads "bin" field from package.json and make symlink to node_modules