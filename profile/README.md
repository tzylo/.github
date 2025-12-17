# Tzylo Auth CE

**Tzylo Auth CE** is a lightweight, developer-first authentication service designed for modern applications.

It provides secure, modular authentication primitives that can be **self-hosted** or used as a foundation for larger identity systems.

---

## What is Auth CE?

Auth CE (Community Edition) focuses on **core authentication needs** without unnecessary abstraction or lock-in.

It is built to be:

* Simple to integrate
* Easy to reason about
* Flexible across frameworks and architectures

---

## Core Features

* 🔐 JWT-based authentication
* 🔁 Access & refresh token lifecycle
* 👤 User identity handling
* 🧩 Role-based access control
* ⚡ SDKs and middleware for popular frameworks
* 🐳 Docker-friendly, cloud-native design

---

## Design Goals

Auth CE is designed with the following principles:

* **Framework-agnostic core**
  Business logic is independent of any web framework.

* **Adapter-based integration**
  Thin adapters for Express, Fastify, and SDK consumers.

* **Stateless by default**
  Works cleanly in distributed systems and microservices.

* **Self-host friendly**
  No hard dependency on managed services.

* **Predictable behavior**
  Minimal magic, explicit configuration.

---

## Architecture Overview

At a high level, Auth CE consists of:

* Core authentication logic (token verification, identity resolution)
* Middleware / adapters for server frameworks
* SDK-friendly interfaces
* Clear type contracts for consumers

Each layer is intentionally kept small and composable.

---

## Use Cases

Auth CE is suitable for:

* Backend APIs
* Microservices
* Internal tools
* Early-stage products
* Systems that require full control over auth behavior

---

## Project Status

Auth CE is **actively developed**.

* APIs may evolve
* Backward compatibility is considered, but not frozen
* Focus is on correctness, security, and maintainability

---

## Open Source

Auth CE is open for:

* Issues
* Discussions
* Improvements

Feedback that improves clarity, safety, or developer experience is welcome.

---

### Note

Auth CE is intentionally scoped.
It focuses only on **authentication fundamentals**, not user management platforms or opinionated workflows.

