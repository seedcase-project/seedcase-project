---
title: "Risks and technical debt"
---

## Technical debt

### Django Framework

The Django Framework is a popular web framework for building web
applications in Python. Although the framework provides many benefits,
there are several areas where technical debt has accumulated.

-   Outdated dependencies: The application is currently using outdated
    versions of some Django dependencies, which can lead to security
    vulnerabilities and compatibility issues.
-   Unoptimized database queries: The application is making inefficient
    database queries, which can lead to slower performance and increased
    server load.
-   Poorly organized code: Some parts of the codebase are poorly
    organized, making it difficult to maintain and update the
    application.

To address these issues, the following strategies are recommended:

todo: Not clear, are these things we need to do? How?

-   Update dependencies: The team should update the dependencies to the
    latest versions, making sure to test for compatibility issues.
-   Optimize database queries: The team should review the application's
    database queries and identify areas for optimization, such as
    reducing the number of queries or improving indexing.

### Django REST API Framework

The Django REST API Framework is a powerful tool for building RESTful
APIs in Django. However, there are several areas where technical debt
has accumulated:

-   Some poorly documented endpoints: Some endpoints are poorly
    documented, making it difficult for developers to use them
    effectively.
-   Inconsistent authentication: The application uses inconsistent
    authentication mechanisms, making it difficult to ensure the
    security of the API.

To address these issues, the following strategies are recommended:

-   Improve endpoint documentation: The team should review the API
    endpoints and update the documentation to make it more complete and
    accurate.
-   Standardize authentication: The team should standardize the
    authentication mechanisms used by the API, making sure to use best
    practices for security.

### PostgreSQL Database

The PostgreSQL Database is a powerful open-source database that provides
many benefits. There are some areas where technical debt has
accumulated, primarily regarding situations where a large number of
transactions are happening at the same time. These should not impact the
Seedcase Product. Technical debt is more likely to arise over time, as
the database is being built.

To address these issues, the following strategies are recommended:

-   A standard for naming components in the database should be
    identified and followed.
-   All code should be documented.
-   Commenting should be employed directly in the code where a script
    depends on another.
-   It should be considered whether or not it would be useful to force
    key relationships between entities to minimise the risk of orphan
    data.

## Technical Risks

### Docker Framework

The Docker framework presents several technical risks, including:

-   Security vulnerabilities: Docker images can contain security
    vulnerabilities, such as outdated dependencies or misconfigured
    settings, that can be exploited by attackers.
-   Misconfigured containers: Misconfigured containers can expose
    sensitive data or provide unauthorized access to the host system.

To mitigate these risks, the following strategies are recommended:

-   Use security hardened Docker images: The team should use Docker
    images from trusted sources, such as official repositories or
    reputable vendors, remove all unused services and close all unused
    ports.
-   Implement container security best practices: The team should
    implement container security best practices, such as restricting
    network access and using minimal and hardened container images.
-   Simplify the infrastructure: The team should simplify the
    infrastructure by reducing the number of containers and optimizing
    their configurations.

## Django Framework

The Django Framework presents several technical risks, including:

-   SQL injection attacks: The application may be vulnerable to SQL
    injection attacks if user input is not properly validated.
-   Insufficient logging and monitoring: The application may not be
    properly logging and monitoring user activities, making it difficult
    to detect and respond to security incidents.

To mitigate these risks, the following strategies are recommended:

-   Implement input validation and sanitization: The team should
    implement input validation and sanitization to prevent XSS and SQL
    injection attacks.
-   Implement logging and monitoring: The team should implement logging
    and monitoring mechanisms to track user activities and detect
    security incidents.
-   Regularly perform security audits: The team should regularly perform
    security audits to identify and address potential vulnerabilities.

### Django REST API Framework

The Django REST API Framework presents several technical risks,
including:

-   Insecure authentication and authorization: The application may use
    insecure authentication and authorization mechanisms, allowing
    unauthorized access to sensitive data.
-   Insufficient access controls: The application may not have
    sufficient access controls, allowing unauthorized users to access
    sensitive data.

To mitigate these risks, the following strategies are recommended:

-   Use secure authentication and authorization mechanisms: The team
    should use secure authentication and authorization mechanisms, such
    as OAuth 2.0 or JSON Web Tokens (JWT).
-   Implement access controls: The team should implement access controls
    to restrict access to sensitive data and functions.

### Front End

Front End presents several technical risks, including:

-   Cross-site scripting (XSS) attacks: The application may be
    vulnerable to XSS attacks if user input is not properly sanitized.
-   Code injection attacks: The application may be vulnerable to code
    injection attacks if user input is not properly validated.

To mitigate these risks, the following strategies are recommended:

-   Implement input validation and sanitization: The team should
    implement input validation and sanitization to prevent XSS and code
    injection attacks.
-   Use secure communication protocols: The team should use secure
    communication protocols, such as HTTPS, to prevent MITM attacks.
-   Regularly perform security audits: The team should regularly perform
    security audits to identify and address potential vulnerabilities.
