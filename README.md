# click-in-click-event-handler

If `click()` is called in a click event handler, then what is the result?

My thought is that it would enter an infinite call, but this is not true.

## Tests

Here are the tests.

- [project pages](https://yanxyz.github.io/click-in-click-event-handler/)
- [project source](https://github.com/yanxyz/click-in-click-event-handler/)

The click event handler will:

- [call `.click()`](./click.html)
- [dispatch a click event created by MouseEvent](./MouseEvent.html)
- [dispatch a click event created by initMouseEvent](./initMouseEvent.html)
- [call jQuery .click()](./jq.html)

## Why

I have asked on [StackOverflow](http://stackoverflow.com/questions/43798336/click-in-click-event-handler).

I have not found out why.

- [`element.click()`](https://html.spec.whatwg.org/multipage/interaction.html#dom-click)
