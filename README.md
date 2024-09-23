# CURSO: APRENDE BLAZOR

# LECCIÓN 3: Crear una aplicación Blazor con VSCode y .NET 8 (.NET CLI)

**NOTA**: El video youtube de esta Lección3 está disponible en el siguiente vínculo: 

1. Instalar VSCode
2. 
   (https://code.visualstudio.com/)

3. Instalar el Framework ".NET 8 SDK" para Windows X64
4. 
   (https://dotnet.microsoft.com/es-es/download/dotnet/8.0)

5. Abrir una ventana de comandos "Command Prompt"

6. Comprobar la version de "dotnet CLI". Ejecutar el comando:

```
dotnet --list-sdks
```

5. Listamos las plantillas de proyectos de Blazor. Ejecutar el comando:

```
dotnet new list
```

6. Creamos la carpeta en el disco duro donde ubicar nuestra aplicación.

Ejecutar los comandos:

```
md Leccion2
```
   
y

```
cd Leccion2
```
   
7. Creamos la aplicación Blazor ejecutando el siguiente comando:

```
dotnet new Blazor
```

(OPCIONAL) En lugar de ejecutar los puntos 6. y 7. Otra opción es crear tanto el directorio como la aplicación Blazor con la línea de comandos: 

```
dotnet new blazor -n "Leccion2"
```

8. Abrir el proyecto en el VSCode. Ejecutar el comando:

```
code .
```

9. Ejecutar la aplicación. Ejecutar el comando:

```
dotnet run
```

10. Parar la aplicación. Ejecutar la combinación de teclas: Ctrl+C

