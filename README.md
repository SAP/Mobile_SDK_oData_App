CRMODataApp
===========
This application is showcasing the usage of the SAP Mobile Platform SDK for iOS. 
You can get the SMP SDK v. 3.0.10 for iOS here: http://help.sap.com/smp3010sdk

The following Mobile SDK frameworks are used:
- ODataAPI
- OData Online
- OData Offline
- HTTPConversation
- MAFLogonManager
- Supportability (for logging and tracing)
- further libraries required due to dependencies

Three different modes are supported:
- Online (default)
- Offline (relies on the OData offline store)
- Demo mode

When used in online mode, one can edit, create or delete entities*.

(*)The endpoint URL and app ID must be filled in in order for the app to work. 
This can be done within Settings -> SAPCRMOData (see screenshot). Also, a valid user name and a password is required - except for demo mode.

![App Settings](https://github.com/SAP/Mobile_SDK_oData_App/blob/screenshots/Screenshots/settings.png)

The Login UI:
![The Login UI](https://github.com/SAP/Mobile_SDK_oData_App/blob/screenshots/Screenshots/login.png)

The App's Main UI:
![The App's Main UI](https://github.com/SAP/Mobile_SDK_oData_App/blob/screenshots/Screenshots/appointments.png)

Built-In Log Viewer:
![Built-In Log Viewer](https://github.com/SAP/Mobile_SDK_oData_App/blob/screenshots/Screenshots/logviewer.png)

In-App Settings:
![In-App Settings](https://github.com/SAP/Mobile_SDK_oData_App/blob/screenshots/Screenshots/inappsettings.png)


