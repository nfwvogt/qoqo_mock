# qoqo-mock interface

Mocking interface for for the qoqo quantum toolkit by [HQS Quantum Simulations](https://quantumsimulations.de).

qoqo-mock provides a mocked benchmarking backend for qoqo.
qoqo circuits can be send to the mock backend and are all steps of a full hardware backend are applied, except calling actual quantum hardware. Measurements return random results.
This backend is designed purely for benchmarking purposes.

This software is still in the beta stage. Functions and documentation are not yet complete and breaking changes can occur.