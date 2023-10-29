# Feature v0.0

## summary

A market for sharing things.

Owners can list their items for rent on the market. Anyone can access the item by paying the owner and then unlocking it via Bluetooth. Owners can track the location of their rented items. The item should be returned to the specified location at the end of the rental period.

## Lexicon

1. Emergency: A circumstance where the user is unable to utilize the application for unlocking purposes, e.g., due to a depleted battery in the user's phone or lock.
2. Share: Enabling another user to control the lock via the application.

## Core Features

### Critical Functionalities:

1. **GPS-Based Tracking**
   The owner and the tenant can know the location of the place.

2. **Bluetooth-Enabled Locking/Unlocking**
   Operate the lock within a specific range using Bluetooth connectivity.

3. **Manual Key Usage**
   Unlock/lock the device using a physical key, primarily intended for emergency situations.

4. **Power monitor**

   The owner should know the lock's battery life.

## User Scenarios

### Scenario 1: Standard Locking/Unlocking

**Objective**: The user seeks to secure or access a locked area.

**Process**: Employ the application or physical key for locking/unlocking purposes.

### Scenario 2: Managing Power Outages

**Objective**: Ensure accessibility in case of an electricity failure or drained device battery.

**Process**: Utilize a manual key to operate the lock during power discrepancies.

### Scenario 3: Sharing Access to the Lock

**Objective**: Delegate lock control to other individuals.

**Process**: 
:dancer:==At the start, the lock generates an encrypted token and forwards it to the server through LoRnWAN. The server can then allocate it to a paid user who can use the token to unlock the lock. After the token is utilized, the lock generates a new one while the old one becomes invalid. The user must ensure that the property is placed in a specified location, otherwise, the lock won't work. The cost of usage will be calculated based on the duration of usage.==:dancer:

### Scenario 4: Tracking the Lock's Location

**Objective**: The user desires to determine the current geographical location of the lock.

**Process**: The application displays the lock's precise coordinates or position on a map, offering the user real-time tracking capabilities. Optionally, the user may view a history of the lock’s locations over a predefined period.