# WanMask Inpage Provider

Used to initialize the inpage ethereum provider injected by WanMask.

## Installation

`npm install wanmask-inpage-provider -S`

## Usage

```javascript
// Create a stream to a remote provider:
var wanmaskStream = new LocalMessageDuplexStream({
  name: 'inpage',
  target: 'contentscript',
})

// compose the inpage provider
var inpageProvider = new WanmaskInpageProvider(wanmaskStream)
```
