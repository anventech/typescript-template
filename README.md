# TypeScript Template

Plantilla para un proyecto de TypeScript.

## Descripción

Esta es una plantilla para un proyecto escrito en TypeScript, par a los que no sepan qué es TypeScript:

```
TypeScript es un lenguaje de programación libre y de código abierto desarrollado y mantenido por Microsoft. Es un superconjunto de JavaScript, que esencialmente añade tipos estáticos y objetos basados en clases.
```

Fuente: [TypeScript - Wikipedia, la enciclopedia libre](https://es.wikipedia.org/wiki/TypeScript)

## Luego de clonar el repositorio

Luego de clonar o descargar el repositorio, ejecutamos el siguiente comando dentro de la carpeta donde hayamos puesto todo:

```
npm install
```

Este comando instalará todos los paquetes que requiere la plantilla. (ver `package.json` si hay alguna duda)

## Estructura de los archivos

```
- source (Código fuente original)
	hello.ts (Archivo original)
- transpiled (Código fuente transpilado)
	hello.js (Archivo transpilado)
.eslintrc.json (Archivo de configuración del linter)
.gitignore (Archivo para ignorar otros archivos al momento de hacer push)
package-lock.json (Archivo de información detallada de los paquetes de NPM)
package.json (Archivo de información de los paquetes de NPM)
tsconfig.json (Archivo de configuración del transpilador)
```

## Transpilar el código fuente

Para transpilar (o compilar) el código fuente, tenemos que ejecutar este comando:

```
npx tsc
```

Este comando hará que todo el contenido que esté en la carpeta `source`, se transpile (convierta en código de JavaScript) y se mueva a la carpeta `transpiled`.

## Créditos

Esta plantilla fue hecha siguiendo las siguientes guías:

[How To Set Up a New TypeScript Project | DigitalOcean](https://www.digitalocean.com/community/tutorials/typescript-new-project)

[Setting up a linter | Discord.js Guide](https://discordjs.guide/preparations/setting-up-a-linter.html)

## Contactar al creador

Si quieres contactar al creador de este repositorio puedes hacerlo a través de:

**Discord:** Anventec#8287

**Servidor de Discord:** [discord.gg/XvmUX9wph3](https://discord.gg/XvmUX9wph3)

**Twitter:** [@anventec](https://twitter.com/anventec)