# Go Design Patterns

A collection of Go (Golang) design patterns with simple explanations and practical code examples. I'm building this repository as I learn and explore software design in Go, focusing on clean, idiomatic implementations and real-world use cases.

## Why this repository?

When I started learning design patterns, I found that many examples were either too abstract or not written in idiomatic Go. This repository is my way of documenting what I learn while keeping the examples practical and easy to understand.

Whether you're new to design patterns or just looking for Go implementations, I hope you find something useful here.

## Repository Structure

```
.
├── creational/
│   ├── singleton/
│   ├── factory/
│   ├── builder/
│   └── ...
├── structural/
│   ├── adapter/
│   ├── decorator/
│   ├── facade/
│   └── ...
├── behavioral/
│   ├── observer/
│   ├── strategy/
│   ├── command/
│   └── ...
└── README.md
```

Each pattern contains:

* A short explanation
* The problem it solves
* When to use it
* A Go implementation
* A runnable example
* Notes and best practices

## Patterns

### Creational

* [ ] Singleton
* [ ] Factory Method
* [ ] Abstract Factory
* [ ] Builder
* [ ] Prototype

### Structural

* [ ] Adapter
* [ ] Bridge
* [ ] Composite
* [ ] Decorator
* [ ] Facade
* [ ] Flyweight
* [ ] Proxy

### Behavioral

* [ ] Chain of Responsibility
* [ ] Command
* [ ] Iterator
* [ ] Mediator
* [ ] Memento
* [ ] Observer
* [ ] State
* [ ] Strategy
* [ ] Template Method
* [ ] Visitor

## Running the examples

Clone the repository:

```bash
git clone https://github.com/<your-username>/go-design-patterns.git
cd go-design-patterns
```

Run an example:

```bash
go run ./creational/singleton
```

## Who is this for?

* Go developers learning design patterns
* Students preparing for interviews
* Anyone looking for practical Go examples
* Developers who prefer learning by reading code

## Contributing

If you find a mistake, have a better implementation, or want to add a missing pattern, feel free to open an issue or submit a pull request. Contributions are always welcome.

## License

This project is licensed under the MIT License.
