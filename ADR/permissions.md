
## Status
Proposed

## Context
The mobile app requires certain permissions from the user to function properly, such as location services for ride tracking and camera access for profile picture updates.

## Decision
We propose to request permissions from the user only when necessary, explaining clearly why each permission is needed. We will also handle denial of permissions gracefully, ensuring the app remains functional where possible.

## Consequences
This approach respects user privacy and gives them control over what data they share. However, it may require additional development effort to handle different permission states.