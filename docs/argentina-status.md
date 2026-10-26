# Estado del Fútbol Argentino - World Football Manager

## Completado

### Clubes
- **30/30** clubes de la Liga Profesional 2026 cargados con datos de estadio, capacidad, reputación y presupuesto.

### Plantillas Primer Equipo
- **Boca Juniors**: Plantilla completa y realista (23 jugadores)
- **River Plate**: Plantilla completa y realista (20 jugadores) incluyendo cedidos

### Estructura de Juveniles
- Definidas las categorías oficiales del fútbol argentino
- Enfoque prioritario en **Reserva** y **Cuarta (U20)** como las dos primeras categorías de cantera

## En progreso / Pendiente

- Completar plantillas de: Racing, Independiente, Vélez, Estudiantes, San Lorenzo, Rosario Central, Lanús, Talleres, Newell's, Argentinos, etc.
- Crear archivos de Reserva y U20 para los clubes grandes
- Agregar más jugadores de nivel medio y de cantera
- Sistema de proyección de juveniles al primer equipo

## Convención

- `status: "loan"` + `loanFrom` → Jugador cedido que milita en el club
- `status: "loaned_out"` + `loanTo` → Jugador del club que está cedido en otro lado
- Overall y Potential calibrados de forma coherente con el nivel real del jugador
