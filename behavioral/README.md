[GURU](https://refactoring.guru/design-patterns/behavioral-patterns)

## Chain of Responsibility
- Allow components to process information/events in a chain
- Each element in the chain refers to next element; or
- Make a list and go through it

## Command
- Encapsulate a request into a separate object
- Good for audit, replay, undo/redo
- Part of CQS/CQRS

## Interpreter
- Transform textual input into structurals (e.g. ASTs)
- Used by interpreters, compilers, static analysis tool, etc.
- Compiler theory is a separate branch of Computer science

## Mediator 
- Provides mediation service between several objects
- E.g., message passing, chat room

## Memento
- Yields token representing system states
- Tokens do not allow direct manipulation, but can be used in appropriate APIs

# Observer
- Allows notifications of changes/happenings in a component

# State
- We model systems by having on of a possible states and transitions between these states
- Such a system is called a state machine
- Special frameworks exists to orchestrate state machines 

# Strategy & Template Method
- Both define a skeleton algorithm with details filled in by implementer
- Strategy uses composition; Template Method doesn't 

## Visitor
- Allows non-intrusive addition of functionality to hierarchies
