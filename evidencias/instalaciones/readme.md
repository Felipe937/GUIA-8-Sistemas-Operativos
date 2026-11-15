# Evidencias de Instalación - Guía 8

## Descripción general

Este directorio contiene las evidencias físicas y configuraciones relacionadas con la instalación del sistema operativo y entornos de prueba.

## Contenido actual

### ISO de Windows Server 2019 EVAL
- **Nombre**: `17763.3650.221105-1748.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_es-es.iso`
- **Ruta**: `evidencias/instalaciones/17763.3650.221105-1748.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_es-es.iso`
- **Tamaño**: 5.6 GB
- **Sistema**: Windows Server 2019 Evaluation
- **Idioma**: Español (es-es)
- **Fecha de creación**: 14/11/2026
- **Propósito**: Instalación para la Guía 8 de Sistemas Operativos
- **Ubicación**: Disponible para uso en VirtualBox o instalación física

### Configuración de VirtualBox (referencia)
Los scripts y pruebas en el repositorio están diseñados para trabajar con este ISO en un entorno VirtualBox.

## Instrucciones de uso
1. Montar el ISO en VirtualBox
2. Iniciar la máquina virtual
3. Seguir el asistant de instalación de Windows Server 2019
4. Ejecutar scripts de diagnóstico verificacion_iso.ps1 para validar la instalación

## Evidencias sugeridas (pending)
- Capturas de pantalla del asistant de instalación
- Logs detallados del proceso de instalación
- Resultados de `verificacion_iso.ps1` después de la instalación
- Configuración de adaptadores de red en VirtualBox
- Configuración de memoria y CPU asignadas

## Próximos pasos
- Documentar parámetros de configuración utilizados
- Ejecutar y documentar `verificacion_iso.ps1`
- Crear reporte de éxito/fallos de instalación