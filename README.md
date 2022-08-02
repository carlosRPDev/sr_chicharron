# Sr Chicharron

Este es un proyecto tipo E-Commerce, el cual esta basado en la comercializacion de productos terminados, empacados y distribuidos para el cosumo humano derivados del cerdos.

Teniendo en cuenta el alto impacto que ha tenido la digitalizacion de emprendimientos, queremos implementar una aplicacion web la cual sea un nuevo canal para la comercializacion de los productos.

Todo ello con el objetivo primordial el aprendizaje. Para ello ese proyecto tiene como fin ser presentado como requerimiento para el BootCamp de Rails de CodigoFacilito

## Tecnologias

* Ruby 3.1.1
* Rails 7.0.3
* Yarn 1.22.10
* PostgreSQL 13.3

## Correr el proyecto en local

### Clonar el proyecto

```shell
git clone git@github.com:carlosRPDev/sr_chicharron.git

cd sr_chicharron
```

### Instalar la dependencias

Usando [Bundler](https://github.com/bundler/bundler) y [Yarn](https://github.com/yarnpkg/yarn):

```shell
bundle && yarn
```

### Preparar la base de datos

```shell
rails db:create
rails db:migrate
```
  
## Iniciar el servidor

```shell
rails s
```
