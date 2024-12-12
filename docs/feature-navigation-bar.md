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
This information enables the identification of connectivity issues between ONU and ACS, facilitating the debugging of failures in executing ONU-related tasks via myWorldlink app and Customer Portal.

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

## Wi-Fi

### WIFI Details
This section lets you easily view the customer's Wi-Fi details. In the older version, eSupport, we could only see the SSID for the 2.4GHz band. With cSupport, you now get a complete view of both the 2.4GHz and 5GHz bands, including their Wi-Fi and broadcast statuses and the authentication mode. It’s a more detailed and user-friendly way to understand the customer’s issues.

![WIFI Details](img/wifi-details.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. WIFI Details</i>
</div><br>

### Connected Devies
This section displays a list of devices currently connected to the client’s router, whether via Ethernet or Wi-Fi.

![Connected Devices](img/connected-devices-wifi.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Connected Devices Wi-Fi</i>
</div><br>

![Connected Devices Ethernet](img/connected-devices-ethernet.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Connected Devices Ethernet</i>
</div><br>

## NetTv

Under this section, you can check client's NetTv information and logs.

![Nettv](img/nettv.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Nettv</i>
</div><br>

### NetTv Details
This section will provide you with the number of NetTv the client has installed with its MAC address and package information. You can directly `ADD BONUS` and `EXTEND` without having to visit another application.

![Nettv Details](img/nettv-details.png){ style="display: block; margin: auto;" }

<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Nettv Details</i>
</div><br>

- **Extend**
    This feature enables you to extend a client’s package in cases where their current package has expired, ensuring uninterrupted service.

![NetTv Extend](img/nettv-extend.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. NetTv Extend</i>
</div><br> 

- **Add Bonus:**
    The Add Bonus feature resolves cases where a customer's NETTV service is interrupted due to system issues, even though their internet package payment was successfully completed.

![Add Bonus](img/add-bonus.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Add Bonus</i>
</div><br> 

## Internet Usage

The Internet Usage feature makes it easy to track how much data a client has used. You can see details for both uploads and downloads, and use the date filter to check usage during a specific time frame. It’s a simple way to monitor and understand a client’s internet activity, helping you provide better support and service.

![Internet Usage](img/internet-usage.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Internet Usage</i>
</div>
!!! note
    Clicking the arrow button lets you sort the dates to easily find the day with the highest data consumption.

## Ticket History

With the Ticket History feature, you can easily look through past tickets based on the problem type. Simply click on a problem type to view all related tickets. You can also use the date filter to focus on a specific time period by default it shows the data of past 7 days, making it easier to track and spot trends in support requests.

![Ticket Details](img/ticket-history.gif){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Add Bonus</i>
</div><br> 

## Followup History

With this feature, you can easily see all the remarks from previous follow-ups. It gives you a clear record of every interaction.

![Followup History](img/followup-history.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Followup History</i>
</div><br> 

- **View Followup**
    This section allows you to view the remarks from the previous follow-ups.

![View Followup](img/view-followup.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. View Followup</i>
</div><br>

![Followup Remarks](img/followup-remarks.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Followup Remarks</i>
</div><br>

- **Add Followup**
    This section allows you to post remarks after completing a follow-up with the client, ensuring that all interactions are documented for future reference.

![Add Followup](img/add-followup.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Add Followup</i>
</div><br>

![Post Remarks](img/post-remarks.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Post Remarks</i>
</div><br>

## Documents

This section contains all the documents related to the client, including those uploaded during the installation process and any additional documents submitted by the client via the myWorldLink app.

![Documents](img/documents.png){ style="display: block; margin: auto;" }
<div align="center">
<i style="font-size: 14px; color: grey;">Fig. Documents</i>
</div><br>