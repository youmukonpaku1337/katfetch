# shellfetch
A simple fetch script in BASH

# How do I install shellfetch?

```sh
$ sudo install -Dm755 shellcheck /usr/local/bin
$ mkdir -p ~/.config/shellcheck/
$ install -Dm600 config ~/.config/shellcheck/
```

And then install `figlet` using your package manager,
well if you don't use custom ASCII art using the `-a` or `--art` flag(s)

# Configuration

Configure shellfetch in the `~/.config/shellfetch/config` file
<!-- TODO: config documentation, how to configure it -->

# How do I use shellfetch?
Just run shellfetch, you can also set colors in config file
```sh
$ shellfetch
```

You can also pass some flags which can be found [here](/shellfetch#L23...L41)

Reference: https://gist.github.com/Prakasaka/219fe5695beeb4d6311583e79933a009

# Example
![image of shellfetch](https://user-images.githubusercontent.com/50289495/153940629-78bee967-d344-4e8a-9830-610b2fae16c8.png)
