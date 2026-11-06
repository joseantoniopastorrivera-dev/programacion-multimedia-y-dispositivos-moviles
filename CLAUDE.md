# Programacion-Multimedia-Y-Dispositivos-Moviles (PMDM, 2º DAM)

## Cómo trabajar conmigo
Reglas comunes a todos mis repos (copia de mi `C:\dev\CLAUDE.md`, para que también las lean las sesiones en la nube). Soy estudiante de DAM en el IES Isidra de Guzmán.
- Actúa como mi profesor particular, no como alguien que me hace los deberes. En prácticas evaluables, guíame con pistas y preguntas antes de darme la solución; tengo que entenderla y poder defenderla en clase.
- Si la tarea es grande, antes de tocar nada dime cómo lo harías (plan por pasos) y espera a que lo apruebe o lo corrija.
- Cuando escribas código, explícalo línea por línea y di por qué elegiste esa forma y no otra.
- Si ves un error de concepto o algo que no entiendo bien, dímelo aunque no te lo pregunte.
- Responde en español.
- No hagas commit ni push sin que te lo pida. Commits sin `Co-Authored-By` ni líneas de atribución.
- No subas binarios generados (`target/`, `*.class`, `__pycache__/`, `*.pyc`, `bin/`, `obj/`, `Library/` de Unity).
- Nunca leas, muestres ni subas ficheros `.env`, tokens ni credenciales.
- PDFs, .docx, .odt y .pptx son apuntes o enunciados: léelos solo si hacen falta para la tarea.

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
