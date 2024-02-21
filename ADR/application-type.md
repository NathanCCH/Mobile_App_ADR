
# Application Type

## Status
Proposed

## Context
The mobile app needs to provide real-time location updates, a map interface, and secure payment transactions. The type of app we choose will impact these features.

## Decision
We propose to develop a native app. Native apps provide better performance, a more consistent look and feel with the device's ecosystem, and access to all device APIs including geolocation, which is crucial for our app.

## Consequences
Choosing a native app means we'll need to develop and maintain separate codebases if we want to support both iOS and Android. However, the improved performance and access to native device features can provide a better user experience.
