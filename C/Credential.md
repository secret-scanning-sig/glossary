# Credential

An item or piece of information used to identify, authenticate, and/or provide
access for a principal (e.g. user or service account). A credential is often a
type of [secret](../S/Secret.md) given that credentials are often sensitive
information.

## Examples

- Username and Password
- SSH Private Key
- Government Issued ID (e.g. Driver's License or Passport)
- API Token

## When a credential is not a secret

A credential is not a secret if it poses ABSOLUTELY NO risk upon exposure. For
instance, credentials for an ephemeral test database would not be secrets,
provided the database is local-only, holds no sensitive information, is never
exposed to a network, is torn down after tests complete, etc...

**But the sensitivity of a credential is easy to misjudge!** In practice treat
all credentials as secrets and protect them properly.
