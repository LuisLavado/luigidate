# luigidate

Una utilidad para manejar fechas en formato timestamp y long time.

## Install

```
# bash
npm install luigidate
```

## How to use it
```
// Import it with `require`
const dateFormatter = require('luigidate');

// Obtener timestamp actual
console.log(dateFormatter.getTimeStamp());

// Obtener fecha en español (formato por defecto)
console.log(dateFormatter.getLongTime());

// Obtener fecha en inglés
console.log(dateFormatter.getLongTime('en-US'));
```

