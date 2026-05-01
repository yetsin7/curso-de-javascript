# Curso de JavaScript — De cero a PRO

Curso práctico para aprender JavaScript moderno desde cero, entendiendo cómo se
ejecuta el código tanto en Node.js como en el navegador.

Repositorio oficial: <https://github.com/yetsin7/Curso-de-JavaScript>

---

## 🇳🇮 Para estudiantes de Nicaragua (y de toda Latinoamérica)

Hola. Si estás leyendo esto desde Managua, León, Estelí, Granada, Matagalpa,
Bluefields o cualquier rincón de Nicaragua, este libro fue pensado para ti.

También es completamente útil si estás en Honduras, El Salvador, Guatemala,
Costa Rica, Panamá, México, Colombia, Venezuela, Perú o cualquier otro país
de habla hispana. La programación no entiende de fronteras, y este recurso
tampoco.

No necesitas pagar un curso caro. No necesitas registrarte en ninguna
plataforma. No necesitas internet permanente: una vez que clonas el repositorio,
puedes estudiar **sin conexión**, desde tu computadora, a tu propio ritmo.

## 🎯 ¿Por qué existe este libro?

La misión es sencilla: que más nicaragüenses aprendan a programar.

En Nicaragua existen muchísimos jóvenes con talento que quieren entrar al mundo
de la programación, pero se topan con tres barreras:

1. **El costo.** Los cursos buenos suelen ser caros y se pagan en dólares.
2. **El internet.** No siempre hay conexión estable para ver videos en línea.
3. **El idioma.** Mucho del mejor material está en inglés.

Este libro intenta resolver esas tres barreras a la vez:

- Es **100% gratuito**, para siempre.
- Funciona **offline** una vez que clonas el repositorio.
- Está escrito en **español claro y natural**, con comentarios y explicaciones
  pensadas para que cualquier persona pueda entenderlas, sin importar su nivel.
- **No requiere registro**, ni correo, ni tarjeta, ni nada.
- **No recolecta datos.** Tu aprendizaje es solo tuyo.

Si este libro te ayuda a dar tus primeros pasos como programador o programadora,
la misión está cumplida.

---

## 👤 ¿Para quién es este libro?

- Personas que nunca han programado en JavaScript
- Estudiantes y autodidactas que aprenden por su cuenta
- Desarrolladores de otros lenguajes que quieren aprender JS
- Quienes quieren actualizar su conocimiento al estándar moderno
- Personas que quieren entender qué hace el navegador o Node cuando corre código

## 📚 Qué vas a aprender

Este libro no se enfoca solo en "qué escribir". También explica:

- cómo JavaScript interpreta instrucciones;
- cómo se crean variables y objetos en memoria;
- cómo la consola, el DOM o Node muestran resultados;
- cómo funciona la asincronía a nivel de software;
- cómo pensar mejor los errores y depurarlos.

---

## ⚙️ Requisitos

