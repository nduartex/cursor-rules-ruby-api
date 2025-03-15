# Cursor Rules for Ruby/Rails API Development

This repository contains a comprehensive collection of Cursor.sh rules and best practices for Ruby and Ruby on Rails API development. These rules are designed to enhance your development experience by providing consistent guidelines, automated suggestions, and practical examples within the Cursor editor.

## Structure

The rules are organized into several categories:

### Core Development
- `api.mdc`: Detailed API design guidelines, response formats, authentication, and performance optimizations
- `clean_code.mdc`: Comprehensive best practices for writing clean, maintainable code with practical examples
- `controllers.mdc`: Controller-specific patterns and best practices
- `database.mdc`: Database design, optimization guidelines, and query best practices
- `design_patterns.mdc`: Extensive guide on common design patterns with real-world implementation examples
- `general.mdc`: General development practices and conventions
- `ruby.mdc`: Ruby language specific guidelines and best practices

### Security & Performance
- `security.mdc`: Comprehensive security best practices, including authentication, data protection, and API security
- `perfomance.mdc`: Performance optimization guidelines and monitoring strategies
- `monitoring.mdc`: Application and infrastructure monitoring, logging, and metrics collection

### API Development
- `serializers.mdc`: Serialization patterns and best practices for API responses
- `swagger.mdc`: API documentation guidelines using Swagger/OpenAPI

### Development Workflow
- `git.mdc`: Git workflow and commit message conventions
- `deployment.mdc`: Deployment strategies, CI/CD configuration, and infrastructure management
- `testing.mdc`: Testing strategies, patterns, and best practices

## Features

- **Comprehensive Examples**: Each rule category includes practical code examples
- **Modern Practices**: Up-to-date with current Ruby/Rails best practices
- **Security Focus**: Strong emphasis on security best practices
- **Performance Optimization**: Detailed guidelines for optimizing application performance
- **Monitoring & Observability**: Complete monitoring and logging setup examples
- **Infrastructure Management**: Deployment and infrastructure configuration templates

## Usage

1. Clone this repository:
```bash
git clone https://github.com/nduartex/cursor-rules-ruby-api.git
```

2. Copy the `.cursor` directory to your Ruby/Rails project:
```bash
cp -r cursor-rules-ruby-api/.cursor your-project/
```

3. Cursor will automatically load these rules and provide suggestions based on them.

## Rule Highlights

### API Design
- Consistent JSON response format
- Proper error handling
- Authentication and authorization
- Rate limiting and pagination
- Performance optimization

### Clean Code
- SOLID principles implementation
- Method and class organization
- Naming conventions
- Error handling patterns
- Code examples of good vs bad practices

### Security
- Authentication best practices
- Data encryption
- API security measures
- Secure headers configuration
- Audit logging

### Monitoring & Deployment
- Application monitoring setup
- Infrastructure monitoring
- Logging best practices
- CI/CD configuration
- Feature flags implementation
- Health checks

## Contributing

Feel free to submit pull requests to improve existing rules or add new ones. Please ensure your contributions:

1. Include practical examples
2. Follow Ruby/Rails best practices
3. Include proper documentation
4. Add tests when applicable
5. Consider security implications

## License

This project is available as open source under the terms of the MIT License.