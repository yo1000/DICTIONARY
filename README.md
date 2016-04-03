# DICTIONARY
NAMING DICTIONARY

## Controller

| Object               | Naming    | Note            |
|:---------------------|:----------|:----------------|
| Class - Page         | *Page     | @Controller     |
| Class - API          | *Resource | @RestController |
| Method - HTTP GET    | get*      |                 |
| Method - HTTP POST   | post*     |                 |
| Method - HTTP PUT    | put*      |                 |
| Method - HTTP DELETE | delete*   |                 |

## Service

| Object          | Naming      | Note        |
|:----------------|:------------|:------------|
| Class           | *Service    | @Service    |
| Method - Create | create*     |             |
| Method - Read   | find*       |             |
| Method - Update | modify*     |             |
| Method - Delete | remove*     |             |

## Repository

| Object          | Naming      | Note        |
|:----------------|:------------|:------------|
| Class           | *Repository | @Repository |
| Method - Create | insert*     |             |
| Method - Read   | select*     |             |
| Method - Update | update*     |             |
| Method - Delete | delete*     |             |
| Method - Exists | exists*     |             |
| Method - Count  | count*      |             |

## JPA methods

- http://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.query-methods.query-creation
- http://docs.spring.io/spring-data/jpa/docs/current/reference/html/#repositories.query-methods.query-property-expressions
