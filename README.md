# VIP Playtime Plugin

Este es un plugin para [Oxide](https://umod.org/) que otorga el grupo VIP a los jugadores después de cierto tiempo de juego. Está diseñado para usarse en servidores de juegos que utilizan el sistema de permisos de Oxide.

## Características

- Asigna automáticamente el grupo VIP a los jugadores después de alcanzar un tiempo de juego determinado.
- Comando para que los jugadores consulten su tiempo de juego y el tiempo restante para alcanzar el estatus VIP.
- Guarda automáticamente los datos de juego a intervalos regulares.

## Instalación

1. **Descargar el plugin**: Descarga el archivo `VIPPlaytime.cs` y colócalo en la carpeta `plugins` de tu servidor Oxide.

2. **Configuración (opcional)**: Puedes ajustar la configuración editando el archivo `VIPPlaytime.json` que se genera automáticamente en la carpeta `config` después de ejecutar el plugin por primera vez.

## Comandos

- `/viptime`: Muestra el tiempo de juego acumulado y el tiempo restante para alcanzar el estatus VIP.

## Configuración

El archivo de configuración `VIPPlaytime.json` se encuentra en la carpeta `config` y permite ajustar los siguientes parámetros:

```json
{
  "VIPHours": 20,
  "VIPGroup": "vip",
  "SaveInterval": 900,
  "ViptimeCommand": "viptime"
}

