
```text
c[_]
COFFEESHOP
THE HTML5 SHELL
```

## Using CoffeeShop

[CoffeeShop][1] is a purely in-browser application. You only need a server to
serve the files to your browser. We host [an instance of the shell server][1]
on GitHub Pages. You are welcome to use it. The CoffeeShop user documentation
is built into the application.

## Hacking CoffeeShop

If you would like to run your own server or hack on the CoffeeShop source, you
easily can.

CoffeeShop is just a bunch of static files, so you can use any server, locally
or online. Cosh also only uses cross origin services, so it will work the same
way however it is hosted.

Note that local storage is always per-origin.

CoffeeShop will never have dependencies. Just use the `build` launch-code, and
the shell will build itself from source whenever you refresh the page.

    http://localhost:8080#build

If you host a server at `localhost:9090`, it will serve in gallery mode. The
actual Gallery lives on GitHub, and is shared by all users.

## Limitations

You must use a V8 based browser (Chromium, Chrome or Opera). No other engine
supports custom errors and named eval yet (FireFox has named eval now).

## Status

All of the main features are implemented, documented and stable.

Experienced programmers should find CoffeeShop useful now. Support for
new programmers is being worked on.

Currently, this is more or less a solo effort, but contributions are welcome,
and there are plans to do bigger things with CoffeeShop once it is ready.

## License

CoffeeShop is Free Software. A lot of CoffeeShop's parts come from third party
projects under their chosen [open source] licenses. All code and docs in this
repository are bundled together under the [GPLv3][2] for convenience.

[1]: https://coshmain.github.io/ "CoffeeShop"
[2]: http://www.gnu.org/licenses/gpl-3.0.html "GNU General Public License v3"
