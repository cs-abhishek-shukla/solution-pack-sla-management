# What's New

| Compatible Version         |
|----------------------------|
| FortiSOAR v8.0.0 and later |

- **Response Due Date** and **Response SLA** are now accurately recalculated upon changes in status (e.g., from *Open* → *Investigating* → *Pending* → *Investigating*).

- **Acknowledge SLA** is now correctly set when an alert transitions from *Open* to *Closed*.

- The calculation of **Ack Due Date** and **Ack Date** is now precise when an alert is updated to **Investigating** immediately after its creation.

## Bug Fixes

- Fixed an issue in the step *Set Acknowledge SLA as Missed* where the field *Ack Due Date* was being updated instead of the field *Ack Date*.