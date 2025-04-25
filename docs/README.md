# Cleartrip B2B V4 APIs Documentation

This repository contains the OpenAPI/Swagger documentation for Cleartrip's B2B V4 APIs.

## Repository Structure

```
docs/
├── openapi.yaml                 # Main OpenAPI file
├── paths/                       # API endpoints
│   ├── search/                  # Search related endpoints
│   ├── booking/                 # Booking related endpoints
│   ├── content/                 # Content related endpoints
│   └── trip/                    # Trip management endpoints
├── components/                  # Reusable components
│   ├── schemas/                 # Data models
│   ├── security/               # Security definitions
│   └── examples/               # Request/response examples
└── README.md                   # This file
```

## API Categories

1. **Search APIs**
   - Search by Hotel ID
   - Search by Location

2. **Booking APIs**
   - Provisional Booking
   - Final Booking

3. **Content APIs**
   - Hotel Profiles
   - Locations

4. **Trip Management APIs**
   - Trip Details
   - Cancellation
   - Refund Information

## Security

All APIs require the following headers:
- `x-ct-api-key`: API key for authentication
- `x-ct-request-id`: Unique request ID for tracking
- `x-lineage-id`: Unique lineage ID for tracking

## Usage

1. Clone this repository
2. Use any OpenAPI/Swagger compatible tool to view and test the APIs
3. For local development, you can use tools like:
   - [Swagger UI](https://swagger.io/tools/swagger-ui/)
   - [Redoc](https://github.com/Redocly/redoc)
   - [Postman](https://www.postman.com/)

## Contributing

1. Follow the directory structure for organizing new APIs
2. Add proper documentation and examples
3. Update the README when adding new features
4. Use consistent naming conventions 