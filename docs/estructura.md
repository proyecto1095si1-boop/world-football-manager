# Estructura de datos - World Football Manager

## Objetivo

Crear una base de datos sólida y expandible inspirada en Transfermarkt + atributos de Football Manager.

## Ligas prioritarias (Fase 1)

1. Premier League (Inglaterra)
2. LaLiga (España)
3. Serie A (Italia)
4. Bundesliga (Alemania)
5. Ligue 1 (Francia)
6. Liga Profesional (Argentina)
7. Brasileirão (Brasil)

## Próximos pasos

- [ ] Completar plantillas de Boca y River con más jugadores
- [ ] Agregar Racing, Independiente, Vélez, Estudiantes, Central
- [ ] Empezar con clubs grandes de Europa (Real Madrid, Barcelona, Manchester City, etc.)
- [ ] Crear sistema de IDs consistente
- [ ] Definir atributos detallados (pace, shooting, etc.)
- [ ] Motor básico de simulación

## Convención de IDs

- Club: `nombre-corto` en kebab-case (ej: `boca-juniors`, `manchester-city`)
- Jugador: `club-apellido` o `club-nombre-apellido` si hay conflicto
