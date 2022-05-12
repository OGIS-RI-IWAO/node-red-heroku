node-red-heroku
================

A wrapper for deploying [Node-RED](http://nodered.org) into the [Heroku](https://www.heroku.com).

## Node-RED v2.x on Heroku

forked by https://github.com/joeartsea/node-red-heroku
forked by https://github.com/n0bisuke/node-red-heroku

fork元からHerokuでNode-REDを動かすとパレット管理の追加ができなかったため、package.jsonのバージョンをより最新に変更しています。
また、fork元と同じくbuildpackとしてpostfresが入るようになっています。

### Deploying Node-RED into Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/OGIS-RI-IWAO/node-red-heroku)

### Password protect the flow editor

By default, the editor is open for anyone to access and modify flows. To password-protect the editor:

Add the following user-defined variables.

* NODE_RED_USERNAME - the username to secure the editor with
* NODE_RED_PASSWORD - the password to secure the editor with
