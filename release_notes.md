# What's New

<table>
    <tr>
        <th>Compatible Version</th>
        <td>FortiSOAR v7.6.0 and later</td>
    </tr>
</table>

- **Response Due Date** and **Response SLA** are now accurately recalculated upon changes in status (e.g., from *Open* → *Investigating* → *Pending* → *Investigating*).
- **Acknowledge SLA** is now correctly set when an alert transitions from *Open* to *Closed*.
- The calculation of **Ack Due Date** and **Ack Date** is now precise when an alert is updated to **Investigating** immediately after its creation.
- Fixed an issue where the **Set Acknowledge SLA as Missed** step incorrectly updated the **Ack Due Date** field instead of the **Ack Date** field