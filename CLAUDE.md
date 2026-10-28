# Programacion-Multimedia-Y-Dispositivos-Moviles (PMDM, 2º DAM)

Transición de Java a C# y desarrollo con Unity.

## Estructura (real; el README menciona carpetas que aún no existen)
- `Transicion-Java-C#/01-Conceptos-Basicos-Y-Condicionales/`, `02-Bucles/`, `03-Juegos/03-Juegos/` — proyectos de consola .NET (`.csproj`, `net10.0`).
- `Proyecto01/` — proyecto Unity 6 (`6000.0.83f1`), URP e Input System. Escenas en `Assets/Scenes/`.

## Compilar y ejecutar
- Consola: `dotnet run --project "Transicion-Java-C#/02-Bucles"` (cambia la carpeta).
- Unity: abrir `Proyecto01` desde Unity Hub con el editor 6000.0.83f1. Scripts en `Assets/`.

## Notas
- Convenciones C#: PascalCase en métodos y propiedades, propiedades automáticas en lugar de getters/setters de Java.
- En Unity no edites `ProjectSettings/` ni archivos `.meta` a mano; no subas `Library/`, `Temp/`, `Logs/`, `obj/`, `bin/`.
