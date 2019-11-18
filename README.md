# closure-heap

This is an implementation of a [Heap][] datastructure.  Smaller keys rise to
the top.

This implementation is extracted from the [Google Closure Library][].

## Usage

```js
const Heap = require('closure-heap')

const h = new Heap
h.insert(3, 'sheep')
h.insert(1, 'goat')
h.insert(2, 'chicken')

console.log(h.remove())
// => goat
```

See the [Closure docs][] (or take a look at the source) for additional
documentation.

[Heap]: https://en.wikipedia.org/wiki/Heap_%28data_structure%29
[Google Closure Library]: https://github.com/google/closure-library/blob/master/closure/goog/structs/heap.js
[Closure docs]: https://google.github.io/closure-library/api/goog.structs.Heap.html
