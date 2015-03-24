
```text
c[_]
COFFEESHOP
THE HTML5 SHELL
```

CoffeeShop is a purely in-browser application. You only need a server to
serve the files to your browser. We host [an instance of the shell server][1]
on GitHub. You are welcome to use that URL.

If you would like to publish or push to GitHub Gist, you will need a GitHub
account. CoffeeShop does not need an account system.

### Hosting and Hacking

If you would like to run your own server or hack on the CoffeeShop source, you
can host you own instances easily.

The entire application is just a bunch of static files, so you can serve it
from any server, locally or online. Cosh also only uses cross origin services,
so that the app will work the same way however it is hosted. Note that local
storage is always per-origin.

If you are hacking on CoffeeShop itself, you also only need a static file
server on your local machine; there are no dependencies or build tools. Just
edit the CoffeeScript and Markdown source, then use the `build` launch code
to force the shell to rebuild itself from source.

    http://localhost:8080#build

If you host your dev server at `localhost:9090`, it will serve in gallery mode.
In gallery mode, the app always builds from source, as nothing persists. The
actual Gallery lives on GitHub, and is shared by all users.

### Limitations

You must use a V8 based browser (Chromium, Chrome or Opera). FireFox support
is possible and planned, but not a priority.

### Status

All of the main features are implemented, documented and stable.

Experienced programmers should find CoffeeShop useful now. Support for
new programmers is being worked on.

Currently, this is more or less a solo effort, but contributions are welcome,
and there are plans to do bigger things with CoffeeShop once it is ready.

### License

CoffeeShop is Free Software. A lot of CoffeeShop's parts come from third party
projects under their chosen [open source] licenses. All code and docs in this
repository are bundled together under the [GPLv3][2] for convenience.

[1]: https://coshmain.github.io/ "CoffeeShop"
[2]: http://www.gnu.org/licenses/gpl-3.0.html "GNU General Public License v3"
