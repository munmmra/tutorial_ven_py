# Tutotial para la configuración de un ambiente viertual con venv

## Que es venv?
Venv es un módiulo de python para la creación de "entornos virtuales",
Es una herramienta usada para crear un entorno Python aislado. Este entorno tiene sus propios directorios de instalación que no comparten bibliotecas con otros entornos virtualenv o las bibliotecas instaladas globalmente en el servidor

### Crear el ambiente virtual
```console
> python -m venv nombre_del_entorno_virtual
```
### Activar el ambiente virtual
1.- En Windows ejecutar el comando 
```console
> Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process -Force
```
2.- Ejecutar el comando 
```console
> .\nombre_del_entorno_virtual\Scripts\Activate.ps1
```