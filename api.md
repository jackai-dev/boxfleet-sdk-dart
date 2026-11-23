# BoxFleet hosted control plane (boxfleet.io) Dart API

<!-- omniwrap-api-reference eyJjb250cmFjdF9maW5nZXJwcmludCI6ImUzZmQ0Yzc0NGFlODkzM2MwZTBiZDBjMjFhNjkyODk3Nzk1YTE0NjU3ZTU3N2ZiODIxMDg1MDBkMzlmMmFjOGQiLCJvcGVyYXRpb25fY291bnQiOjU2LCJyZW5kZXJlciI6ImRhcnQiLCJ2ZXJzaW9uIjoiMS41LjAifQ -->

This generated index is tied to Semantic IR `1.14.0` and contract fingerprint `e3fd4c744ae8933c0e0bd0c21a692897795a14657e577fb82108500d39f2ac8d`. Every operation below is rendered from the same semantic contract and artifact-attested public member allocation as the SDK.

SDK maturity: **experimental**  
Artifact evidence: [`omniwrap-artifact.json`](omniwrap-artifact.json) binds this file by SHA-256 and is revalidated by the package gate.

## Shared types

- `HostedPersistentBoxClose`
- `HostedPersistentBoxRead`
- `HostedPersistentUsageMeter`
- `HostedPersistentUsageRead`
- `ObservedBox`

## Resource `accounts`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRBY2NvdW50c0NvbmZpZyIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6ImdldEFjY291bnRzQ29uZmlnIiwicGF0aCI6Ii92MS9hY2NvdW50cy9jb25maWciLCJyZXNvdXJjZSI6ImFjY291bnRzIiwic2VjdGlvbl9zaGEyNTYiOiIzNjdlYTg4ODA4N2JlZjMzOTMwYTUzN2M1MDFiZGQ5MjVjZmQyYThiZTk5ZmRkMzJhNjhlZDRlOGZmMDMxOWI5Iiwic2lnbmF0dXJlX3NoYTI1NiI6IjZkY2ViZDAxY2I2ZTA5NzM4Njk1ZmU3ODMyNDAwM2IzMTkxZDgzNTgwMjYwNDgyYzY0OTg4OGIxOWY5MTlkZTUifQ -->
### `client.getAccountsConfig`

Operation ID: `getAccountsConfig`  
Route: `GET` `/v1/accounts/config`  

#### Signature

