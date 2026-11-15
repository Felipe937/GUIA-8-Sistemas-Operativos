# Instalación de Windows Server 2019 EVAL - Guía 8

## Propósito

Este documento describe los pasos y evidencias para la instalación de Windows Server 2019 Evaluation version como parte de la Guía 8 de Sistemas Operativos.

## Evidencias disponibles

Los siguientes archivos e imágenes fueron identificados:
- `17763.3650.221105-1748.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_es-es.iso` - Archivo ISO de Windows Server EVAL (5.6 GB)
- `verificacion_iso.ps1` - Script de verificación de la ISO
- `verificacion_iso.txt` - Reporte de verificación (actualmente vacío)
- `diagnostico.ps1` - Diagnóstico general del sistema
- `diagnostico.txt` - Reporte de diagnóstico en texto

## Estado actual

### ISO de Windows Server
- **Archivo**: `17763.3650.221105-1748.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_es-es.iso`
- **Tamaño**: 5.6 GB
- **Fecha**: 14/11/2026
- **Sistema**: Windows Server 2019 Evaluation (versión en español)
- **Ubicación**: `evidencias/instalaciones/`

### Diagnóstico del sistema
Los scripts de diagnóstico identificaron componentes relacionados con:
- Configuración de hardware
- Validación de componentes del sistema
- Preparación para instalación

## Fases del proceso
1. **Preparación**: Obtención y verificación del ISO de evaluación
2. **Configuración**: Preparación del entorno VirtualBox o físico
3. **Instalación**: Proceso de instalación de Windows Server 2019
4. **Post-instalación**: Configuración inicial y validación

## Evidencias faltantes
- No hay capturas de pantalla del proceso de instalación
- No hay logs detallados del asististant de instalación
- El archivo `verificacion_iso.txt` está vacío (0 bytes) - pending completar
- Falta documentación de la Fase 1 y Fase 2 específicas

## Próximas tareas
- Ejecutar `verificacion_iso.ps1` y documentar resultados
- Capturar screenshots del proceso de instalación
- Completar el archivo `verificacion_iso.txt` con hallazgos
- Documentar pasos específicos de la Fase 1 y Fase 2