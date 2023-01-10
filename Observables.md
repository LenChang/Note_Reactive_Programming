# Promise vs. Observalbe
> A Promise handles a **single event** when an async operation completes or fails.

> An Observable is like a **Stream** (in many languages) and allows to pass zero or more events where the callback is called for each event.

## Oftern Observalbe is perferred ove Promise ...
- Observable could handle 0, 1, or multiple events, however Promise only handle the event
- Observable could be cancellable.
- **Promise** starts immediately; **Observalbe** only starts if you subscribe to it. That's why Observalbe is called *Lazy execution*

## Reference
- https://stackoverflow.com/questions/37364973/what-is-the-difference-between-promises-and-observables
