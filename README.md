# Disallowed Usernames List

This `data.txt` contains a list of 5000+ disallowed usernames to implement in your platforms.

## Usage

You can import this list using jsDelivr for client-side applications:

```
https://cdn.jsdelivr.net/gh/PullChicks/disallowed_usernames@main/data.txt
```

This helps reduce bandwidth issues by using a CDN.

## Platform Username Creation Rules

Consider implementing these additional rules when building username creation systems:

- **Minimum Requirements**: Set username length to more than 4 characters
- **Repeatability**: Reject usernames where the same one or two words repeat without additional variation
- **Character Diversity**: Enable minimum 3 different letters requirement (helps prevent usernames like "XDXXX")
- **Premium Usernames**: Reserve maximum short usernames (even for first users) - these could potentially be sold later, similar to Instagram's approach
