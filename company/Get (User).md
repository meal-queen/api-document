Path: `/api/company/users`

Method: `GET`

Request Body:

```json
{
		"company": String
		"take": int
		"page": int
		"role": AffiliationUserRoles [ ROLE_NOT_APPROVED, ROLE_USER, ROLE_ADMIN, ROLE_ROOT ]
}
```

Request Headers:

```json
{
		"Authorization": Bearer Token(String)
}
```
