# API Design Workflow

## RESTful API Design Standards
- Use nouns for resources (e.g., `/users`, `/products`).
- Use HTTP methods consistently:
  - `GET`: Retrieve a resource.
  - `POST`: Create a new resource.
  - `PUT`: Update an existing resource.
  - `DELETE`: Remove a resource.

## OpenAPI/Swagger Documentation Generation
- Utilize OpenAPI Specification to document the API.
- Keep documentation in sync with code changes.
- Generate interactive API docs using Swagger UI.

## Data Contract Definitions
- Clearly define data models for requests and responses.
- Use JSON for data interchange format.
- Validate input against defined schemas.

## Versioning Strategy
- Include versioning in the URL (e.g., `/v1/users`).
- Maintain backward compatibility when introducing changes.
- Deprecate older versions with clear communication.

## Error Handling Conventions
- Use standardized error response format:
  - `error`: A short description of the error.
  - `code`: Error code for programmatic use.
  - `message`: User-friendly error message.
- Provide meaningful HTTP status codes (e.g., 200, 400, 404, 500).