```dart
Future<ApiResponse> getAccountsConfig()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | OK | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRBY2NvdW50c0NvbmZpZyJ9 -->

## Resource `admin`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJjb250cm9sVXNlciIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJjb250cm9sVXNlciIsInBhdGgiOiIvdjEvYWRtaW4vdXNlcnMiLCJyZXNvdXJjZSI6ImFkbWluIiwic2VjdGlvbl9zaGEyNTYiOiJkZjBhZmMyOTAzNTFiNjk1YThjNWU5YmZlYjA5ZTQ1NTNiMjkwNDRiYmQzM2VmYWU3Mzk2YmFjMjAyZmMzNTU2Iiwic2lnbmF0dXJlX3NoYTI1NiI6IjAzMTliYzhhNWNlOGVkMDA0OTg2ZjU4ODczM2IwYTE1MDU3YzUyYjg4YTExNDM1MjM4YWZlYmQ2OTFlNmY5MzYifQ -->
### `client.controlUser`

Operation ID: `controlUser`  
Route: `POST` `/v1/admin/users`  

#### Signature

```dart
Future<ApiResponse> controlUser(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Applied | none |
| `401` | Admin token required | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJjb250cm9sVXNlciJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRBZG1pbkNvbnNvbGUiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJnZXRBZG1pbkNvbnNvbGUiLCJwYXRoIjoiL3YxL2FkbWluL2NvbnNvbGUiLCJyZXNvdXJjZSI6ImFkbWluIiwic2VjdGlvbl9zaGEyNTYiOiJhNzhhZTJkOTZkMjQ3M2JjOGY1YjlhODJlZDQ5NzA5ZDViYjk2ZjFhNzE3Y2M3ZTgxYTQ0ZGNlYzMzNzRhNGFhIiwic2lnbmF0dXJlX3NoYTI1NiI6IjQzNjBhMmNjNzRjMGI1OWEyNDBhZTZjMGU4ZmVjNTZkYWJkZWRhZjU1M2ViMmQwYWZjODAwMTllMDU1MTQzYzIifQ -->
### `client.getAdminConsole`

Operation ID: `getAdminConsole`  
Route: `GET` `/v1/admin/console`  

#### Signature

```dart
Future<ApiResponse> getAdminConsole()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Console | none |
| `401` | Admin token required | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRBZG1pbkNvbnNvbGUifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRBZG1pblBsYW5zIiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoiZ2V0QWRtaW5QbGFucyIsInBhdGgiOiIvdjEvYWRtaW4vcGxhbnMiLCJyZXNvdXJjZSI6ImFkbWluIiwic2VjdGlvbl9zaGEyNTYiOiIzZjYzOWY2NGRmMjMyZTQxNDA3ZTE4NjkyYTI2NmIxNTcxNWI3ZGJmMjIyMTg3YjE5MTBhM2RjNmFkNDgyNjU3Iiwic2lnbmF0dXJlX3NoYTI1NiI6Ijc1NjBmNTJhYjA0ODVhMjZhZjBkYjFjMDg0YjQyYjE2MDEzZTJmYTAwMzliODM4ZmE2ZDU0MDlmNzBjYzM0OWIifQ -->
### `client.getAdminPlans`

Operation ID: `getAdminPlans`  
Route: `GET` `/v1/admin/plans`  

#### Signature

```dart
Future<ApiResponse> getAdminPlans()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Plans | none |
| `401` | Admin token required | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRBZG1pblBsYW5zIn0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0VXNlcnMiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJsaXN0VXNlcnMiLCJwYXRoIjoiL3YxL2FkbWluL3VzZXJzIiwicmVzb3VyY2UiOiJhZG1pbiIsInNlY3Rpb25fc2hhMjU2IjoiNmUzMjIzODQyNWFiZjdlNzdlYjM1ZTA4YmVkYzZlYzU3Yjg2NWQ5OGFiNzcxY2Y4ZDgyZmE3MmZiMzdlMGYxNSIsInNpZ25hdHVyZV9zaGEyNTYiOiJhZmQwM2ZlOThmOTc1NjRhOTBlOTk4OTRjMjM5ZmM5MWIyNDM5ZjE0NTNhYTk3NjE1YjY3ZDVmNGQyZjQ5ODBmIn0 -->
### `client.listUsers`

Operation ID: `listUsers`  
Route: `GET` `/v1/admin/users`  

#### Signature

```dart
Future<ApiResponse> listUsers()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Users | none |
| `401` | Admin token required | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0VXNlcnMifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJyZWFkVGVsZW1ldHJ5IiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoicmVhZFRlbGVtZXRyeSIsInBhdGgiOiIvdjEvYWRtaW4vdGVsZW1ldHJ5IiwicmVzb3VyY2UiOiJhZG1pbiIsInNlY3Rpb25fc2hhMjU2IjoiODFhMTExNjIwMmY1M2FiNmNlMTc2YmE5ZDJkODRkM2RiNjhhMTI1OTJjYWE3MzA5MWQ1Yzk1M2ZiZTM1ZWIzMiIsInNpZ25hdHVyZV9zaGEyNTYiOiI1YjA1MmYyNDdjYzk2ZjQzY2Y5NzI4YjFiMDdlYjg0YzUwNjJjNDk4ODM1ZGYzYmQ4MjM1NzY2NTgyYmFmZDBlIn0 -->
### `client.readTelemetry`

Operation ID: `readTelemetry`  
Route: `GET` `/v1/admin/telemetry`  

#### Signature

```dart
Future<ApiResponse> readTelemetry()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Events | none |
| `401` | Admin token required | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJyZWFkVGVsZW1ldHJ5In0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJ1cGRhdGVQbGFuIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InVwZGF0ZVBsYW4iLCJwYXRoIjoiL3YxL2FkbWluL3BsYW5zIiwicmVzb3VyY2UiOiJhZG1pbiIsInNlY3Rpb25fc2hhMjU2IjoiZjg4NzI0ZDAwZTNiNWVjZmEzNzI3MGM2MTY5MzBlMzY1YTIxMzA5M2M1ZGViYjdmNWNmMGY3MzQ0MDY3ZTk0NCIsInNpZ25hdHVyZV9zaGEyNTYiOiI3ZGNkNGRlMWQ5MDc4ZDM5Y2U1NGRmYzBkZjc0NmZhNDE5NzE5NzhhYmYyNmNjNTQ2ZGFlMmViYmUwNTVkYzU1In0 -->
### `client.updatePlan`

Operation ID: `updatePlan`  
Route: `POST` `/v1/admin/plans`  

#### Signature

```dart
Future<ApiResponse> updatePlan(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Updated | none |
| `401` | Admin token required | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJ1cGRhdGVQbGFuIn0 -->

## Resource `auth`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRBdXRoR2F0ZSIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6ImdldEF1dGhHYXRlIiwicGF0aCI6Ii92MS9hdXRoL2dhdGUiLCJyZXNvdXJjZSI6ImF1dGgiLCJzZWN0aW9uX3NoYTI1NiI6ImE4MDlmYWI2ZTQzNzBmNjYzMGY0NWNjMGY3MGU1MWY5YzhjOTM0NDExODk5OWI1NDEyMDAwNjc4MDVjNTk3NDciLCJzaWduYXR1cmVfc2hhMjU2IjoiNjJhYTZjNWIwZWE4M2I5NzQ2MWJiOGU0MzNkMzk4ZWM3ZDAxYmIxZjAwMTM5NDllOTM4YTc2MWIwMGUzNDU0MyJ9 -->
### `client.getAuthGate`

Operation ID: `getAuthGate`  
Route: `GET` `/v1/auth/gate`  

#### Signature

```dart
Future<ApiResponse> getAuthGate()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | OK | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRBdXRoR2F0ZSJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJyZWdpc3RlciIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJyZWdpc3RlciIsInBhdGgiOiIvdjEvYXV0aC9yZWdpc3RlciIsInJlc291cmNlIjoiYXV0aCIsInNlY3Rpb25fc2hhMjU2IjoiYWQ4ZGZmNjAzMmZmZmVlZjAxYzg5OTdkNWIyYWFlODQxOTFjZjVkMzg1NTU0NmZhNjZkMDg2YjE0Y2FhYzAwNyIsInNpZ25hdHVyZV9zaGEyNTYiOiJkYTYzNTQzZWRjNzBmMjMzNjBmNzI4NGYwMzQyZDE2YTMxMGRhYjgyMWQ2MjQ1OTc4Y2QwZjFlZjEyYzhlNjY5In0 -->
### `client.register`

Operation ID: `register`  
Route: `POST` `/v1/auth/register`  

#### Signature

```dart
Future<ApiResponse> register(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `201` | License issued | none |
| `202` | Verification code sent (or withheld by the resend cooldown) | none |
| `400` | Invalid or expired code | none |
| `403` | Not invited or refused | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |
| `429` | Rate limited | none |
| `503` | Registration not configured | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJyZWdpc3RlciJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJ1cGRhdGVBdXRoR2F0ZSIsIm1ldGhvZCI6IlBVVCIsIm9wZXJhdGlvbl9pZCI6InVwZGF0ZUF1dGhHYXRlIiwicGF0aCI6Ii92MS9hdXRoL2dhdGUiLCJyZXNvdXJjZSI6ImF1dGgiLCJzZWN0aW9uX3NoYTI1NiI6IjhkMzM1MTRhYmUxNzJiMTE1OTIyNTc1MmFhZjQ2MTkxNGU3MjUyMzY0ZmFhMGM2OWNiN2VhODM5MjYzOGJjYjMiLCJzaWduYXR1cmVfc2hhMjU2IjoiYTg1YjI3MWJiMjY5Mzk4MDY0ZjZlN2RhYmIxODViMmNkNGIxMGNjMzczYWNhNzEyMzYxNzkyNWRjMDdmMDU3MCJ9 -->
### `client.updateAuthGate`

Operation ID: `updateAuthGate`  
Route: `PUT` `/v1/auth/gate`  

#### Signature

```dart
Future<ApiResponse> updateAuthGate(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Updated | none |
| `401` | Admin token required | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJ1cGRhdGVBdXRoR2F0ZSJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJ2ZXJpZnlMaWNlbnNlIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InZlcmlmeUxpY2Vuc2UiLCJwYXRoIjoiL3YxL2F1dGgvdmVyaWZ5IiwicmVzb3VyY2UiOiJhdXRoIiwic2VjdGlvbl9zaGEyNTYiOiI4OTViMjI3Y2JkOWU3YWE1ZTFkNzdmMWU0ODE5MDViNzUwYjJiYjk3YjEwZmIzOTY2ZWFkOTgzZjdlYzQ2ZjA2Iiwic2lnbmF0dXJlX3NoYTI1NiI6IjU3YTQxNGI5YmM5M2ZlNjdiNWJiYzAzZTc2ZWFhZTJkYmU0OWQxZTNkNzczZmFiMTFiNTc1ZjhiMzhkYTI3YjcifQ -->
### `client.verifyLicense`

Operation ID: `verifyLicense`  
Route: `POST` `/v1/auth/verify`  

#### Signature

```dart
Future<ApiResponse> verifyLicense(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Valid | none |
| `401` | Invalid license | none |
| `403` | Refused | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |
| `503` | Verification not configured | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJ2ZXJpZnlMaWNlbnNlIn0 -->

## Resource `billing`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJzdHJpcGVXZWJob29rIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InN0cmlwZVdlYmhvb2siLCJwYXRoIjoiL3YxL2JpbGxpbmcvc3RyaXBlL3dlYmhvb2siLCJyZXNvdXJjZSI6ImJpbGxpbmciLCJzZWN0aW9uX3NoYTI1NiI6ImY4YTdmMGNkZGQxZWFiOGJjNzM1ZWY5NThlZWMzNzg1MDI2MDQyNTFjNTQ5MGFiNWM4ODhhNjg5NjAyYmJjMzciLCJzaWduYXR1cmVfc2hhMjU2IjoiNmQyMGRjY2I4Yzc3MjQ3MWRjNmM1ODAzZGQ5YTVkMDJkNWE0NDU4ODRkM2ZhZTRkNWJjZjRlZjJlN2IzZDI3MCJ9 -->
### `client.stripeWebhook`

Operation ID: `stripeWebhook`  
Route: `POST` `/v1/billing/stripe/webhook`  

#### Signature

```dart
Future<ApiResponse> stripeWebhook()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Received | none |
| `400` | Invalid signature or payload | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJzdHJpcGVXZWJob29rIn0 -->

## Resource `health`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRIZWFsdGgiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJnZXRIZWFsdGgiLCJwYXRoIjoiL2hlYWx0aCIsInJlc291cmNlIjoiaGVhbHRoIiwic2VjdGlvbl9zaGEyNTYiOiJhMzRjMmVhZGMzMzViZTVlNTdlYjEwZjM2MzQ0NWExYTRlZTgyMDA2M2JjYWM3MWRkMjhlMDJjNTRjMjI5OWNjIiwic2lnbmF0dXJlX3NoYTI1NiI6IjExYWVhOWMzOGRiM2RmZGNmZTkyNmQ4OWJmZGUxMjZlZmU4MGU1YTE0MjliZTVjMDcwZjJhMTk0ZjJjMjU2NWEifQ -->
### `client.getHealth`

Operation ID: `getHealth`  
Route: `GET` `/health`  

#### Signature

```dart
Future<ApiResponse> getHealth()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | OK | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRIZWFsdGgifQ -->

## Resource `jobs`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJjYW5jZWxKb2IiLCJtZXRob2QiOiJQT1NUIiwib3BlcmF0aW9uX2lkIjoiY2FuY2VsSm9iIiwicGF0aCI6Ii92MS9qb2JzL3tqb2JJZH0vY2FuY2VsIiwicmVzb3VyY2UiOiJqb2JzIiwic2VjdGlvbl9zaGEyNTYiOiI4NDgzZDk1MGQ3MjEyMjQ5MGEwYWNjMGE4MmFkZjJhYTFlMDUwYmU3YWM5ZDA1Y2FiNzk0MTYyZjYwOWUxZWNmIiwic2lnbmF0dXJlX3NoYTI1NiI6IjIxOGE5YmMwNGQzMzMxZTFlM2VlYjgwODUxMmQ4M2VkNTg1ODdhMjE3MWQ2YjRiMTM5ZWRlZjU3NWQyYjQzOGYifQ -->
### `client.cancelJob`

Operation ID: `cancelJob`  
Route: `POST` `/v1/jobs/{jobId}/cancel`  

#### Signature

```dart
Future<ApiResponse> cancelJob(String jobId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `jobId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | OK | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "jobId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJjYW5jZWxKb2IifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRKb2IiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJnZXRKb2IiLCJwYXRoIjoiL3YxL2pvYnMve2pvYklkfSIsInJlc291cmNlIjoiam9icyIsInNlY3Rpb25fc2hhMjU2IjoiNzdjMGVjZjdiM2M5ODAyOGVhMWEwNmQ0ZGM1YTVkOTMxYjFiY2E1MGFlOWQ1NmE2NTgyZjkzMWUxMTIxMGJjZCIsInNpZ25hdHVyZV9zaGEyNTYiOiIyYzlkYWE4MGFmMGQzZDdlM2IxYTkxODc1OGNhZTg2NDgwZDE3YTRmNzE4YTIzMjkzYTYzMjdjMmJjMzI5ODMyIn0 -->
### `client.getJob`

Operation ID: `getJob`  
Route: `GET` `/v1/jobs/{jobId}`  

#### Signature

```dart
Future<ApiResponse> getJob(String jobId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `jobId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | OK | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "jobId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRKb2IifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0Sm9iRXZlbnRzIiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoibGlzdEpvYkV2ZW50cyIsInBhdGgiOiIvdjEvam9icy97am9iSWR9L2V2ZW50cyIsInJlc291cmNlIjoiam9icyIsInNlY3Rpb25fc2hhMjU2IjoiNjcyNjNmZjY4YjI5OGFiMDViNWEwZDBhMGMyNjQ3ZTZjNTFlNzY3OWNkOTA4ZDc3MDdiNTc5MjZiMWRhNWQ1YSIsInNpZ25hdHVyZV9zaGEyNTYiOiIzYTk3YjkxODc1NDBmZTg2MmJjOWJjMDdjZWQ1ZTI3YjJhNzU3Mzg5NzJjNzgzZjVjOTJhM2JjNDUwYjI0NWFjIn0 -->
### `client.listJobEvents`

Operation ID: `listJobEvents`  
Route: `GET` `/v1/jobs/{jobId}/events`  

#### Signature

```dart
Future<ApiResponse> listJobEvents(String jobId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `jobId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | OK | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "jobId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0Sm9iRXZlbnRzIn0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0Sm9icyIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6Imxpc3RKb2JzIiwicGF0aCI6Ii92MS9qb2JzIiwicmVzb3VyY2UiOiJqb2JzIiwic2VjdGlvbl9zaGEyNTYiOiJhMzQ1MzkwNjU5ZWQzYmY0YTM5Mjc5NzFlY2U5MmM0ZGIyMTM5YWMwOGQ5YjVmMTU1OGJjMzI1NzM4MDZkYWNlIiwic2lnbmF0dXJlX3NoYTI1NiI6ImJjYThjMWNlMmJhYjZlNjVhNWM4MmQwOTVlMzliMTEzMWNiM2ZjY2UxYTJiYThlZmUwYzhjMTVjZmQ1MTA0NzYifQ -->
### `client.listJobs`

Operation ID: `listJobs`  
Route: `GET` `/v1/jobs`  

#### Signature

```dart
Future<ApiResponse> listJobs()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Jobs | none |
| `401` | Session required | none |
| `503` | Storage not configured | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0Sm9icyJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJzdWJtaXRKb2IiLCJtZXRob2QiOiJQT1NUIiwib3BlcmF0aW9uX2lkIjoic3VibWl0Sm9iIiwicGF0aCI6Ii92MS9qb2JzIiwicmVzb3VyY2UiOiJqb2JzIiwic2VjdGlvbl9zaGEyNTYiOiI3NjQwYTUxZmQ3ZmY1ODMzYmM5ZTA4NDQ3OTc4YTFlYjk0NTA1Yzk3MDU0YjYwZjNiMTVhY2MwZjJkZDZjZjIxIiwic2lnbmF0dXJlX3NoYTI1NiI6IjM4YWY4MDk3MTNiODg3Yjc5NWY0NzRkNDZjZDE1ZDg4OTdlOWNmMGUyNDE4MGJkNDMzZjAwYzY3NzQzNzEzMzEifQ -->
### `client.submitJob`

Operation ID: `submitJob`  
Route: `POST` `/v1/jobs`  

#### Signature

```dart
Future<ApiResponse> submitJob(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Replayed | none |
| `201` | Created | none |
| `401` | Session required | none |
| `503` | Storage not configured | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJzdWJtaXRKb2IifQ -->

## Resource `organizations`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJjbG9zZVBlcnNpc3RlbnRCb3giLCJtZXRob2QiOiJQT1NUIiwib3BlcmF0aW9uX2lkIjoiY2xvc2VQZXJzaXN0ZW50Qm94IiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vcGVyc2lzdGVudC1ib3hlcy97Ym94SWR9L2Nsb3NlIiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiJkMGIxYzQ2YjQ0NjRlY2NjN2YwYmI5NWI4ZjAwNjI2NTIyZTZlMTVjYTc1ZjNmYTAwNWFmNmMyZWI5OGQ3YzFhIiwic2lnbmF0dXJlX3NoYTI1NiI6IjZhYmI5Yjk4ZGY4OTI4MDZkNWQ5ZTAxNmM4MzhiZmRmNzQ1N2VlZmNhOTMxNWQxOGZkMmFmODM2MTFhYmI3YjkifQ -->
### `client.closePersistentBox`

Operation ID: `closePersistentBox`  
Route: `POST` `/v1/organizations/{organizationId}/persistent-boxes/{boxId}/close`  

#### Signature

```dart
Future<ApiResponse> closePersistentBox(String organizationId, String boxId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `boxId` | `path` | yes | `string&lt;uuid&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Closure is recorded; repeat requests return the same result without deleting again. | application/json (HostedPersistentBoxClose) |
| `202` | Closure is unconfirmed. Lost, late, negative or mismatched acknowledgements and failed receipt persistence retain reservations. Repeat requests never dispatch another deletion; operator reconciliation is required. | application/json (HostedPersistentBoxClose) |
| `400` | Invalid UUID, body or query parameters. | none |
| `401` | Missing or rejected product session. | none |
| `403` | Current authority denied cleanup or the organization/product/environment differs. | none |
| `404` | No durable box in this exact target scope. | none |
| `409` | Unconfirmed or changed provider allocation requires operator reconciliation. | none |
| `503` | Authority or storage unavailable, or no matching operator provider adapter. Missing configuration refuses before any close intention or deletion. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "boxId",
      "value": "00000000-0000-0000-c54d-988d0e4e7e77"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJjbG9zZVBlcnNpc3RlbnRCb3gifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJjcmVhdGVCaWxsaW5nUG9ydGFsIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6ImNyZWF0ZUJpbGxpbmdQb3J0YWwiLCJwYXRoIjoiL3YxL29yZ2FuaXphdGlvbnMve29yZ2FuaXphdGlvbklkfS9iaWxsaW5nL3BvcnRhbCIsInJlc291cmNlIjoib3JnYW5pemF0aW9ucyIsInNlY3Rpb25fc2hhMjU2IjoiZDhkYWZhNWY0MmMyMDI5OTYyMjI5NzIwM2ZjMjQxYTg4ZWVmMTE3MDY1YTNkOTc0MjJiZGE2NDY0MGE1ZjUxNSIsInNpZ25hdHVyZV9zaGEyNTYiOiJhYjU3NWE0MzEzZTQzN2FhZmQxZjc5NmM0NWUyZTk4YTM2YzFiYzQ5ZDYzZjk3OTA2MGZiZTJhODg5NTg2MmQwIn0 -->
### `client.createBillingPortal`

Operation ID: `createBillingPortal`  
Route: `POST` `/v1/organizations/{organizationId}/billing/portal`  

#### Signature

```dart
Future<ApiResponse> createBillingPortal(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `201` | portalUrl | none |
| `404` | No Stripe customer yet | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJjcmVhdGVCaWxsaW5nUG9ydGFsIn0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJjcmVhdGVCb3giLCJtZXRob2QiOiJQT1NUIiwib3BlcmF0aW9uX2lkIjoiY3JlYXRlQm94IiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vYm94ZXMiLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6IjdkN2UwNTkxNjUwMzZjYjYxODIxMDNlNDMwOGFmMTE1Y2IyMzc5Y2EwZjk4OTg1MzJjZDUxMDE3ODY3NzAyNDMiLCJzaWduYXR1cmVfc2hhMjU2IjoiZWZhY2ZmODEyYmY5M2RkOGI2Yjg0NWIyZTVmMzY4OGM4Y2RiNDEyODI0Y2QwOGEyODhkNGY1ZDBhZTdjYTVlNiJ9 -->
### `client.createBox`

Operation ID: `createBox`  
Route: `POST` `/v1/organizations/{organizationId}/boxes`  

#### Signature

```dart
Future<ApiResponse> createBox(String organizationId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `201` | Box running at the provider | none |
| `402` | Concurrent-box limit reached | none |
| `502` | The provider refused; recorded as failed | none |
| `503` | No provider or no storage | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJjcmVhdGVCb3gifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJjcmVhdGVDaGVja291dCIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJjcmVhdGVDaGVja291dCIsInBhdGgiOiIvdjEvb3JnYW5pemF0aW9ucy97b3JnYW5pemF0aW9uSWR9L2JpbGxpbmcvY2hlY2tvdXQiLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6ImE2NjEzNzFlOGQ5NmZjNGViYWI2MGJiYjc4YTNlZDYyMzJhN2I0ZTdmMTM3MjJjMGNlNGE5NGNlZjQ3ODkxYzYiLCJzaWduYXR1cmVfc2hhMjU2IjoiNGIyYzFmMjVhOWY0ZTgxZDAwZDQ4MWEwZTZhOWEwYWU1Njc5Yzk4MmM0MjJiZWUyYTM2NGFjYjI4ZGEyMGFhMiJ9 -->
### `client.createCheckout`

Operation ID: `createCheckout`  
Route: `POST` `/v1/organizations/{organizationId}/billing/checkout`  

#### Signature

```dart
Future<ApiResponse> createCheckout(String organizationId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `201` | checkoutUrl of the Stripe Checkout Session | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. Autonomous mode: Plan not on sale or subscription exists | none |

#### Canonical required-input example

```json
{
  "body": {
    "planKey": "pro"
  },
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJjcmVhdGVDaGVja291dCJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRCaWxsaW5nIiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoiZ2V0QmlsbGluZyIsInBhdGgiOiIvdjEvb3JnYW5pemF0aW9ucy97b3JnYW5pemF0aW9uSWR9L2JpbGxpbmciLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6IjhkMGRjOGE1YWM5NmU2Y2M0NDg3NWE3YTkyYjY1ODJiMWY3MmRlNjUyY2M0NWU3NzRhZWE1ZWFhZThiOWMzMDYiLCJzaWduYXR1cmVfc2hhMjU2IjoiODVhNmZlM2IyNWMxNDA4M2VjNzM1ZGZkMjZkYzU2MWY3NzNhOTI5NjAwZTIyYjIyZGQ4MGM4OTk2NGY3NDBkMyJ9 -->
### `client.getBilling`

Operation ID: `getBilling`  
Route: `GET` `/v1/organizations/{organizationId}/billing`  

#### Signature

```dart
Future<ApiResponse> getBilling(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Billing status | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRCaWxsaW5nIn0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRCb3giLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJnZXRCb3giLCJwYXRoIjoiL3YxL29yZ2FuaXphdGlvbnMve29yZ2FuaXphdGlvbklkfS9ib3hlcy97Ym94SWR9IiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiJhNzA4YmRkZWJkZTZmZWY3NjZmNDlhYmUxMzU5ZDA3Y2VjZTdjZTc5NzNkYWU1NTdiMzI1Yjk3NjExNzAwODNmIiwic2lnbmF0dXJlX3NoYTI1NiI6ImVlZjNlNzg5NjZkNGI1MDY4MzBkYTdmMWRiMjY1MmI5ZDFhYzY5OWNkZmZhNWM2MmI2N2ZkNTE2NmNjOTc1YzkifQ -->
### `client.getBox`

Operation ID: `getBox`  
Route: `GET` `/v1/organizations/{organizationId}/boxes/{boxId}`  

#### Signature

```dart
Future<ApiResponse> getBox(String organizationId, String boxId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `boxId` | `path` | yes | `string&lt;uuid&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Stored box | none |
| `404` | Unknown box | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "boxId",
      "value": "00000000-0000-0000-d32a-0e84cb70d88a"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRCb3gifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRFbnRpdGxlbWVudHMiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJnZXRFbnRpdGxlbWVudHMiLCJwYXRoIjoiL3YxL29yZ2FuaXphdGlvbnMve29yZ2FuaXphdGlvbklkfS9lbnRpdGxlbWVudHMiLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6ImEyMzhmZWQ4YjExOGE2ZTE4OGJmMjMxYjhmZmFhZmI5MDNhM2JjNmE1YzYzOWJlMTdhMTYxYjZjZjRlMDFlZTAiLCJzaWduYXR1cmVfc2hhMjU2IjoiMDE5OWFkMDk2MjhkNmFmYzVjM2Y0OGNlODgxYTlmZjliY2M5OWNhODc0MWM2NWZmNTQwOGI3MDlkNDk3YWEwZSJ9 -->
### `client.getEntitlements`

Operation ID: `getEntitlements`  
Route: `GET` `/v1/organizations/{organizationId}/entitlements`  

#### Signature

```dart
Future<ApiResponse> getEntitlements(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Entitlements and usage | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRFbnRpdGxlbWVudHMifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRGbGVldCIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6ImdldEZsZWV0IiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vZmxlZXQiLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6IjMxNDgxZDIzYjIyMTY2OTczYWJhMDZlM2Y1ZWVkMjIxNDc0NTkzYjNjMzI5YmI2ZTZmZThlNWRjYjVlN2VhYjUiLCJzaWduYXR1cmVfc2hhMjU2IjoiMDY2OTc4OTQ4YWZjZjIxNGQxZTJiOWNhOWFlNjI4YzYxMzcyODhkMWQ1YTIyYzc0NDNlODQ5ODY4ZTUxNGExYSJ9 -->
### `client.getFleet`

Operation ID: `getFleet`  
Route: `GET` `/v1/organizations/{organizationId}/fleet`  

#### Signature

```dart
Future<ApiResponse> getFleet(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Stored fleet | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRGbGVldCJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRGbGVldFBvbGljeSIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6ImdldEZsZWV0UG9saWN5IiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vZmxlZXQvcG9saWN5IiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiIwMDdhNTcwN2M1MjdlNjFiN2Q4YjI1YTRiMWVlMDBlMmZhODFkYTIwZjY5NWI0MTFlOWMwNDg4YWMxNjgzYjRkIiwic2lnbmF0dXJlX3NoYTI1NiI6ImEzNGUyMWEyMTM0YjUxMDEzODc2NzAwMGZkOTg3MThjZTIyYTYzMzA0ZmUxMTgxZTQ3MDFkMDMyNWRjOWJiMzcifQ -->
### `client.getFleetPolicy`

Operation ID: `getFleetPolicy`  
Route: `GET` `/v1/organizations/{organizationId}/fleet/policy`  

#### Signature

```dart
Future<ApiResponse> getFleetPolicy(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Effective policy | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRGbGVldFBvbGljeSJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRQZXJzaXN0ZW50Qm94IiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoiZ2V0UGVyc2lzdGVudEJveCIsInBhdGgiOiIvdjEvb3JnYW5pemF0aW9ucy97b3JnYW5pemF0aW9uSWR9L3BlcnNpc3RlbnQtYm94ZXMve2JveElkfSIsInJlc291cmNlIjoib3JnYW5pemF0aW9ucyIsInNlY3Rpb25fc2hhMjU2IjoiYTAwN2QwMmM5NDFhYTQyMGYxMzQ4NzViM2I5ODAxZGUwYzg1NjY0NmQ3NWEyNDMwYjBiODFhOGI0ZWJmMjRhYyIsInNpZ25hdHVyZV9zaGEyNTYiOiIxZDMxNTA2NTQwZjIwOTZiZWIxMzhkNDI4MTBlNmMxNmE0NGM1NzQ0ZThhZmUxZTJiMGJhNWI2NzEyNDhiMmExIn0 -->
### `client.getPersistentBox`

Operation ID: `getPersistentBox`  
Route: `GET` `/v1/organizations/{organizationId}/persistent-boxes/{boxId}`  

#### Signature

```dart
Future<ApiResponse> getPersistentBox(String organizationId, String boxId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `boxId` | `path` | yes | `string&lt;uuid&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Private stored record and reserved budget; runtime status is not-metered. | application/json (object) |
| `400` | Invalid UUID or query parameters. | none |
| `401` | Missing or rejected product session. | none |
| `403` | Current authority denied access or the organization/product/environment differs. | none |
| `404` | No durable box in this exact target scope. | none |
| `503` | Authority or durable record storage unavailable. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "boxId",
      "value": "00000000-0000-0000-098c-d4f2b24057fb"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRQZXJzaXN0ZW50Qm94In0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRQZXJzaXN0ZW50Qm94UHJvdmlkZXJVc2FnZSIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6ImdldFBlcnNpc3RlbnRCb3hQcm92aWRlclVzYWdlIiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vcGVyc2lzdGVudC1ib3hlcy97Ym94SWR9L3VzYWdlIiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiI1ZTEzYTQ2NTk4MDZhYmUyNTUwNzBkYmQyYjkxNTk2YjcwOTRlMmEwZDJiM2RlNDc4YTJmOWEyMzRkMjk0NjRiIiwic2lnbmF0dXJlX3NoYTI1NiI6IjljZjYxZDVkNGZhYjI2M2Q3ZWNjNGEyMjY0NGEzZTU5MGRkZmFlNjExYzEwM2VhMjY4ZWRiZmY0OTYyYjBmNjYifQ -->
### `client.getPersistentBoxProviderUsage`

Operation ID: `getPersistentBoxProviderUsage`  
Route: `GET` `/v1/organizations/{organizationId}/persistent-boxes/{boxId}/usage`  

#### Signature

```dart
Future<ApiResponse> getPersistentBoxProviderUsage(String organizationId, String boxId, {Map<String, String> query = const {}})
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `boxId` | `path` | yes | `string&lt;uuid&gt;` |  |
| `from` | `query` | yes | `string&lt;date-time&gt;` |  |
| `to` | `query` | yes | `string&lt;date-time&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Private provider evidence summary with explicit interval coverage. | application/json (object) |
| `400` | Invalid box ID or bounded UTC window. | none |
| `401` | Missing or rejected product session. | none |
| `403` | Current authority denied access or target scope differs. | none |
| `404` | No durable box in this exact target scope. | none |
| `413` | Stored evidence exceeds the per-read record bound; select a smaller window. | none |
| `503` | Authority or usage storage unavailable. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "boxId",
      "value": "00000000-0000-0000-0848-7a89fcbe4ab4"
    },
    {
      "in": "query",
      "name": "from",
      "value": "2026-01-01T00:00:00Z"
    },
    {
      "in": "query",
      "name": "to",
      "value": "2026-01-01T00:00:27Z"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRQZXJzaXN0ZW50Qm94UHJvdmlkZXJVc2FnZSJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0Qm94ZXMiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJsaXN0Qm94ZXMiLCJwYXRoIjoiL3YxL29yZ2FuaXphdGlvbnMve29yZ2FuaXphdGlvbklkfS9ib3hlcyIsInJlc291cmNlIjoib3JnYW5pemF0aW9ucyIsInNlY3Rpb25fc2hhMjU2IjoiOWY5YTZjM2E2OWFhZWUxM2RiZTFlYTE4NGE4Mzk2NzMxNWNhOTNkYTgwZjM3OGM5Y2JlMzIwNTQyNGQ0Zjc3NSIsInNpZ25hdHVyZV9zaGEyNTYiOiI5MjkzZDdhZDYxODJmOTJkNjU3NjMwOTIxNGNkMmRlODVmMTQ1YzBlY2UzZDdkODU3ZjYxNThlNjAyYjJhNjNlIn0 -->
### `client.listBoxes`

Operation ID: `listBoxes`  
Route: `GET` `/v1/organizations/{organizationId}/boxes`  

#### Signature

```dart
Future<ApiResponse> listBoxes(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Stored boxes with their provider state | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0Qm94ZXMifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0SW52b2ljZXMiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJsaXN0SW52b2ljZXMiLCJwYXRoIjoiL3YxL29yZ2FuaXphdGlvbnMve29yZ2FuaXphdGlvbklkfS9iaWxsaW5nL2ludm9pY2VzIiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiJkNGQ0ZGRhMDM2YWVmNmQ1ZTliNWRlNDAxNWQ2YmJkMTkyY2NiMjk0ZTAyM2JjMjhkZDE2YmM4ZGZiY2YxNzRkIiwic2lnbmF0dXJlX3NoYTI1NiI6IjY4Zjc5YjQyN2YwNmE2MzUyNGRiNDVmMGI0YTgzMTU0OGFlMzJjYjcyMWYyOTQ5ZjBjMGE1N2MzMmY2Y2M2Y2UifQ -->
### `client.listInvoices`

Operation ID: `listInvoices`  
Route: `GET` `/v1/organizations/{organizationId}/billing/invoices`  

#### Signature

```dart
Future<ApiResponse> listInvoices(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Invoices | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0SW52b2ljZXMifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0TWVtYmVycyIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6Imxpc3RNZW1iZXJzIiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vbWVtYmVycyIsInJlc291cmNlIjoib3JnYW5pemF0aW9ucyIsInNlY3Rpb25fc2hhMjU2IjoiMzI2OWYzODJjMzQ4YTI1MTRlYzUwYTFkYzdkYjYwODc5MzY5ZDZmYWI0MGNkZGNkN2VjYTVhZWQxMjNiNjlkZSIsInNpZ25hdHVyZV9zaGEyNTYiOiI3MTQ2YzE4MzEwMTRlMjliMjRlNzZkYzc2NzgyMDM1MjY5MDQ2YzdmNmIzZTdlYjUwMTk2YzhkMjY5NGQ4MzA4In0 -->
### `client.listMembers`

Operation ID: `listMembers`  
Route: `GET` `/v1/organizations/{organizationId}/members`  

#### Signature

```dart
Future<ApiResponse> listMembers(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Stored members and the plan seat limit | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0TWVtYmVycyJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0T2JzZXJ2ZWRCb3hlcyIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6Imxpc3RPYnNlcnZlZEJveGVzIiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vb2JzZXJ2ZWQtYm94ZXMiLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6ImMzMjcyM2ZlMmZkYTRmNDFkMGQ5Mjc1MjAzMjFjOWM3OWI4ZjkzZWUyY2E4Yzc4MWQ5Y2M5MWI0NmJjZmVjNjIiLCJzaWduYXR1cmVfc2hhMjU2IjoiNzNiMDRjNTE3NGJhN2EwZGZjYzY1MmRiOTAxNTllZThlN2Q1MTFiMzRmN2ZkNWE3MzVlM2IzNDRlZGQxNTQ0MyJ9 -->
### `client.listObservedBoxes`

Operation ID: `listObservedBoxes`  
Route: `GET` `/v1/organizations/{organizationId}/observed-boxes`  

#### Signature

```dart
Future<ApiResponse> listObservedBoxes(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Up to 100 non-expired client snapshots, private and not cacheable. | application/json (object) |
| `401` | No valid product session. | none |
| `403` | Organization or scope denied. | none |
| `503` | Inventory storage unavailable. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0T2JzZXJ2ZWRCb3hlcyJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0UGVyc2lzdGVudEJveE9mZmVycyIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6Imxpc3RQZXJzaXN0ZW50Qm94T2ZmZXJzIiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vcGVyc2lzdGVudC1ib3hlcy9vZmZlcnMiLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6ImY5Nzk4OWNjYzJhMDJjNDBlYWIwYTM1N2U1ZDQ1Y2ViYzllYTcxOTdmZjZlYmY1ZTRjMDRlZDAxZDE3NWQ3ZDUiLCJzaWduYXR1cmVfc2hhMjU2IjoiMTFjNmJlZTgxOWI0ZTNiNTY5M2I4Y2I4MzRkM2I2OGU2M2Q0OTEwOTVkMTc2M2VjMjdhZWRlNjZlOWVjNDJhOCJ9 -->
### `client.listPersistentBoxOffers`

Operation ID: `listPersistentBoxOffers`  
Route: `GET` `/v1/organizations/{organizationId}/persistent-boxes/offers`  

#### Signature

```dart
Future<ApiResponse> listPersistentBoxOffers(String organizationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Private configured offers. | application/json (object) |
| `401` | Product session required. | none |
| `403` | Current read authority denied. | none |
| `503` | Storage or operator offer configuration unavailable. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0UGVyc2lzdGVudEJveE9mZmVycyJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0UGVyc2lzdGVudEJveGVzIiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoibGlzdFBlcnNpc3RlbnRCb3hlcyIsInBhdGgiOiIvdjEvb3JnYW5pemF0aW9ucy97b3JnYW5pemF0aW9uSWR9L3BlcnNpc3RlbnQtYm94ZXMiLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6IjRlNTk2OGFkYTU5YTllZTk2NzU5NjQ3YzI1YjU0ZjNjZWFjMGI0MTRjNGQ0NDAwYWFiZjA1YTAwMGMyMDg5M2EiLCJzaWduYXR1cmVfc2hhMjU2IjoiYThmMzJhZWRhNzc2MTJhNWJkM2NiODYwZTEzZWU5ZTA3OWQzYjQ2MTRlZDE4NzFmMzJhOGUzNWYyNjQzYTRhNSJ9 -->
### `client.listPersistentBoxes`

Operation ID: `listPersistentBoxes`  
Route: `GET` `/v1/organizations/{organizationId}/persistent-boxes`  

#### Signature

```dart
Future<ApiResponse> listPersistentBoxes(String organizationId, {Map<String, String> query = const {}})
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `limit` | `query` | no | `integer` | Maximum recent records; duplicates and other query parameters are rejected. |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Bounded stored records, private and not cacheable. limitReached indicates the requested bound was filled, not an exact total or proof that more records exist. | application/json (object) |
| `400` | Invalid query parameters. | none |
| `401` | Missing or rejected product session. | none |
| `403` | Current authority denied access or the organization/product/environment differs. | none |
| `503` | Authority or durable record storage unavailable. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0UGVyc2lzdGVudEJveGVzIn0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJwcm92aXNpb25QZXJzaXN0ZW50Qm94IiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InByb3Zpc2lvblBlcnNpc3RlbnRCb3giLCJwYXRoIjoiL3YxL29yZ2FuaXphdGlvbnMve29yZ2FuaXphdGlvbklkfS9wZXJzaXN0ZW50LWJveGVzIiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiI1MTY2Y2U1ZDllY2FkMTA2MDExMzU3NzYyNDQ4MDIwMTM4NmQ5ZDQwMzEwNWIxMTY2ZmViMjczNjcyZmE2OWRiIiwic2lnbmF0dXJlX3NoYTI1NiI6Ijk0NzJmZjY1MWNlZWEzMjE0M2FlNjdhM2FiNTljMTMyMDcxNTI3YjQ1MjE4MGU2Y2U5NGY4NDY2YTJlMGU3N2EifQ -->
### `client.provisionPersistentBox`

Operation ID: `provisionPersistentBox`  
Route: `POST` `/v1/organizations/{organizationId}/persistent-boxes`  

#### Signature

```dart
Future<ApiResponse> provisionPersistentBox(String organizationId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `Idempotency-Key` | `header` | no | `string` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Previously recorded running or closed allocation; replayed is true. | none |
| `201` | Provider allocation confirmed and recorded as running. Runtime remains reserved, not measured. | application/json (object) |
| `202` | The reservation is held and the allocation remains unconfirmed. Repeated requests never dispatch create again; operator reconciliation is required. | none |
| `400` | Invalid body, unsupported fields, query parameters or idempotency key. | none |
| `401` | Missing or rejected product session. | none |
| `402` | Missing durable entitlement, bounded allowance or available capacity. | none |
| `403` | Current authority denied the operation or target scope. | none |
| `409` | Idempotency conflict, unresolved prior budget or UTC month boundary. | none |
| `413` | Request body exceeds 4 KiB. | none |
| `503` | Authority, storage, operator offer or independent runtime enforcement unavailable. Missing configuration is refused before reservation. | none |

#### Canonical required-input example

```json
{
  "body": {
    "offer": "example",
    "reserveMinutes": 1
  },
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJwcm92aXNpb25QZXJzaXN0ZW50Qm94In0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJwdXRGbGVldFBvbGljeSIsIm1ldGhvZCI6IlBVVCIsIm9wZXJhdGlvbl9pZCI6InB1dEZsZWV0UG9saWN5IiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vZmxlZXQvcG9saWN5IiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiJmNTBiMDExNTA0YTY1MmYwZWEzODRmZGJhYWE3MWI2YmJhMzI3OTkwNzUwMjE4NDE2NDdjNDQ3NTBlZmNlOGIzIiwic2lnbmF0dXJlX3NoYTI1NiI6ImMxM2YzYjI5OTBlNzU5OWE1MTUxNjgyOWMwYjc5MjZkYjJiZjlhYWU2NzZhODYwNzExYjQyNGM2ZTM5MzhmMTkifQ -->
### `client.putFleetPolicy`

Operation ID: `putFleetPolicy`  
Route: `PUT` `/v1/organizations/{organizationId}/fleet/policy`  

#### Signature

```dart
Future<ApiResponse> putFleetPolicy(String organizationId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Stored policy | none |
| `400` | Invalid or unenforced field | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJwdXRGbGVldFBvbGljeSJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJyZWNvbmNpbGVQZXJzaXN0ZW50Qm94IiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InJlY29uY2lsZVBlcnNpc3RlbnRCb3giLCJwYXRoIjoiL3YxL29yZ2FuaXphdGlvbnMve29yZ2FuaXphdGlvbklkfS9wZXJzaXN0ZW50LWJveGVzL3tib3hJZH0vcmVjb25jaWxlIiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiJlODhlNDhkOWYwMjMxYzBjMzVlODAxMDA4NDJmNDZjOTQ1YTdiZTA3ODVmYTE1NTMwNDM2MjMzNTI0N2NiMTdjIiwic2lnbmF0dXJlX3NoYTI1NiI6IjYwMGZmZmE0NDJjMjk4ZDQyNWNhN2JjZWM3NDZjMjc5MjZlNmI1Mjc2ODNkY2Q3YjMyZWIyMTIzZmI3M2Y1NTQifQ -->
### `client.reconcilePersistentBox`

Operation ID: `reconcilePersistentBox`  
Route: `POST` `/v1/organizations/{organizationId}/persistent-boxes/{boxId}/reconcile`  

#### Signature

```dart
Future<ApiResponse> reconcilePersistentBox(String organizationId, String boxId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `boxId` | `path` | yes | `string&lt;uuid&gt;` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Confirmed operation or replayed receipt. | application/json (object) |
| `202` | Operation remains unconfirmed; reconcile its operation ID without repeating the mutation. | application/json (object) |
| `400` | Invalid bounded lifecycle request. | none |
| `401` | Product session required. | none |
| `402` | Durable feature or quota denied. | none |
| `403` | Fresh operation authority denied. | none |
| `404` | Box or operation missing in the exact organization and deployment. | none |
| `409` | Conflicting operation, unresolved evidence or unavailable runtime budget. | none |
| `503` | Authority, storage or matching operator adapter unavailable. | none |

#### Canonical required-input example

```json
{
  "body": {
    "operationId": "00000000-0000-0000-f735-3d332872b96e"
  },
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "boxId",
      "value": "00000000-0000-0000-a264-3ce9cdfbbeff"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJyZWNvbmNpbGVQZXJzaXN0ZW50Qm94In0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJyZW1vdmVNZW1iZXIiLCJtZXRob2QiOiJERUxFVEUiLCJvcGVyYXRpb25faWQiOiJyZW1vdmVNZW1iZXIiLCJwYXRoIjoiL3YxL29yZ2FuaXphdGlvbnMve29yZ2FuaXphdGlvbklkfS9tZW1iZXJzL3t1c2VySWR9IiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiIzOTFiZjY2OTVlMDYxNTNjNzNiMDQ4NGMyYTQxOGI5YjAyNmQ4NWU2NDBlMzYyNGJiZTZkODJhNzc2N2I3M2I2Iiwic2lnbmF0dXJlX3NoYTI1NiI6ImQ1OWQ4NTA5NzdhNzZiNGY4N2Y3ZWFiOTc2NjcxNzk2OThhMjdmZjBiMzM0NWNiMGYyMzIyNjAwYTA3MjA4NzEifQ -->
### `client.removeMember`

Operation ID: `removeMember`  
Route: `DELETE` `/v1/organizations/{organizationId}/members/{userId}`  

#### Signature

```dart
Future<ApiResponse> removeMember(String organizationId, String userId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `userId` | `path` | yes | `string` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Removed | none |
| `404` | Unknown member | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "userId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJyZW1vdmVNZW1iZXIifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJzdGFydFBlcnNpc3RlbnRCb3giLCJtZXRob2QiOiJQT1NUIiwib3BlcmF0aW9uX2lkIjoic3RhcnRQZXJzaXN0ZW50Qm94IiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vcGVyc2lzdGVudC1ib3hlcy97Ym94SWR9L3N0YXJ0IiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiIyMDZjZjNmNzNjZDI4ZTZjOGZlOGM4Mzk1MmFlYTRiNDlkNmI2MDcxNmUzMGI3NzhjYWEyYzc1MDFkZTg4ODJhIiwic2lnbmF0dXJlX3NoYTI1NiI6IjE5NzZmNzBiOTcxYzFhMDMzZmIyYTQyNDg2ZjY0MmM4OTY4Y2U2N2MxZjQ1NmNlNzQxMzUzNDAxMDAzZDJlZDkifQ -->
### `client.startPersistentBox`

Operation ID: `startPersistentBox`  
Route: `POST` `/v1/organizations/{organizationId}/persistent-boxes/{boxId}/start`  

#### Signature

```dart
Future<ApiResponse> startPersistentBox(String organizationId, String boxId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `boxId` | `path` | yes | `string&lt;uuid&gt;` |  |
| `Idempotency-Key` | `header` | no | `string` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Confirmed operation or replayed receipt. | application/json (object) |
| `202` | Operation remains unconfirmed; reconcile its operation ID without repeating the mutation. | application/json (object) |
| `400` | Invalid bounded lifecycle request. | none |
| `401` | Product session required. | none |
| `402` | Durable feature or quota denied. | none |
| `403` | Fresh operation authority denied. | none |
| `404` | Box or operation missing in the exact organization and deployment. | none |
| `409` | Conflicting operation, unresolved evidence or unavailable runtime budget. | none |
| `503` | Authority, storage or matching operator adapter unavailable. | none |

#### Canonical required-input example

```json
{
  "body": {
    "reserveMinutes": 1
  },
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "boxId",
      "value": "00000000-0000-0000-d7e8-d81c5e30ed9a"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJzdGFydFBlcnNpc3RlbnRCb3gifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJzdG9wQm94IiwibWV0aG9kIjoiREVMRVRFIiwib3BlcmF0aW9uX2lkIjoic3RvcEJveCIsInBhdGgiOiIvdjEvb3JnYW5pemF0aW9ucy97b3JnYW5pemF0aW9uSWR9L2JveGVzL3tib3hJZH0iLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6ImQ0NGZkMjgwNTNjZDFkZjNjNWU5MWM0ZjMxOGE4YzllMTcwMmM2Njc0YzRkMmE3YmYwYzU5YzgzZDYzMmUwOTYiLCJzaWduYXR1cmVfc2hhMjU2IjoiMDM4MTkxZDY2MGQ2NTU1ZDgyNGVhMmU4MWNmYjk2ZjVjYjU1MDMwNzM0Y2JiODU3Nzk0ZTNmMGY0YTJmOGMyOSJ9 -->
### `client.stopBox`

Operation ID: `stopBox`  
Route: `DELETE` `/v1/organizations/{organizationId}/boxes/{boxId}`  

#### Signature

```dart
Future<ApiResponse> stopBox(String organizationId, String boxId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `boxId` | `path` | yes | `string&lt;uuid&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Stopped | none |
| `502` | The provider refused; state unchanged | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "boxId",
      "value": "00000000-0000-0000-265e-7c895c60153e"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJzdG9wQm94In0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJzdG9wUGVyc2lzdGVudEJveCIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJzdG9wUGVyc2lzdGVudEJveCIsInBhdGgiOiIvdjEvb3JnYW5pemF0aW9ucy97b3JnYW5pemF0aW9uSWR9L3BlcnNpc3RlbnQtYm94ZXMve2JveElkfS9zdG9wIiwicmVzb3VyY2UiOiJvcmdhbml6YXRpb25zIiwic2VjdGlvbl9zaGEyNTYiOiIwNDRiMGFhNDA4MmU0M2EzYjU3NWQ3NWJkZmMzZDNkZGM3Y2UwZjNlOWYwZmMyYmQ3NTU1MjlmNDY3YWVlNGQzIiwic2lnbmF0dXJlX3NoYTI1NiI6IjExNTdhNDY5NWMxZWMzMTZjNzhiMDQxMmFhZTkwM2FkM2E2MGYyZDMwMmFlMGFhMDNiZDcwYWI5MjdlMjdhNWQifQ -->
### `client.stopPersistentBox`

Operation ID: `stopPersistentBox`  
Route: `POST` `/v1/organizations/{organizationId}/persistent-boxes/{boxId}/stop`  

#### Signature

```dart
Future<ApiResponse> stopPersistentBox(String organizationId, String boxId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `boxId` | `path` | yes | `string&lt;uuid&gt;` |  |
| `Idempotency-Key` | `header` | no | `string` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Confirmed operation or replayed receipt. | application/json (object) |
| `202` | Operation remains unconfirmed; reconcile its operation ID without repeating the mutation. | application/json (object) |
| `400` | Invalid bounded lifecycle request. | none |
| `401` | Product session required. | none |
| `402` | Durable feature or quota denied. | none |
| `403` | Fresh operation authority denied. | none |
| `404` | Box or operation missing in the exact organization and deployment. | none |
| `409` | Conflicting operation, unresolved evidence or unavailable runtime budget. | none |
| `503` | Authority, storage or matching operator adapter unavailable. | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    },
    {
      "in": "path",
      "name": "boxId",
      "value": "00000000-0000-0000-978f-a93165cf6579"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJzdG9wUGVyc2lzdGVudEJveCJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJzeW5jT2JzZXJ2ZWRCb3hlcyIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJzeW5jT2JzZXJ2ZWRCb3hlcyIsInBhdGgiOiIvdjEvb3JnYW5pemF0aW9ucy97b3JnYW5pemF0aW9uSWR9L29ic2VydmVkLWJveGVzL3N5bmMiLCJyZXNvdXJjZSI6Im9yZ2FuaXphdGlvbnMiLCJzZWN0aW9uX3NoYTI1NiI6ImNiMTk0NzAwZWEyNDBlNTAxZGQ2MTFjOTVkYWI0YmNiZWQ3ZTljNTI1MTk0MTc5YzBiZWFiYTFkMmEwMWMxM2YiLCJzaWduYXR1cmVfc2hhMjU2IjoiMjlmYmM3OWFlZDVkMTI2YzI0NDA5MWYyYzdiZWExYTQ1MGVkNTUyMDBiNmU4NTRjNjA4ZTdlY2Y0MTllMjlhYSJ9 -->
### `client.syncObservedBoxes`

Operation ID: `syncObservedBoxes`  
Route: `POST` `/v1/organizations/{organizationId}/observed-boxes/sync`  

#### Signature

```dart
Future<ApiResponse> syncObservedBoxes(String organizationId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Snapshot accepted; private and not cacheable. | application/json (object) |
| `400` | Invalid observation snapshot. | none |
| `401` | No valid product session. | none |
| `403` | Organization or scope denied. | none |
| `413` | Snapshot exceeds 64 KiB. | none |
| `503` | Inventory storage unavailable. | none |

#### Canonical required-input example

```json
{
  "body": {
    "boxes": [
      {
        "boxId": "example",
        "kind": "provider-list",
        "provider": "example",
        "state": "running"
      }
    ],
    "sourceId": "00000000-0000-0000-ae61-93cfab8e5e4b"
  },
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJzeW5jT2JzZXJ2ZWRCb3hlcyJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJ1cHNlcnRNZW1iZXIiLCJtZXRob2QiOiJQT1NUIiwib3BlcmF0aW9uX2lkIjoidXBzZXJ0TWVtYmVyIiwicGF0aCI6Ii92MS9vcmdhbml6YXRpb25zL3tvcmdhbml6YXRpb25JZH0vbWVtYmVycyIsInJlc291cmNlIjoib3JnYW5pemF0aW9ucyIsInNlY3Rpb25fc2hhMjU2IjoiNmI3NDcwNjA2Yzc1ZDQ3YWExOGM3NjIxMjA1NjE0ODFlYTYxNDZkMjRiMGQ1M2QxNzY4YmY3OTJkMjdlNTkzZiIsInNpZ25hdHVyZV9zaGEyNTYiOiIwNGU4MzE2NTk5MTA0MGQ1ODYxN2U2MTQzYmE5MmQxYmY3OTMxNzk5NThlNGI3MjcyN2QyMDYzYTU3ODkxODQ2In0 -->
### `client.upsertMember`

Operation ID: `upsertMember`  
Route: `POST` `/v1/organizations/{organizationId}/members`  

#### Signature

```dart
Future<ApiResponse> upsertMember(String organizationId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `organizationId` | `path` | yes | `string` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Member updated | none |
| `201` | Member added | none |
| `402` | Seat limit reached or entitlement missing | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "body": {
    "email": "example-f35c@example.test",
    "role": "owner"
  },
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "organizationId",
      "value": "example"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJ1cHNlcnRNZW1iZXIifQ -->

## Resource `plans`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRQbGFucyIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6ImdldFBsYW5zIiwicGF0aCI6Ii92MS9wbGFucyIsInJlc291cmNlIjoicGxhbnMiLCJzZWN0aW9uX3NoYTI1NiI6IjRkYTk4OTgyZGJjMTA3Yjk4M2ExYTc0MWYzOTMzZjcxZjhmNTBlNWFlNzk4YTdhNjQyZWRjMzQ0ODdiZjNiNzkiLCJzaWduYXR1cmVfc2hhMjU2IjoiMTFkYzkzOWQ3ZmVkYzA4NGM0M2I3NjUzODg3YWU3MjljNjFmMTU4ZjdiOTc1YTAwYTlhZTk3N2I3YTA1ZGQyMCJ9 -->
### `client.getPlans`

Operation ID: `getPlans`  
Route: `GET` `/v1/plans`  

#### Signature

```dart
Future<ApiResponse> getPlans()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | OK | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRQbGFucyJ9 -->

## Resource `telemetry`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJpbmdlc3RUZWxlbWV0cnkiLCJtZXRob2QiOiJQT1NUIiwib3BlcmF0aW9uX2lkIjoiaW5nZXN0VGVsZW1ldHJ5IiwicGF0aCI6Ii92MS90ZWxlbWV0cnkvaW5nZXN0IiwicmVzb3VyY2UiOiJ0ZWxlbWV0cnkiLCJzZWN0aW9uX3NoYTI1NiI6IjM0MWQ1NzkxZGVjNzNhOWYyYWIwMmE3ZDNmNjE4MmVjMzMzN2Y1OTE1ZTA4ZmYzNjE4NjBhZTA2NDhjOTFmYzQiLCJzaWduYXR1cmVfc2hhMjU2IjoiMTdiZTJhODM0MzU2M2QyNjc5NTkzNWExY2VkODNiNjAyMDBjMWQwYWIyMDQ0MGJmNDQ4YWM5YjMwMDdiYTI1MyJ9 -->
### `client.ingestTelemetry`

Operation ID: `ingestTelemetry`  
Route: `POST` `/v1/telemetry/ingest`  

#### Signature

```dart
Future<ApiResponse> ingestTelemetry(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `201` | Stored | none |
| `400` | Invalid event | none |
| `401` | License required | none |
| `409` | Managed account authority required; use the returned JackAISaaS accountUrl or portalUrl. | none |
| `413` | Body too large | none |
| `503` | Ingestion not configured | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJpbmdlc3RUZWxlbWV0cnkifQ -->

## Resource `waitlist`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0V2FpdGxpc3QiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJsaXN0V2FpdGxpc3QiLCJwYXRoIjoiL3YxL3dhaXRsaXN0IiwicmVzb3VyY2UiOiJ3YWl0bGlzdCIsInNlY3Rpb25fc2hhMjU2IjoiNzlmMTE0OGI1NzEwY2FkN2MzOTkxYTI0NWVhNjc1YjUyOTMwNGYwMjM2ZWRlMWZmMTZiMjQ3ZGFmNDg3MDBjNiIsInNpZ25hdHVyZV9zaGEyNTYiOiIwOTkwYjE3ZmRiMTY2MGZiYWQ5Mjk3OGMwNWYwYTA2MmU0ZThjMDJmYjQ1NWE2NzRlMGI2ZjVmZTUwMjY2NTViIn0 -->
### `client.listWaitlist`

Operation ID: `listWaitlist`  
Route: `GET` `/v1/waitlist`  

#### Signature

```dart
Future<ApiResponse> listWaitlist()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Requests | none |
| `401` | Admin token required | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0V2FpdGxpc3QifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJyZXF1ZXN0QWNjZXNzIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InJlcXVlc3RBY2Nlc3MiLCJwYXRoIjoiL3YxL3dhaXRsaXN0IiwicmVzb3VyY2UiOiJ3YWl0bGlzdCIsInNlY3Rpb25fc2hhMjU2IjoiNDUxNDZjMjhiZTQ0YjhjZjI0YTVkZGY2YzIxNmVlM2U0ZWJjZTU3YmExMTEyNDEzYzFhZWVjNzQ5NzI2Nzc1YiIsInNpZ25hdHVyZV9zaGEyNTYiOiIwYzEzOTllZDE5ZjZlMDBiOTk4NTEwY2VlNGM0YjAyODZjMzdlOWI5YzUyZjE3NzkxNWMwYTFkYzRiMTY0YmUwIn0 -->
### `client.requestAccess`

Operation ID: `requestAccess`  
Route: `POST` `/v1/waitlist`  

#### Signature

```dart
Future<ApiResponse> requestAccess(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `202` | Received | none |
| `400` | Invalid email | none |
| `413` | Body too large | none |
| `429` | Rate limited | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJyZXF1ZXN0QWNjZXNzIn0 -->

## Resource `workspaces`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJjbG9zZUhvc3RlZFdvcmtzcGFjZSIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJjbG9zZUhvc3RlZFdvcmtzcGFjZSIsInBhdGgiOiIvdjEvd29ya3NwYWNlcy97d29ya3NwYWNlSWR9L2Nsb3NlIiwicmVzb3VyY2UiOiJ3b3Jrc3BhY2VzIiwic2VjdGlvbl9zaGEyNTYiOiIxYmRhNTljMmI1MWUwMWExMTljZmQyODc0ZjdlYWMyZTQwN2M2NTJjMTU5ZjNiMTNlNTRmZmZkY2IzNTczY2MyIiwic2lnbmF0dXJlX3NoYTI1NiI6ImJlZWZhMDY5MzM5NWY0NTlhOGUyYzI1MWEyOTBkZmI2OTUwOGYwYmUwYmU0MTY3NTJlNmJkYjZmZmI4ZTg0OWQifQ -->
### `client.closeHostedWorkspace`

Operation ID: `closeHostedWorkspace`  
Route: `POST` `/v1/workspaces/{workspaceId}/close`  

#### Signature

```dart
Future<ApiResponse> closeHostedWorkspace(String workspaceId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `workspaceId` | `path` | yes | `string&lt;uuid&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authorized workspace state or result | none |
| `400` | Invalid bounded request | none |
| `401` | Product session rejected | none |
| `402` | Hub entitlement or atomic quota denied | none |
| `403` | Operation or fleet policy denied | none |
| `404` | Resource not found in the authorized tenant and product environment | none |
| `409` | Idempotency conflict, incompatible state or cleanup unconfirmed | none |
| `503` | Operator provider, template, storage or authority unavailable | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "workspaceId",
      "value": "00000000-0000-0000-6658-e129a559a4dd"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJjbG9zZUhvc3RlZFdvcmtzcGFjZSJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRIb3N0ZWRXb3Jrc3BhY2UiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJnZXRIb3N0ZWRXb3Jrc3BhY2UiLCJwYXRoIjoiL3YxL3dvcmtzcGFjZXMve3dvcmtzcGFjZUlkfSIsInJlc291cmNlIjoid29ya3NwYWNlcyIsInNlY3Rpb25fc2hhMjU2IjoiMzhjYTRmODQ4OGQ4OGI0OWRiZjdhMDkyZDlhY2UxOTA3Mjc1NjYwY2EzNDYzNjdiNTc4YmE0MWExM2Q3ODdmMCIsInNpZ25hdHVyZV9zaGEyNTYiOiJhNzRlNmRjODQ1ZDNjOWMzMDg0MzM3NmQxZDJlMjJhMTFjOTI1NmNkODVmZDAxYjI4ODIyMTI0ZGMxOWYxYjg4In0 -->
### `client.getHostedWorkspace`

Operation ID: `getHostedWorkspace`  
Route: `GET` `/v1/workspaces/{workspaceId}`  

#### Signature

```dart
Future<ApiResponse> getHostedWorkspace(String workspaceId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `workspaceId` | `path` | yes | `string&lt;uuid&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authorized workspace state or result | none |
| `400` | Invalid bounded request | none |
| `401` | Product session rejected | none |
| `402` | Hub entitlement or atomic quota denied | none |
| `403` | Operation or fleet policy denied | none |
| `404` | Resource not found in the authorized tenant and product environment | none |
| `409` | Idempotency conflict, incompatible state or cleanup unconfirmed | none |
| `503` | Operator provider, template, storage or authority unavailable | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "workspaceId",
      "value": "00000000-0000-0000-dd2f-cd2edd1eeb24"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRIb3N0ZWRXb3Jrc3BhY2UifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRIb3N0ZWRXb3Jrc3BhY2VPcGVyYXRpb24iLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJnZXRIb3N0ZWRXb3Jrc3BhY2VPcGVyYXRpb24iLCJwYXRoIjoiL3YxL3dvcmtzcGFjZXMve3dvcmtzcGFjZUlkfS9vcGVyYXRpb25zL3tvcGVyYXRpb25JZH0iLCJyZXNvdXJjZSI6IndvcmtzcGFjZXMiLCJzZWN0aW9uX3NoYTI1NiI6ImE4NzU5NTVjOTcxYzYyOTc3MjFkYjExYWI4NWYxMjdiZWQxMzUwYzY2NjNkNDAwYjQ5YzcxOGI3N2M2MmM1ZGQiLCJzaWduYXR1cmVfc2hhMjU2IjoiYjY3M2Q4Njc3Nzc2NjIxNmJlNzQ5Yzg3MDlhYTkwM2MwZWJmYTQzNGRiODdhODFmYzg4MWUwODkyMTJiMmVlYyJ9 -->
### `client.getHostedWorkspaceOperation`

Operation ID: `getHostedWorkspaceOperation`  
Route: `GET` `/v1/workspaces/{workspaceId}/operations/{operationId}`  

#### Signature

```dart
Future<ApiResponse> getHostedWorkspaceOperation(String workspaceId, String operationId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `workspaceId` | `path` | yes | `string&lt;uuid&gt;` |  |
| `operationId` | `path` | yes | `string&lt;uuid&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authorized workspace state or result | none |
| `400` | Invalid bounded request | none |
| `401` | Product session rejected | none |
| `402` | Hub entitlement or atomic quota denied | none |
| `403` | Operation or fleet policy denied | none |
| `404` | Resource not found in the authorized tenant and product environment | none |
| `409` | Idempotency conflict, incompatible state or cleanup unconfirmed | none |
| `503` | Operator provider, template, storage or authority unavailable | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "workspaceId",
      "value": "00000000-0000-0000-7261-284a8b699ebd"
    },
    {
      "in": "path",
      "name": "operationId",
      "value": "00000000-0000-0000-5ba1-19fa55640b6d"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRIb3N0ZWRXb3Jrc3BhY2VPcGVyYXRpb24ifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRIb3N0ZWRXb3Jrc3BhY2VTb3VyY2UiLCJtZXRob2QiOiJHRVQiLCJvcGVyYXRpb25faWQiOiJnZXRIb3N0ZWRXb3Jrc3BhY2VTb3VyY2UiLCJwYXRoIjoiL3YxL3dvcmtzcGFjZXMve3dvcmtzcGFjZUlkfS9zb3VyY2UiLCJyZXNvdXJjZSI6IndvcmtzcGFjZXMiLCJzZWN0aW9uX3NoYTI1NiI6ImU3YWQxZWU4YTVjZjdiNGExZjY3YmVlYjk4MjEwNjIxMWFiZmJlM2NlZmYxMTY4ZmQ5NDYzZjlhNzdjZWQzZjMiLCJzaWduYXR1cmVfc2hhMjU2IjoiNjc5NWVmODU5NjdiNjNlNWI5NTQ0ZmMzNDY2NTJiMzdmMDU2MGY0ZWQ5NTBiYzM5NTIzMjMxMzNmZGNlZDk3ZSJ9 -->
### `client.getHostedWorkspaceSource`

Operation ID: `getHostedWorkspaceSource`  
Route: `GET` `/v1/workspaces/{workspaceId}/source`  

#### Signature

```dart
Future<ApiResponse> getHostedWorkspaceSource(String workspaceId)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `workspaceId` | `path` | yes | `string&lt;uuid&gt;` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authorized workspace state or result | none |
| `400` | Invalid bounded request | none |
| `401` | Product session rejected | none |
| `402` | Hub entitlement or atomic quota denied | none |
| `403` | Operation or fleet policy denied | none |
| `404` | Resource not found in the authorized tenant and product environment | none |
| `409` | Idempotency conflict, incompatible state or cleanup unconfirmed | none |
| `503` | Operator provider, template, storage or authority unavailable | none |

#### Canonical required-input example

```json
{
  "parameters": [
    {
      "in": "path",
      "name": "workspaceId",
      "value": "00000000-0000-0000-43c8-d895a22336ed"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRIb3N0ZWRXb3Jrc3BhY2VTb3VyY2UifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsaXN0SG9zdGVkV29ya3NwYWNlcyIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6Imxpc3RIb3N0ZWRXb3Jrc3BhY2VzIiwicGF0aCI6Ii92MS93b3Jrc3BhY2VzIiwicmVzb3VyY2UiOiJ3b3Jrc3BhY2VzIiwic2VjdGlvbl9zaGEyNTYiOiIwMDdiNTc2YWY4YzQwMTY4MGI3NGEzNjY5ODM3N2RiMTY0YTFjMDE4MmRmNjg0NmM5YjVhN2RkMTBkOTFkMTk4Iiwic2lnbmF0dXJlX3NoYTI1NiI6IjM3MTcxMmJlMTIzMzRhMzkwMzkyNjJjYWNiNjUyOTRmNWRmOGU2NTgxZjEwZmE3YTlmZTYzZjg3NzdlZTA4MzAifQ -->
### `client.listHostedWorkspaces`

Operation ID: `listHostedWorkspaces`  
Route: `GET` `/v1/workspaces`  

#### Signature

```dart
Future<ApiResponse> listHostedWorkspaces()
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authorized workspace state or result | none |
| `400` | Invalid bounded request | none |
| `401` | Product session rejected | none |
| `402` | Hub entitlement or atomic quota denied | none |
| `403` | Operation or fleet policy denied | none |
| `404` | Resource not found in the authorized tenant and product environment | none |
| `409` | Idempotency conflict, incompatible state or cleanup unconfirmed | none |
| `503` | Operator provider, template, storage or authority unavailable | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsaXN0SG9zdGVkV29ya3NwYWNlcyJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJvcGVuSG9zdGVkV29ya3NwYWNlIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6Im9wZW5Ib3N0ZWRXb3Jrc3BhY2UiLCJwYXRoIjoiL3YxL3dvcmtzcGFjZXMiLCJyZXNvdXJjZSI6IndvcmtzcGFjZXMiLCJzZWN0aW9uX3NoYTI1NiI6IjFjYzc2NjY5ZTBkNjgwNGRjODM5NTY1MmVjY2M5NGIzZGUwYjA1MTc5NzhiNDhkYjRmM2FlYjk0ZDRiYjdiNjkiLCJzaWduYXR1cmVfc2hhMjU2IjoiYzVjMGZlMmExZWM1NmJmNWU4YjJkMjMzMDYzYzEwZDdjMzg1ODk5YjU1Y2RlNmQyODczZjg2ZmZlYzY5NDJjNSJ9 -->
### `client.openHostedWorkspace`

Operation ID: `openHostedWorkspace`  
Route: `POST` `/v1/workspaces`  

#### Signature

```dart
Future<ApiResponse> openHostedWorkspace(Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `Idempotency-Key` | `header` | no | `string` | Required here or in the idempotencyKey body field. Replays never allocate or execute again. |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authorized workspace state or result | none |
| `201` | Prepared workspace; source and provider allocation recorded durably | none |
| `400` | Invalid bounded request | none |
| `401` | Product session rejected | none |
| `402` | Hub entitlement or atomic quota denied | none |
| `403` | Operation or fleet policy denied | none |
| `404` | Resource not found in the authorized tenant and product environment | none |
| `409` | Idempotency conflict, incompatible state or cleanup unconfirmed | none |
| `503` | Operator provider, template, storage or authority unavailable | none |

#### Canonical required-input example

```json
{
  "body": {},
  "content_type": "application/json",
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJvcGVuSG9zdGVkV29ya3NwYWNlIn0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJyZWNvdmVySG9zdGVkV29ya3NwYWNlIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InJlY292ZXJIb3N0ZWRXb3Jrc3BhY2UiLCJwYXRoIjoiL3YxL3dvcmtzcGFjZXMve3dvcmtzcGFjZUlkfS9yZWNvdmVyIiwicmVzb3VyY2UiOiJ3b3Jrc3BhY2VzIiwic2VjdGlvbl9zaGEyNTYiOiI2ZDE4ZmM0ZmIzYjkwZDg1N2EwMWNlODczMDc1YzZmNjE4ZDhjZGQ2NGRjMDM4ZmEzODljN2MzN2ZiOWMxOGYyIiwic2lnbmF0dXJlX3NoYTI1NiI6ImZmZGJlYjNkODM0ZTAyMTQwNzViMDU2YjYxZWRkYmZjYTBiYTg4ZTY5ZWIxM2MwMGQxMTJjM2NmMTJkMzc0OWEifQ -->
### `client.recoverHostedWorkspace`

Operation ID: `recoverHostedWorkspace`  
Route: `POST` `/v1/workspaces/{workspaceId}/recover`  

#### Signature

```dart
Future<ApiResponse> recoverHostedWorkspace(String workspaceId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `workspaceId` | `path` | yes | `string&lt;uuid&gt;` |  |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authorized workspace state or result | none |
| `202` | No verified terminal receipt yet; workspace remains unavailable for new commands | none |
| `400` | Invalid bounded request | none |
| `401` | Product session rejected | none |
| `402` | Hub entitlement or atomic quota denied | none |
| `403` | Operation or fleet policy denied | none |
| `404` | Resource not found in the authorized tenant and product environment | none |
| `409` | Idempotency conflict, incompatible state or cleanup unconfirmed | none |
| `503` | Operator provider, template, storage or authority unavailable | none |

#### Canonical required-input example

```json
{
  "body": {
    "operationId": "00000000-0000-0000-d4ac-b0b84827b6d9"
  },
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "workspaceId",
      "value": "00000000-0000-0000-973a-c9ae0260973d"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJyZWNvdmVySG9zdGVkV29ya3NwYWNlIn0 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJydW5Ib3N0ZWRXb3Jrc3BhY2UiLCJtZXRob2QiOiJQT1NUIiwib3BlcmF0aW9uX2lkIjoicnVuSG9zdGVkV29ya3NwYWNlIiwicGF0aCI6Ii92MS93b3Jrc3BhY2VzL3t3b3Jrc3BhY2VJZH0vcnVuIiwicmVzb3VyY2UiOiJ3b3Jrc3BhY2VzIiwic2VjdGlvbl9zaGEyNTYiOiJjYzU4YTg3MGNkMzc0MzAwNWU3NjZiOTk3MjFjZDk2ZDBjMjdlMTNmMTgxMmUxYmQ5YmExYjVlNzMyZGI4ZWZkIiwic2lnbmF0dXJlX3NoYTI1NiI6ImQyMDU0MTczNjdlODczOWJmODU2YmNiMzZlMTkxYjZjNmJhZjU3OWNlMjIzYzQwNjg3ZjY0Y2I0NTNjMzAzZDEifQ -->
### `client.runHostedWorkspace`

Operation ID: `runHostedWorkspace`  
Route: `POST` `/v1/workspaces/{workspaceId}/run`  

#### Signature

```dart
Future<ApiResponse> runHostedWorkspace(String workspaceId, Map<String, dynamic>? body)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| `workspaceId` | `path` | yes | `string&lt;uuid&gt;` |  |
| `Idempotency-Key` | `header` | no | `string` | Required here or in the idempotencyKey body field. Replays never allocate or execute again. |
| `body` | body | yes | `object` |  |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authorized workspace state or result | none |
| `202` | Running or uncertain operation; inspect or explicitly recover, never resend with a new key | none |
| `400` | Invalid bounded request | none |
| `401` | Product session rejected | none |
| `402` | Hub entitlement or atomic quota denied | none |
| `403` | Operation or fleet policy denied | none |
| `404` | Resource not found in the authorized tenant and product environment | none |
| `409` | Idempotency conflict, incompatible state or cleanup unconfirmed | none |
| `503` | Operator provider, template, storage or authority unavailable | none |

#### Canonical required-input example

```json
{
  "body": {
    "command": "example"
  },
  "content_type": "application/json",
  "parameters": [
    {
      "in": "path",
      "name": "workspaceId",
      "value": "00000000-0000-0000-4862-6c003dd1756b"
    }
  ]
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJydW5Ib3N0ZWRXb3Jrc3BhY2UifQ -->

