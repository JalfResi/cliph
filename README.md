# Cliph

PHP Command line test program using Box2 to build a phar.

## Build

Install Box2 like so:

```sh
curl -LSs https://box-project.github.io/box2/installer.php | php
```

The command will check your PHP settings, warn you of any issues, and the download it to the current directory. From there, you may place it anywhere that will make it easier for you to access (such as `/usr/local/bin`) and chmod it to `755`. You can even rename it to just `box` to avoid having to type the `.phar` extension every time.

Now build the Phar like so:

```sh
box build -v
```

Which should result in the cliph.phar file being generated in the current directory.