- **Node.js** v18 o superior instalado → [nodejs.org](https://nodejs.org)
- **VS Code** recomendado → [code.visualstudio.com](https://code.visualstudio.com)
- Extensión de VS Code: **ESLint** (opcional pero recomendada)

### Verificar instalación de Node.js

```bash
node --version
# Debe mostrar algo como: v20.x.x o superior
```

---

## 🚀 Cómo usar este repositorio

1. Clona o descarga el repositorio
2. Abre la carpeta en VS Code
3. Navega al módulo que te interese
4. Ejecuta cualquier archivo con:

```bash
node nombre_del_archivo.js
```

Ejemplo:

```bash
node 01-fundamentos/01_hola_mundo.js
```

Lee los comentarios en el código como si fueran parte de la clase.

> 💡 **Tip para estudiar sin internet:** una vez clonado el repo, no necesitas
> volver a conectarte. Puedes estudiar desde cualquier lugar, incluso si la
> conexión se va.

## 🧠 Qué ocurre cuando JavaScript se ejecuta

Si ejecutas un archivo con Node.js:

- Node carga el motor de JavaScript;
- el motor analiza el código;
- reserva memoria para variables, funciones y objetos;
- ejecuta instrucciones;
- escribe resultados en consola o interactúa con archivos y red.

Si ejecutas JavaScript en el navegador:

- el navegador descarga HTML, CSS y JS;
- crea el DOM;
- ejecuta el script;
- responde a eventos del usuario como clics o escritura;
- actualiza la interfaz en pantalla.

---

## 🗂️ Estructura del repositorio

| Nivel | Módulo | Tema | Archivos |
|-------|--------|------|----------|
| 🟢 **Básico** | `01-fundamentos/` | Variables, tipos, template literals | 01–06 |
| 🟢 **Básico** | `02-tipos-de-datos/` | Strings, numbers, booleans, null/undefined | 01–05 |
| 🟢 **Básico** | `03-operadores/` | Aritmética, comparación, lógicos, spread | 01–05 |
| 🟢 **Básico** | `04-control-de-flujo/` | if/else, for, while, break/continue | 01–05 |
| 🟢 **Básico** | `05-funciones/` | Declaradas, arrows, closures, HOF | 01–06 |
| 🟡 **Medio** | `06-arrays/` | Métodos de array, desestructuración | 01–05 |
| 🟡 **Medio** | `07-objetos/` | Objetos, prototipos, clases ES6+ | 01–05 |
| 🟡 **Medio** | `08-async/` | Callbacks, Promises, async/await | 01–05 |
| 🟡 **Medio** | `09-módulos/` | import/export, CommonJS, ES Modules | 01–04 |
| 🟡 **Medio** | `10-dom/` | Manipulación del DOM, eventos | 01–05 |
| 🟡 **Medio** | `11-apis/` | fetch, REST APIs, JSON | 01–04 |
| 🔴 **Avanzado** | `12-node-fs/` | File system, streams, buffers | 01–04 |
| 🔴 **Avanzado** | `13-express/` | Servidor HTTP, rutas, middlewares | 01–05 |
| 🔴 **Avanzado** | `14-typescript/` | Tipos, interfaces, generics | 01–05 |
| 🔴 **Avanzado** | `15-testing/` | Jest, unit tests, mocks | 01–04 |
| 🔴 **Avanzado** | `16-react-intro/` | Componentes, hooks, estado | 01–05 |
| 🔴 **Avanzado** | `17-patrones/` | Design patterns en JS | 01–05 |

---

## 💻 Instalar Node.js

### Windows
1. Ve a [nodejs.org](https://nodejs.org)
2. Descarga la versión **LTS** (recomendada para producción)
3. Ejecuta el instalador y sigue los pasos
4. Abre una terminal nueva y ejecuta `node --version`

### macOS (con Homebrew)
```bash
brew install node
```

### Linux (Ubuntu/Debian)
```bash
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
```

---

## 📖 Consejos para aprender bien

1. **No copies y pegues** — escribe el código a mano para que lo memorices
2. **Ejecuta cada archivo** y observa la salida antes de seguir
3. **Haz los ejercicios** del final de cada módulo antes de ver la solución
4. **Experimenta** cambiando valores, rompiendo el código y arreglándolo
5. **Lee los comentarios** — son la explicación del concepto
6. **Revisa el README** de cada módulo antes de empezar los archivos
7. **Practica todos los días** — aunque sea 20 minutos

---

## ⚠️ Errores comunes

- Creer que `var`, `let` y `const` son iguales.
- Ejecutar sin observar la salida real.
- Confundir código de Node con código del navegador.
- Querer memorizar todo sin practicar.
- Ignorar errores de consola en lugar de leerlos.

## 📂 Carpeta `datos/`

Contiene una base de datos SQLite con la Biblia (RV60) para practicar
consultas reales con Node.js. Ver `datos/README.md` para detalles.

---

## ❤️ Cómo apoyar este proyecto

Este libro crece gracias a la comunidad. Si te ha sido útil, hay varias formas
de ayudar a que llegue a más estudiantes nicaragüenses y latinoamericanos:

- ⭐ **Dale una estrella al repositorio** en GitHub. Eso le da visibilidad y
  ayuda a que más personas lo encuentren.
- 🤝 **Compártelo** con amigos, compañeros de clase, familiares o cualquier
  persona que quiera aprender a programar. Un mensaje de WhatsApp puede cambiar
  la vida profesional de alguien.
- 🐛 **Abre un issue** si encuentras un error, una explicación confusa o un
  tema que crees que falta. Toda retroalimentación es bienvenida.
- 🔧 **Envía un pull request** si quieres mejorar un capítulo, corregir un
  ejemplo o agregar contenido. Las contribuciones son bienvenidas.
- 📣 **Cuenta tu experiencia.** Si aprendiste algo con este libro, contarlo
  motiva a otros a empezar.

Enlace directo: <https://github.com/yetsin7/Curso-de-JavaScript>

---

## 📝 Licencia

Este repositorio es de uso libre para fines educativos.
Puedes compartirlo, modificarlo y usarlo como quieras.

Hecho con cariño desde Nicaragua para el mundo. 🇳🇮
