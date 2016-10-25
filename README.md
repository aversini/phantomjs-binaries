# Mirror for Phantomjs binaries
Phantomjs binaries are hosted on github, and their links are redirected to AWS. If your local proxy/firewall prevents access to AWS, you can force phantomjs to use this mirror by overriding one of phantomjs parameters. 3 possibilities:

## Environment variable
`export PHANTOMJS_CDNURL=https://github.com/aversini/phantomjs-binaries/raw/master/`

## .npmrc configuration file
`npm config set phantomjs_cdnurl https://github.com/aversini/phantomjs-binaries/raw/master/`

## Process argument
`npm install node-sass --phantomjs_cdnurl==https://github.com/aversini/phantomjs-binaries/raw/master/`
