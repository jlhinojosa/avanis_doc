# Welcome to Avanis

Welcome to the Avanis project documentation. This guide provides information about the project structure, architecture, and how to contribute.

{/* - [Product](./product/intro.md) explains the functional aspects of the product including all the features and the business reasons */}

{/* - [User Guide](./userguide/intro.md) explains how the product is used by an end user. */}

# Platform Overview

## Introduction

The Avanis platform is designed as a modular, scalable, and maintainable system. It integrates a modern web application, backend services, and deployment infrastructure.

The primary goal of this application is to provide users with a clear, intuitive, and efficient way to maintain and control all financial aspects of their lives, providing streamlined workflows, simplifying interactions, and ensuring reliable access to relevant information, enabling users to perform actions with confidence, receive timely feedback, and trust that their data and interactions are handled securely and effectively.

---

## [Architecture Overview]
{/* (../architecture/introduction) */}

The platform follows a layered and modular architecture:

- **Frontend Layer (Web)**
  - Built with React
  - Responsible for user interaction, UI rendering, and client-side logic
  - Communicates with backend services via HTTP APIs

- **Backend Layer (Services)**
  - Implemented using Spring Boot
  - Structured as independent services (e.g., API Gateway, Authentication, Core Services)
  - Handles business logic, authentication, data processing, and integrations

- **Infrastructure & Deployment Layer**
  - Docker for containerization
  - Kubernetes for orchestration and environment management
  - Supports multiple environments (development, staging, production)

- **Monorepo Structure**
  - All components (frontend, backend, deployment, documentation) are managed in a single repository
  - Maven is used as the build and dependency management tool across all modules
  - Ensures consistency, traceability, and coordinated versioning

- **Documentation Layer**
  - Markdown-based documentation stored within the repository
  - Published via Docusaurus for both developer and user consumption
  - Covers architecture, modules, operations, and user guides

---

## Key Functionalities

- **Modular Application Development**
  - Clear separation between frontend and backend components
  - Independent services with well-defined responsibilities

- **Authentication and Authorization**
  - Dedicated authentication service
  - Token-based security (e.g., JWT)
  - Centralized access control

- **API Management**
  - API Gateway to route and manage incoming requests
  - Standardized API contracts between services

- **Scalable Deployment**
  - Containerized services using Docker
  - Kubernetes-based deployment with environment-specific configurations

- **Developer Experience**
  - Unified build system using Maven
  - Consistent project structure across all modules
  - Integrated documentation aligned with code

- **Documentation and Knowledge Sharing**
  - Centralized, version-controlled documentation
  - Separation between technical, product, and user documentation
  - Easy navigation and publishing through Docusaurus

- **Extensibility**
  - Designed to support additional services and modules
  - Flexible architecture to accommodate future growth and integrations

## User-Facing Functionalities

- **User Authentication**
  - Users can securely sign in and sign out of the application
  - Support for token-based sessions (e.g., JWT)
  - Secure access to protected areas of the platform

- **User Account Management**
  - View and manage personal profile information
  - Update credentials and account settings
  - Manage session and security preferences

- **Navigation and Interface Interaction**
  - Access different sections of the application through a structured UI
  - Responsive interface for consistent experience across devices
  - Real-time feedback on user actions

- **Data Access and Visualization**
  - View relevant data exposed by the platform
  - Interact with dashboards, lists, and detailed views
  - Filter, search, and navigate through information

- **Core Application Features**
  - Execute primary business workflows supported by the platform
  - Create, update, and manage domain-specific entities
  - Trigger actions and processes within the system

- **Notifications and Feedback**
  - Receive system messages, alerts, or confirmations
  - Get feedback on successful or failed operations
  - Stay informed about relevant updates or changes

- **Error Handling and Recovery**
  - Clear messaging when errors occur
  - Ability to retry actions or correct inputs
  - Guidance for resolving common issues

- **Session Management**
  - Maintain active sessions during usage
  - Automatic session expiration and renewal mechanisms
  - Secure handling of authentication tokens

- **Help and Support Access**
  - Access user documentation and guides
  - View FAQs and troubleshooting information
  - Navigate help resources directly from the application