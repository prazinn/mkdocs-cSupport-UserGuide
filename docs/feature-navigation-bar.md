# Feature Navigation Bar

This is a simple feature that allows you to navigate between different features of the the dashboard. This consists of the following features:

![Feature Navigation Bar](img/feature-navigation-bar.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Feature Navigation Bar</i>
</div>

1. [Dashboard.](#dashboard)
1. [Logs.](#logs)
1. [Wi-Fi.](#wi-fi)
1. [Nettv.](#nettv)
1. [Internet Usage.](#internet-usage)
1. [Ticket History.](#ticket-history)
1. [Followup History.](#followup-history)
1. [Documents.](#documents)

## Dashboard 

This section provides detailed information about the ONU (Optical Network Unit) and the client’s internet connectivity, offering valuable insights into their network setup and performance. Additionally, it includes features such as Mega Boost, Account Diagnostics, and NWCC details to enhance troubleshooting.

!!! note
    This is the default view after entering a username.

### Connectivity Info

This section provides information about the client’s connection status. If the client is connected to the internet, the connectivity details will be displayed in green, highlighting all relevant connectivity information.

<!-- NEED TO CHANGE IMAGE -->
![Connectivity Info Online](img/connectivity-info.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Connectivity Info when the client is connected</i>
</div><br>

![Connectivity Info Online](img/connectivity-info-offline.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Connectivity Info when the client is not connected</i>
</div><br>

### FTTH INFO
This is the section where we can find the information related to the ONU of the client as well as the information regarding ACS and splitters.

![FTTH INFO](img/ftth-info.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. FTTH INFO</i>
</div><br>

Clicking on the `ONU IP` redirects to the ONU login page. The credentials for the ONU can be accessed through ONU credetntials section

![ONU Credentials](img/onu-credentials.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. ONU Credentials</i>
</div><br>

### Network Status
This is the section where we find the total number of users that are connected to the GPON network.
![Network Status](img/network-status.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Network Status</i>
</div><br>

!!! note
    Clicking on the username will open a new tab dedicated to that user, providing quick access to their details and activities.

### ACS Status

This is the section that provides the details regarding the connection status of the ONU with the ACS server.
This information enables the identification of connectivity issues between ONU and ACS, facilitating the debugging of failures in executing ONU-related tasks via myWorldlink app and customer portal.

![ACS Status](img/acs-status.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. ACS Status</i>
</div><br>

## Logs

This section contains two types of logs: `Connection Logs` and `Port History Logs`, providing detailed insights into the device’s connectivity and port usage history.

![Logs List](img/logs-list.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Logs List</i>
</div><br>

### Connection Logs
![Connection Logs Timeline View](img/connection-logs-timeline-view.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Connection Logs Timeline View</i>
</div><br>

![Connection Logs List View](img/connection-logs-listview.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Connection Logs List View</i>
</div><br>

### Port History Logs
![Port History Logs Timeline View](img/port-history-timeline.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Port History Logs Timeline View</i>
</div><br>

![Port History Logs List View](img/port-history-list.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Port History Logs List View</i>
</div><br>
