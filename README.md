# js-crdt-protocols

JS implementations of crdt-protocols.

## Install

```
npm i @organicdesign/crdt-protocols
```

## Usage

Import the protocol you want from this package:


```javascript
import { <MESSAGE TYPE> } from "@organicdesign/crdt-protocols/<PROTOCOL>"
```

For example:

```javascript
import { CounterData } from "@organicdesign/crdt-protocols/pn-counter"
```

## Updating

To update the scripts to the new version of crdt-protocols:

```
npm run submodule
npm run build
```
