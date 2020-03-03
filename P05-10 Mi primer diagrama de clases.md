```mermaid

 classDiagram
      Videoclub <|-- Serie
      Videoclub <|-- Videojuego

      class Videoclub{
        -info_Serie
        -info_Videojuego
        +mostrar()
      }

      class Serie{
        -nombre
        -genero
        -creador
        +mostrar()
      }

      class Videojuego{
        -titulo
        -horas_estimadas
        -genero
        -compañia
        +mostrar()
      }

  end
```
