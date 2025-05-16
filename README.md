# network-protocol

What kind of data do we want to receive, as raw as possible or formatted before sending?
Who is more in control the backend or the frontend?
Return an enum from all functions?

- Pick the data we want?
- Authentication?
- Caching?
- @deprecated attribute

## Data types
- string
- date
- uuid?
- int
- float
- boolean
- struct
- enum
- option
- array

## Procedures
A procedure takes in has one input type and one return type. The type can be a scalar, struct, enum or anything else.

```
struct User{}
proc get_user(uuid) -> User
```

## Semver
Follow semver and allow different x.y.z versions 
