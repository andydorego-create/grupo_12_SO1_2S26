# Trabajo práctico integrador — Sistemas Operativos 1 (2026)

**Modalidad:** Individual (a confirmar con la cátedra si se necesita identificación de grupo)  
**Estudiante:** Andres Do Rego Barros  
**Sistema anfitrión:** Rocky Linux Minimal (versión pendiente de verificar)  
**Libro LFS:** **13.1-systemd**, edición estable publicada el 01/09/2026.  
**Manual oficial:** https://linuxfromscratch.org/lfs/view/13.1-systemd/

## Objetivo
Preparar una máquina virtual Rocky Linux para construir Linux From Scratch (LFS), configurar un segundo disco para montar `/mnt/lfs`, comprobar requisitos del anfitrión y registrar evidencias, decisiones y cambios en Git.

## Estado actual
- [ ] Validar recursos de la VM (CPU, RAM, disco y red)
- [ ] Actualizar Rocky e instalar herramientas
- [ ] Configurar y montar el disco dedicado de LFS
- [ ] Ejecutar `version-check.sh` sin errores
- [ ] Guardar las evidencias del anfitrión
- [ ] Crear snapshot inicial
- [ ] Completar diario y registro de IA con actividades realmente realizadas

## Evidencias solicitadas
Subir a `evidencias/parte1/` estos archivos **generados en la VM**, no simulados:
- `anfitrion.txt`
- `disco-lfs.txt`
- `version-check.txt`
- `snapshot-00.png`

## Fuentes
- Manual oficial: https://linuxfromscratch.org/lfs/view/13.1-systemd/
- Requisitos del anfitrión: https://linuxfromscratch.org/lfs/view/13.1-systemd/chapter02/hostreqs.html
- Revisar las erratas y avisos de seguridad asociados antes de la compilación.

> Este repositorio se está completando por etapas. Las casillas sin marcar y archivos ausentes indican trabajo pendiente.
