# Modifications

- Wendertron sends a extra request header: `x-is-wendertron: true`
- Wendertron declares a global variable called `wendertronWait` which is set to `null`. Wendertron will await this value before serializing the page.
