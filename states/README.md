# States

## React state

### Rappels
- Pourquoi on utilise un hook au lieu de déclarer un state avec const ?
- Pourquoi on utilise le setter de state plutôt que de muter l'objet ?

## Redux state

### Principes

https://redux.js.org/understanding/thinking-in-redux/three-principles

- Une seule source de vérité
- Le state est immutable (lecture seule)
- Un changement d'état se fait par une fonction pure: 1 state = 1 state précédent + 1 action
- CQRS: Command Query Responsability Segregation

## XState

https://github.com/davidkpiano/xstate