uick
them in the source code. This improves security and makes the application easier
to manage across development, staging, and production environments.

Overall, this concept helped me understand how automation and containerization
simplify cloud deployments and make applications more scalable and maintainable.

---

### Case Study: The Never-Ending Deployment Loop

The deployment issues in this scenario are mainly caused by improper environment
variable handling, port conflicts, and poor container lifecycle management.
Errors like “Environment variable not found” occur when required configuration
values are not correctly defined in the CI/CD pipeline or cloud environment.
Similarly, “Port already in use” errors happen when old containers are not stopped
before deploying new ones.

These issues can be resolved by properly containerizing the application using Docker,
defining all required environment variables securely in the CI/CD pipeline,
and ensuring that old containers are stopped or replaced before new deployments.

A well-configured CI/CD workflow ensures a clean handoff between each stage —
from code commit, to container build, to deployment — resulting in stable,
versioned, and secure deployments on AWS or Azure.