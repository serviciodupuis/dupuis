# Changelog
Todos los cambios importantes seran registrados en este documento.


## [0.0.5] - 2021-10-11
### Added
- Validar curso de accion solo basado en el item type y no en el digito con el que comienza el sku

## [0.0.4] - 2021-08-11
### Added
- Validación viajarIpos = 0 para cuando se quiere eliminar items de IPOS

## [0.0.3] - 2021-00-03

### Fixed
- valores de propagación en variables en Lambda.

### Added
- Validación contenido tags.
- Validación contenido dimensiones, cuando contienes comas.

## [0.0.2] - 2021-07-30
Liberacion oficial de la interface en ambiente de producción.

### Fixed
- Validación de variables en Lambda.
- Validación manejo de imágenes en Lambda.
- Corrección integración recuperación de precio OIC.

### Added
- Validación Precio, si el precio es menor a 1, termina la ejecución de la integración
- Configuracion, validacion imagenes para items
- Formato descripción extedida
- Formato nuevos valores tags

### Removed
- logs innecesarios

## [0.0.1] - 2021-07-28
Version inicial de la interface 2.0 de propagación de items