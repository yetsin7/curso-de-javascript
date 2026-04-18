# Carpeta `datos/` — Recursos del Libro de JavaScript

Esta carpeta contiene la base de datos propia de este curso. Aquí se guarda la
copia local de `biblia_rv60.sqlite3` que usan los ejercicios y proyectos del
repositorio.

Ruta relativa desde cualquier capítulo de este libro:

```javascript
import path from 'path';
import { fileURLToPath } from 'url';

const __dirname = path.dirname(fileURLToPath(import.meta.url));
const DB_PATH = path.join(__dirname, '..', '..', 'datos', 'biblia_rv60.sqlite3');
```

O con CommonJS:

```javascript
const path = require('path');
const DB_PATH = path.join(__dirname, '..', '..', 'datos', 'biblia_rv60.sqlite3');
```

Puedes modificar esta base sin afectar a los demás cursos.
