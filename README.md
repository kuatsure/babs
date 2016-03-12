# babs

### Install

```sh
$ npm install
```

### Running `babs` Locally

You can test your hubot by running the following, however some plugins will not behave as expected unless the environment variables they rely upon have been set.

You can start `babs` locally by running:

```sh
$ bin/hubot
```

You'll see some start up output and a prompt:

```sh
[Sat Feb 28 2015 12:38:27 GMT+0000 (GMT)] INFO Using default redis on localhost:6379
babs>
```

Then you can interact with `babs` by typing `babs help`.

```sh
babs> babs help
babs animate me <query> - The same thing as `image me`, except adds [snip]
babs help - Displays all of the help commands that babs knows about.
...
```
