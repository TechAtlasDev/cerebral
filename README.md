# Mannual de instalación del proyecto

El proyecto usa Astro, pero en el frontend usa TailwindCSS, DaisyUI y React (React aún no ha sido instalado)

## Manual de instalación:

1. Clonar el repositorio: Para clonar el repositorio, nosotros tendremos que tener instalado el sistema de git en nuestro escritorio, luego de eso, tendremos que ejecutar el comando:

```bash
git clone https://github.com/techatlasdev/cerebral
```

2. Entrar a la carpeta del archivo clonado: Para movernos en la terminal con comandos, podemos usar el comando `cd`, así:

```bash
cd cerebral
```

3. Instalar el administrador de paquetes: El administrador de paquetes nos permitirá gestionar el proyecto de manera optima, rápida y fácil, existen muchos tipos de administradores, por ejemplo:
* NPM
* PNPM
* Bun

En este proyecto se usó Bun, pero puedes escoger el que quieras, si quieres usar bun, puedes visitar su web: https://bun.sh/

4. Instalar las dependencias con tu administrador de paquetes: Las dependencias son herramientas externas que nosotros estamos incluyendo al repositorio para poder hacer que el desarrollo de nuestra aplicación sea más fácil, por lo tanto, para indicarle a nuestro gestor de paquetes que instale las dependencias, dependerá del administrador de paquetes que hemos instalado, por ejemplo:

```bash
bun install
```

```bash
npm install
```
5. Iniciar el proyecto: Una vez las dependencias del proyecto estén instaladas, vamos a ejecutar el proyecto, el comando para hacerlo simplemente es con:

```bash
bun run dev
```

```bash
npm run dev
```

## Uso del proyecto

Este proyecto por defecto se iniciará en el puerto 4321, es decir, si quieres ver el proyecto, puedes entrar a: http://localhost:4321

Si quieres modificar el proyeccto, puedes entrar a la carpeta `src` para tener un contexto mas amplio de la organización del proyecto.