# Programacion-Multimedia-Y-Dispositivos-Moviles (PMDM, 2º DAM)

Transición de Java a C# y desarrollo con Unity.

## Estructura
- `transicion-java-csharp/01-conceptos-basicos-y-condicionales/`, `02-bucles/`, `03-juegos/03-juegos/` — proyectos de consola .NET (`.csproj`, `net10.0`).
- `proyecto01/` — proyecto Unity 6 (`6000.0.83f1`), URP e Input System. Escenas en `Assets/Scenes/`.

## Compilar y ejecutar
- Consola: `dotnet run --project "transicion-java-csharp/02-bucles"` (cambia la carpeta).
- Unity: abrir `proyecto01` desde Unity Hub con el editor 6000.0.83f1. Scripts en `Assets/`.

## Notas
- Convenciones C#: PascalCase en métodos y propiedades, propiedades automáticas en lugar de getters/setters de Java.
- En Unity no edites `ProjectSettings/` ni archivos `.meta` a mano; no subas `Library/`, `Temp/`, `Logs/`, `obj/`, `bin/`.
