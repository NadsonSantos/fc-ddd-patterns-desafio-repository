# DDD Patterns - Order Repository and Domain Events Implementation

This project implements Domain Driven Design (DDD) patterns for an e-commerce application, focusing on the Order Repository in the infrastructure layer and Domain Events for the Customer aggregate.

## Features

- **Order Repository**: Complete implementation with create, update, find, and findAll operations.
- **Domain Events**: Event-driven architecture for Customer creation and address changes.
  - `CustomerCreatedEvent`: Dispatched when a new customer is created, triggering console log handlers.
  - `CustomerAddressChangedEvent`: Dispatched when customer address is changed, logging the update.

## Installation

To install the dependencies, run:

```bash
npm install
```

## Running Tests

To run the tests, use the following command:

```bash
npm test
```

This will compile the TypeScript code and run all Jest tests. All tests should pass, including the OrderRepository tests and Customer domain event tests.

## Project Structure

- `src/domain/`: Domain layer with entities, services, interfaces, and events
- `src/infrastructure/`: Infrastructure layer with repository implementations
- Tests are located alongside the implementation files with `.spec.ts` extension