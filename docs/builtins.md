# Builtins

To be a nice programming environment, the browser needs some extras.

CoffeeShop takes some liberties with the global namespace. [This article][1]
from the SugarJS developers helps explain how. The [SugarJS][2] library has
been applied wholesale, extending the builtin types with a large collection
of useful methods.

As ever, [jQuery][3] is available globally as `jQuery` and `$`.

## Shell Functions

Cosh adds a set of twelve functions designed for shell style programming. For example, this code clones a gist, saves it, then opens it in the editor:

    edit set clone "98f97a41924ca81c9863"

The [Output Functions](/docs/output.md) (`put`, `peg` and `print`) are used to
render things to the board.

The [Storage Functions](/docs/storage.md) (`set`, `get` and `pop`) are used to
store and retrieve JSON values in local storage.

The [Chit Functions](/docs/chits.md) (`run`, `edit`, and `chit`) are used to
run, edit and create chits. Chits are basically just files (that use JSON)
and are explained properly later.

The [Gist Functions](/docs/gists.md) (`clone`, `publish` and `push`) are used
for cloning, creating and managing gists on GitHub.

## Loose Ends

Anything not defined on this page may change without notice.

- `gallery` A function that takes a gist ID and opens the gist in the Gallery
- `galleryMode` A bool that is `true` in the Gallery and is `false` otherwise
- `uniquePIN` A parameterless function that returns a unique integer per call
- `uniqueID` A parameterless function that returns a unique string per call

[1]: http://sugarjs.com/native
[2]: http://sugarjs.com
[3]: http://jquery.com
