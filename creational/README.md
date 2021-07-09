[GURU](https://refactoring.guru/design-patterns/creational-patterns)

## Builder
- Separate component for when object construction gets too complicated
- Can create mutually cooperating sub-builders
- Often has fluent interfaces

## Factories
- Factory functions (constructors) are common
- Factory can be simple function or a dedicated struct

## Prototype
- Creation of object from an existing object
- Requires either explicit deep copy or copy through serialization

## Singleton
- When you need to ensure just a single instance exists
- Can be made thread-safe and lazy
- Consider extracting interface or using dependency injection