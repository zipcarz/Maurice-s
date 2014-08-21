Maurice-s
=========
Using worker: worker-linux-8-1.bb.travis-ci.org:travis-linux-20
git.1
1.28s$ git clone --depth=50 --branch=master git://github.com/LLK/scratch-flash.git LLK/scratch-flash
Cloning into 'LLK/scratch-flash'...
remote: Counting objects: 2843, done.
remote: Compressing objects: 100% (982/982), done.
remote: Total 2843 (delta 1853), reused 2832 (delta 1847)
Receiving objects: 100% (2843/2843), 5.06 MiB | 0 bytes/s, done.
Resolving deltas: 100% (1853/1853), done.
Checking connectivity... done.
$ cd LLK/scratch-flash
git.3
$ git checkout -qf c460fc289f31913310d14fdef3ced0a64369c1a3
0.76s$ nvm install 0.10
######################################################################## 100.0%
Now using node v0.10.31
1.38s0.02s$ node --version
v0.10.31
0.71s$ npm --version
1.4.23
install
83.24s$ npm install 
> flex-sdk@4.6.0-0 preinstall /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk
> npm install playerglobal-latest
> playerglobal-latest@0.1.6 install /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk/node_modules/playerglobal-latest
> node install.js
Successfully downloaded "nexussays/playerglobal" to:
    /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk/node_modules/playerglobal-latest/lib
playerglobal-latest@0.1.6 node_modules/playerglobal-latest
├── mkdirp@0.3.5
├── rimraf@2.2.8
├── ncp@0.5.1
├── async@0.6.2
└── download-github-repo@0.1.3 (download@0.1.18)
> flex-sdk@4.6.0-0 install /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk
> npm config set $npm_package_name:npm_cmd_ran install
> flex-sdk@4.6.0-0 postinstall /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk
> node install.js
Successfully installed the latest "playerglobal.swc" library collection.
flex-sdk@4.6.0-0 node_modules/flex-sdk
└── mkdirp@0.3.5
before_script
83.51s$ npm install flex-sdk
> flex-sdk@4.6.0-0 preinstall /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk
> npm install playerglobal-latest
> playerglobal-latest@0.1.6 install /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk/node_modules/playerglobal-latest
> node install.js
Successfully downloaded "nexussays/playerglobal" to:
    /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk/node_modules/playerglobal-latest/lib
playerglobal-latest@0.1.6 node_modules/playerglobal-latest
├── rimraf@2.2.8
├── ncp@0.5.1
├── mkdirp@0.3.5
├── async@0.6.2
└── download-github-repo@0.1.3 (download@0.1.18)
> flex-sdk@4.6.0-0 install /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk
> npm config set $npm_package_name:npm_cmd_ran install
> flex-sdk@4.6.0-0 postinstall /home/travis/build/LLK/scratch-flash/node_modules/flex-sdk
> node install.js
Successfully installed the latest "playerglobal.swc" library collection.
flex-sdk@4.6.0-0 node_modules/flex-sdk
└── mkdirp@0.3.5
46.79s$ npm test
> Scratch@1.0.0 test /home/travis/build/LLK/scratch-flash
> node tests/build.js
The command "npm test" exited with 0.
Done. Your build exited with 0.
