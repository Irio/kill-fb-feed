# Kill FB Feed

Makes you more productive while using Facebook.

## Development process

With [Mozilla Add-on SDK](https://developer.mozilla.org/en-US/Add-ons/SDK/Tutorials/Installation) installed, run:

```sh
cfx run
```

This command will start a new Mozilla Firefox instance with the add-on installed.

## Release

Generate a new `.xpi` file in the root folder by running the following command:

```sh
cfx xpi
```

Then you can go to your Firefox, `File`, `Open…` and select the new `kil-fb-feed.xpi`.

## License

[MPL 2.0](https://www.mozilla.org/MPL/2.0/)
