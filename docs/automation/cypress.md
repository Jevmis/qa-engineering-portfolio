# Cypress

:material-robot:

Cypress is my primary automation framework.

!!! tip

    Use data-test attributes instead of CSS selectors.

---

## Install

```bash
npm install cypress
```

---

## Visit

```ts
cy.visit("/")
```

---

## Assertions

```ts
cy.get("button").should("be.visible")
```