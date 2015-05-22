# koco-signal-emitter
Koco wrapper for [Signal Emitter](http://blog.millermedeiros.com/signal-emitter/), itself a JS-Signals wrapper to convert it into a regular event emitter.

## Installation

```bash
bower install koco-signal-emitter
```

## Usage with KOCO

This is a shared module that is used in many other module. The convention is to configure an alias in the `require.configs.js` with the name `signal-emitter` like so:

```javascript
paths: {
  ...
  'signal-emitter': 'bower_components/koco-signal-emitter/src/signal-emitter'
  ...
}
```