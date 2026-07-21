# 🤖 Cypress Automation Framework

> A scalable end-to-end automation framework built with Cypress to improve test reliability, reduce execution time, and support continuous delivery.

---

# Overview

Over the years, I've used Cypress to automate functional, regression, API, and end-to-end testing across enterprise, fintech, healthcare, and government applications.

Rather than viewing automation as simply writing test scripts, I treat it as an engineering discipline focused on building scalable frameworks that improve software quality, accelerate releases, and reduce long-term maintenance costs.

My approach emphasizes clean architecture, reusable components, reliable execution, and engineering practices that reduce maintenance costs over time.

---

# Framework Highlights

## Architecture

The framework follows modern automation engineering principles including:

- Page Object Model (POM)
- Custom Cypress Commands
- Reusable Utilities
- Fixtures
- Environment Configuration
- API Testing
- Session Management
- Network Interception
- Test Data Management
- Modular Folder Structure

---

## Technologies Used

### Core

- Cypress
- JavaScript
- TypeScript
- Node.js

### Testing & Authentication

- Mailinator
- Auth0
- cypress-plugin-api

### Reporting

- Mochawesome

### DevOps

- GitHub Actions

---

## Framework Architecture

The framework is organised to encourage scalability and maintainability.

Examples include:

- Page Objects
- Custom Commands
- Fixtures
- API Helpers
- Utility Functions
- Configuration Files
- Environment Variables
- Reporting Modules

---

## Framework Structure

![](../../assets/images/engineering-showcase/cypress/cypress-framework-structure.png){ loading=lazy }

---

# Real Engineering Solutions

The framework contains several reusable engineering solutions that solve real-world testing challenges.

---

## 📧 Automated Email OTP Login

Modern applications frequently require one-time passwords (OTP) during authentication.

To eliminate manual intervention, I designed an automated login flow that integrates:

- Cypress
- Auth0
- Mailinator

The automated authentication workflow:

1. Enters the test email
2. Retrieves the OTP from Mailinator
3. Extracts the verification code
4. Completes authentication
5. Stores the authenticated session
6. Continues test execution without further user interaction

This approach enables reliable testing of secure authentication workflows while significantly reducing execution time.

### Demo
![type:video](../../assets/videos/cypress/email-otp-login.mp4)

### Implementation

![](../../assets/images/engineering-showcase/cypress/email-otp-code.png){ loading=lazy }

---

[:fontawesome-brands-linkedin: Read the full engineering article](https://www.linkedin.com/posts/michaeljndueso_cypress-auth0-emailotp-ugcPost-7441213407606972416-2x8M/?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAC0KOAMB4JNjVL1I3Cfum1yHcU8dfCVfy80){ .md-button .md-button--primary }

---

## 🔑 Session Management with `cy.session()`

Repeated login operations slow down automated test suites and increase execution costs.

To improve efficiency, I implemented reusable authenticated sessions using `cy.session()`.

Benefits include:

- Login once
- Reuse authenticated state
- Faster regression testing
- Reduced OTP requests
- Improved test stability
- Lower execution time

This significantly reduced overall suite execution time while improving reliability for regression and CI/CD pipelines.

### Implementation

![](../../assets/images/engineering-showcase/cypress/cy-session.png){ loading=lazy }

---

[:fontawesome-brands-linkedin: Read the full engineering article](https://www.linkedin.com/posts/michaeljndueso_cypress-testautomation-endtoendtesting-activity-7441210338336882688-lIj5?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAC0KOAMB4JNjVL1I3Cfum1yHcU8dfCVfy80)
{ .md-button }

---

## 🔌 API Testing with `cy.api()`

While Postman is well suited for exploratory API testing, I wanted automated API validation to live alongside UI automation within a single engineering workflow.

Using `cypress-plugin-api`, I integrated API testing directly into the Cypress framework.

This provides:

- Visual request inspection
- Response validation
- Status code verification
- Header inspection
- Payload assertions
- Integrated reporting

Running API tests alongside UI tests simplifies maintenance and keeps all automation within a single codebase.

### Example

![](../../assets/images/engineering-showcase/cypress/cy-api.png){ loading=lazy }

---

[:fontawesome-brands-linkedin: Read the full engineering article](https://www.linkedin.com/posts/michaeljndueso_cypress-apitesting-automation-activity-7458955031283826688-FgKi?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAC0KOAMB4JNjVL1I3Cfum1yHcU8dfCVfy80){ .md-button }

---

# Additional Framework Capabilities

The framework also supports:

- Authentication workflows
- Session management
- API automation
- Cross-browser testing
- Network interception
- File uploads
- Database validation
- Fixtures
- Environment management
- Parallel execution
- Custom reporting
- CI/CD integration

---

# Engineering Impact

This framework was designed to improve both engineering efficiency and software quality by:

- Reducing repetitive manual regression testing
- Increasing test reliability and consistency
- Supporting continuous integration pipelines
- Simplifying framework maintenance through reusable components
- Improving release confidence with automated validation
- Providing faster feedback to development teams

---

# Engineering Philosophy

Automation is not simply about executing scripts.

A well-designed framework should:

- Be easy to extend
- Reduce duplication
- Encourage reuse
- Improve reliability
- Support continuous delivery
- Reduce maintenance effort

The goal is to build automation that scales alongside the application it supports.

---

# Skills Demonstrated

### Automation Engineering

- Cypress
- JavaScript
- TypeScript
- Test Architecture
- Page Object Model
- Custom Commands

### Quality Engineering

- API Testing
- Authentication Testing
- Session Management
- Mailinator Integration
- Auth0

### DevOps

- CI/CD
- GitHub Actions

---

> **"Good automation isn't measured by the number of tests it contains, but by how easily those tests evolve with the product."**