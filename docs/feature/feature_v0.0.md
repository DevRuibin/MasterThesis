# Feature v0.0

## Lexicon

1. Emergency: A circumstance where the user is unable to utilize the application for unlocking purposes, e.g., due to a depleted battery in the user's phone or lock.
2. Share: Enabling another user to control the lock via the application.

## Core Features

### Critical Functionalities:

1. **GPS-Based Remote Access**
Lock/unlock the device from any location using GPS technology, with no distance restrictions.
2. **Bluetooth-Enabled Locking/Unlocking**
Operate the lock within a specific range using Bluetooth connectivity.
3. **Manual Key Usage**
Unlock/lock the device using a physical key, primarily intended for emergency situations.
4. **Locational Tracking of the Lock**
Monitor the lock's position remotely, leveraging LoRaWAN technology for unlimited distance capabilities.

### Additional Functionalities:
1. **User Lock Sharing**
Permit the sharing of lock control with other users via the application.
2. **NFC and Fingerprint Unlocking**
Unlock/lock the device using NFC technology or biometric fingerprint recognition.

## User Scenarios

### Scenario 1: Standard Locking/Unlocking
**Objective**: The user seeks to secure or access a locked area.

**Process**:Employ the application or physical key for locking/unlocking purposes.

### Scenario 2: Managing Power Outages
**Objective**: Ensure accessibility in case of an electricity failure or drained device battery.

**Process**:Utilize a manual key to operate the lock during power discrepancies.

### Scenario 3: Sharing Access to the Lock

**Objective**: Delegate lock control to other individuals.

**Process**:
Employ the application to distribute access rights to distinct user types:
_Owner_: Retains comprehensive control, including lock/unlock capabilities and sharing access.
_Shared User_: Limited to lock/unlock capabilities.
_Visitor_: Conferred a temporary token for a singular lock/unlock action.

### Scenario 4: Tracking the Lock's Location

**Objective**: The user desires to determine the current geographical location of the lock.

**Process**:The application displays the lock's precise coordinates or its position on a map, offering the user real-time tracking capabilities. Optionally, the user may view a history of the lock’s locations over a predefined time period.