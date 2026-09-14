---
name: react-patterns
description: Modern React patterns and principles. Hooks, composition, performance, TypeScript best practices.
allowed-tools: Read, Write, Edit, Glob, Grep
---

# React Patterns

> Principles for building production-ready React applications.

---

## 1. Component Design Principles

### Component Types

| Type | Use | State |
|------|-----|-------|
| **Server** | Data fetching, static | None |
| **Client** | Interactivity | useState, effects |
| **Presentational** | UI display | Props only |
| **Container** | Logic/state | Heavy state |

### Design Rules

- One responsibility per component
- Props down, events up
- Composition over inheritance
- Prefer small, focused components

---

## 2. Hook Patterns

### When to Extract Hooks

| Pattern | Extract When |
|---------|-------------|
| **useLocalStorage** | Same storage logic needed |
| **useDebounce** | Multiple debounced values |
| **useFetch** | Repeated fetch patterns |
| **useForm** | Complex form state |

### Hook Rules

- Hooks at top level only
- Same order every render
- Custom hooks start with "use"
- Clean up effects on unmount

---

## 3. State Management Selection

| Complexity | Solution |
|------------|----------|
| Simple | useState, useReducer |
| Shared local | Context |
| Server state | React Query, SWR |
| Complex global | Zustand, Redux Toolkit |

### State Placement

| Scope | Where |
|-------|-------|
| Single component | useState |
| Parent-child | Lift state up |
| Subtree | Context |
| App-wide | Global store |

---

## 4. React 19 Patterns

### New Hooks

| Hook | Purpose |
|------|---------|
| **useActionState** | Form submission state |
| **useOptimistic** | Optimistic UI updates |
| **use** | Read r

