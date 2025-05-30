# Steps to reproduce

1. run `npm install`
2. configure the snippet

```json
{
  "Console Log": {
    "prefix": "clog",
    "body": ["console.log($0);"],
    "description": "Log a value"
  }
}
```

3. edit `main.ts`
4. type `clo` wait for the completion popup to display
5. type `g` and press `enter` in very quick succession.

It doesn't happen every time, but it does happen fairly regurlarly.
