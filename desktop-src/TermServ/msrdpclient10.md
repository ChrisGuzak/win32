---
title: MsRdpClient10 class
description: Microsoft RDP Client Control (redistributable) - version 11.
ms.assetid: 9D0F2312-0D85-402D-874D-9FA477435210
ms.tgt_platform: multiple
keywords:
- MsRdpClient10 class Remote Desktop Services
- MsRdpClient10 class Remote Desktop Services , described
topic_type:
- apiref
api_name:
- MsRdpClient10
api_location:
- MsTscAx.dll
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# MsRdpClient10 class

Microsoft RDP Client Control (redistributable) - version 11

This class implements the following interfaces.

-   [**IMsRdpClient10**](imsrdpclient10.md)
-   [**IMsRdpClient9**](imsrdpclient9.md)
-   [**IMsRdpClient8**](imsrdpclient8.md)
-   [**IMsRdpClient7**](imsrdpclient7.md)
-   [**IMsRdpClient6**](imsrdpclient6.md)
-   [**IMsRdpClient5**](imsrdpclient5.md)
-   [**IMsRdpClient4**](imsrdpclient4.md)
-   [**IMsRdpClient3**](imsrdpclient3.md)
-   [**IMsRdpClient2**](imsrdpclient2.md)
-   [**IMsRdpClient**](imsrdpclientshell2.md)
-   [**IMsTscAx**](imstscax-interface.md)
-   [**IDispatch**](/windows/win32/api/oaidl/nn-oaidl-idispatch)
-   [**IMsTscAxEvents**](imstscaxevents-interface.md)
-   [**IMsTscNonScriptable**](imstscnonscriptable-interface.md)
-   [**IMsRdpClientNonScriptable**](imsrdpclientnonscriptable-interface.md)
-   [**IMsRdpClientNonScriptable2**](imsrdpclientnonscriptable2.md)
-   [**IMsRdpClientNonScriptable3**](imsrdpclientnonscriptable3.md)
-   [**IMsRdpClientNonScriptable4**](imsrdpclientnonscriptable4.md)
-   [**IMsRdpClientNonScriptable5**](imsrdpclientnonscriptable5.md)
-   [**IMsRdpPreferredRedirectionInfo**](imsrdppreferredredirectioninfo.md)

**MsRdpClient10** has these types of members:

-   [Methods](#methods)
-   [Properties](#properties)

### Methods

The **MsRdpClient10** class has these methods.



| Method                                                                                      | Description                                                                                                                                                                                                                                                                                   |
|:--------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**attachEvent**](imsrdpclient9-attachevent.md)                                            | Attaches an event. <br/>                                                                                                                                                                                                                                                                |
| [**Connect**](imstscax-connect.md)                                                         | Initiates a connection using the properties currently set on the control.<br/>                                                                                                                                                                                                          |
| [**CreateVirtualChannels**](imstscax-createvirtualchannels.md)                             | Creates a client-side virtual channel object for each specified virtual channel name.<br/>                                                                                                                                                                                              |
| [**detachEvent**](imsrdpclient9-detachevent.md)                                            | Detaches an event. <br/>                                                                                                                                                                                                                                                                |
| [**Disconnect**](imstscax-disconnect.md)                                                   | Disconnects the active connection.<br/>                                                                                                                                                                                                                                                 |
| [**GetErrorDescription**](imsrdpclient5-geterrordescription.md)                            | Retrieves the error codes and error messages.<br/>                                                                                                                                                                                                                                      |
| [**GetStatusText**](imsrdpclient7-getstatustext.md)                                        | Retrieves the status text for the specified status code.<br/>                                                                                                                                                                                                                           |
| [**GetVirtualChannelOptions**](imsrdpclient-getvirtualchanneloptions.md)                   | Retrieves the options set for a virtual channel.<br/>                                                                                                                                                                                                                                   |
| [**NotifyRedirectDeviceChange**](imsrdpclientnonscriptable-notifyredirectdevicechange.md)  | Notifies the device redirection module of the Remote Desktop ActiveX control that a device change has occurred on the system. This method passes [**WM\_DEVICECHANGE**](/windows/desktop/DevIO/wm-devicechange) notifications to the control.<br/>                                                        |
| [**OnAuthenticationWarningDismissed**](imstscaxevents-onauthenticationwarningdismissed.md) | Called after an ActiveX control displays an authentication dialog box (for example, the certificate error dialog box).<br/>                                                                                                                                                             |
| [**OnAuthenticationWarningDisplayed**](imstscaxevents-onauthenticationwarningdisplayed.md) | Called before an ActiveX control displays an authentication dialog box (for example, the certificate error dialog box).<br/>                                                                                                                                                            |
| [**OnAutoReconnected**](imstscaxevents-onautoreconnected.md)                               | Called when the client control has automatically reconnected to a remote session.<br/>                                                                                                                                                                                                  |
| [**OnAutoReconnecting**](-imstscaxevents--onautoreconnecting.md)                           | Called when a client is in the process of automatically reconnecting a session with a RD Session Host server.<br/>                                                                                                                                                                      |
| [**OnAutoReconnecting2**](imstscaxevents-onautoreconnecting2.md)                           | Called when a client is in the process of automatically reconnecting a session with a RD Session Host server.<br/>                                                                                                                                                                      |
| [**OnChannelReceivedData**](imstscaxevents-onchannelreceiveddata.md)                       | Called when the client receives data on a scriptable virtual channel.<br/>                                                                                                                                                                                                              |
| [**OnConfirmClose**](imstscaxevents-onconfirmclose.md)                                     | Called when the client calls the [**IMsRdpClient::RequestClose**](imsrdpclient-requestclose.md) method.<br/>                                                                                                                                                                           |
| [**OnConnected**](imstscaxevents-onconnected.md)                                           | Called when the client control is in the process of establishing a connection with a RD Session Host server.<br/>                                                                                                                                                                       |
| [**OnConnecting**](imstscaxevents-onconnecting.md)                                         | Called when the client control begins connecting to a server in response to a call to [**IMsTscAx::Connect**](imstscax-connect.md).<br/>                                                                                                                                               |
| [**OnConnectionBarPullDown**](imstscaxevents-onconnectionbarpulldown.md)                   | Called when the user has dragged down on the connection bar.<br/>                                                                                                                                                                                                                       |
| [**OnDevicesButtonPressed**](imstscaxevents-ondevicesbuttonpressed.md)                     | Called when the devices button in the connection bar has been pressed.<br/>                                                                                                                                                                                                             |
| [**OnDisconnected**](imstscaxevents-ondisconnected.md)                                     | Called when the client control has been disconnected from the RD Session Host server.<br/>                                                                                                                                                                                              |
| [**OnEnterFullScreenMode**](imstscaxevents-onenterfullscreenmode.md)                       | Called when the client enters full-screen mode. For example, this event is called when the user presses the full-screen mode [shortcut key](terminal-services-shortcut-keys.md) combination (CTRL+ALT+BREAK).<br/>                                                                     |
| [**OnFatalError**](imstscaxevents-onfatalerror.md)                                         | Called when the client control encounters a fatal error.<br/>                                                                                                                                                                                                                           |
| [**OnFocusReleased**](imstscaxevents-onfocusreleased.md)                                   | Called when the release focus key combination is pressed. For example, this event is called when the user presses the CTRL+ALT+LEFT ARROW or the CTRL+ALT+RIGHT ARROW key combination.<br/>                                                                                             |
| [**OnIdleTimeoutNotification**](imstscaxevents-onidletimeoutnotification.md)               | Called when there has been no mouse or keyboard input by the user during the period of time set by the [**IMsRdpClientAdvancedSettings::put\_MinutesToIdleTimeout**](imsrdpclientadvancedsettings-minutestoidletimeout.md) method.<br/>                                                |
| [**OnLeaveFullScreenMode**](imstscaxevents-onleavefullscreenmode.md)                       | Called when the client leaves full-screen mode. For example, this event is called when the user presses the full-screen mode [shortcut key](terminal-services-shortcut-keys.md) combination (CTRL+ALT+BREAK).<br/>                                                                     |
| [**OnLoginComplete**](imstscaxevents-onlogincomplete.md)                                   | Called when the client control has successfully logged on to a RD Session Host server, following the display of the Windows Logon dialog box.<br/>                                                                                                                                      |
| [**OnLogonError**](imstscaxevents-onlogonerror.md)                                         | Called when a logon error or other logon event occurs.<br/>                                                                                                                                                                                                                             |
| [**OnMouseInputModeChanged**](imstscaxevents-onmouseinputmodechanged.md)                   | Called when the mouse input mode has changed.<br/>                                                                                                                                                                                                                                      |
| [**OnNetworkStatusChanged**](imstscaxevents-onnetworkstatuschanged.md)                     | Called when the network status has changed.<br/>                                                                                                                                                                                                                                        |
| [**OnReceivedTSPublicKey**](imstscaxevents-onreceivedtspublickey.md)                       | Called during the connection sequence when the client retrieves the public key from the server. This event is only called if the **NotifyTSPublicKey** property is **VARIANT\_TRUE**.<br/>                                                                                              |
| [**OnRemoteDesktopSizeChange**](imstscaxevents-onremotedesktopsizechange.md)               | Called to indicate that the size of the client control on the remote desktop has changed in response to a client control operation.<br/>                                                                                                                                                |
| [**OnRemoteProgramDisplayed**](imstscaxevents-onremoteprogramdisplayed.md)                 | Called when a RemoteApp program is displayed.<br/>                                                                                                                                                                                                                                      |
| [**OnRemoteProgramResult**](imstscaxevents-onremoteprogramresult.md)                       | Called when a RemoteApp program returns a result to the client control.<br/>                                                                                                                                                                                                            |
| [**OnRemoteWindowDisplayed**](imstscaxevents-onremotewindowdisplayed.md)                   | Called when a RemoteApp window is displayed.<br/>                                                                                                                                                                                                                                       |
| [**OnRequestContainerMinimize**](imstscaxevents-onrequestcontainerminimize.md)             | Called when the user presses the **Minimize** button on the connection bar in full-screen mode. The firing of this event is a request that the container application minimize itself.<br/>                                                                                              |
| [**OnRequestGoFullScreen**](imstscaxevents-onrequestgofullscreen.md)                       | Called when the client requests to switch to full-screen mode and the [**IMsTscAdvancedSettings::put\_ContainerHandledFullScreen**](imstscadvancedsettings-containerhandledfullscreen.md) method is called to set the **ContainerHandledFullScreen** property to a nonzero value.<br/> |
| [**OnRequestLeaveFullScreen**](imstscaxevents-onrequestleavefullscreen.md)                 | Called when the client requests to leave full-screen mode and the [**IMsTscAdvancedSettings::put\_ContainerHandledFullScreen**](imstscadvancedsettings-containerhandledfullscreen.md) property has been set to a nonzero value.<br/>                                                   |
| [**OnServiceMessageReceived**](imstscaxevents-onservicemessagereceived.md)                 | Called when the client receives a system message.<br/>                                                                                                                                                                                                                                  |
| [**OnUserNameAcquired**](imstscaxevents-onusernameacquired.md)                             | Called when the user name has been acquired by the control.<br/>                                                                                                                                                                                                                        |
| [**OnWarning**](imstscaxevents-onwarning.md)                                               | Called when the client control encounters an error condition that is not fatal.<br/>                                                                                                                                                                                                    |
| [**Reconnect**](imsrdpclient8-reconnect.md)                                                | Reconnects to the remote session with the new desktop width and height.<br/>                                                                                                                                                                                                            |
| [**RequestClose**](imsrdpclient-requestclose.md)                                           | Requests a graceful shutdown of the client control.<br/>                                                                                                                                                                                                                                |
| [**ResetPassword**](imstscnonscriptable-resetpassword.md)                                  | Resets all password states in the control.<br/>                                                                                                                                                                                                                                         |
| [**SendKeys**](imsrdpclientnonscriptable-sendkeys.md)                                      | Sends a series of keystrokes to the control. The keystrokes are in scan code form, which is the keyboard data from the actual physical keys.<br/>                                                                                                                                       |
| [**SendOnVirtualChannel**](imstscax-sendonvirtualchannel.md)                               | Sends data to the RD Session Host server over a virtual channel that was created previously by using the [**IMsTscAx::CreateVirtualChannels**](imstscax-createvirtualchannels.md) method.<br/>                                                                                         |
| [**SendRemoteAction**](imsrdpclient8-sendremoteaction.md)                                  | Causes an action to be performed in the remote session.<br/>                                                                                                                                                                                                                            |
| [**SetVirtualChannelOptions**](imsrdpclient-setvirtualchanneloptions.md)                   | Sets the virtual channel options for the client control.<br/>                                                                                                                                                                                                                           |
| [**SyncSessionDisplaySettings**](imsrdpclient9-syncsessiondisplaysettings.md)              | Synchronizes session display settings. <br/>                                                                                                                                                                                                                                            |
| [**UpdateSessionDisplaySettings**](/previous-versions/windows/desktop/legacy/mt703457(v=vs.85))          | Updates session display settings. <br/>                                                                                                                                                                                                                                                 |



 

### Properties

The **MsRdpClient10** class has these properties.




| Property | Access type | Description | 
|----------|-------------|-------------|
| <a href="imstscax-advancedsettings.md"><strong>AdvancedSettings</strong></a><br /> | Read-only<br /> | An <a href="imstscadvancedsettings-interface.md"><strong>IMsTscAdvancedSettings</strong></a> interface pointer.<br /> | 
| <a href="imsrdpclient-advancedsettings2.md"><strong>AdvancedSettings2</strong></a><br /> | Read-only<br /> | Pointer to the <a href="imsrdpclientadvancedsettings-interface.md"><strong>IMsRdpClientAdvancedSettings</strong></a> interface, used to set advanced settings for the client control.<br /> | 
| <a href="imsrdpclient2-advancedsettings3.md"><strong>AdvancedSettings3</strong></a><br /> | Read-only<br /> | Pointer to the <a href="imsrdpclientadvancedsettings2.md"><strong>IMsRdpClientAdvancedSettings2</strong></a> interface, used to set advanced settings for the client control.<br /> | 
| <a href="imsrdpclient3-advancedsettings4.md"><strong>AdvancedSettings4</strong></a><br /> | Read-only<br /> | Pointer to the <a href="imsrdpclientadvancedsettings3.md"><strong>IMsRdpClientAdvancedSettings3</strong></a> interface, used to set advanced settings for the client control.<br /> | 
| <a href="imsrdpclient4-advancedsettings5.md"><strong>AdvancedSettings5</strong></a><br /> | Read-only<br /> | An <a href="imsrdpclientadvancedsettings4.md"><strong>IMsRdpClientAdvancedSettings4</strong></a> interface pointer.<br /> | 
| <a href="imsrdpclient5-advancedsettings6.md"><strong>AdvancedSettings6</strong></a><br /> | Read-only<br /> | The interface to <a href="imsrdpclientadvancedsettings5.md"><strong>IMsRdpClientAdvancedSettings5</strong></a>.<br /> | 
| <a href="imsrdpclient6-advancedsettings7.md"><strong>AdvancedSettings7</strong></a><br /> | Read-only<br /> | The interface to <a href="imsrdpclientadvancedsettings6.md"><strong>IMsRdpClientAdvancedSettings6</strong></a>.<br /> | 
| <a href="imsrdpclient7-advancedsettings8.md"><strong>AdvancedSettings8</strong></a><br /> | Read-only<br /> | An object that supports the <a href="imsrdpclientadvancedsettings7.md"><strong>IMsRdpClientAdvancedSettings7</strong></a> interface.<br /> | 
| <a href="imsrdpclient8-advancedsettings9.md"><strong>AdvancedSettings9</strong></a><br /> | Read-only<br /> | An <a href="imsrdpclientadvancedsettings8.md"><strong>IMsRdpClientAdvancedSettings8</strong></a> interface that represents the settings object.<br /> | 
| <a href="imsrdpclientnonscriptable4-allowcredentialsaving.md"><strong>AllowCredentialSaving</strong></a><br /> | Read/write<br /> | Specifies whether the credentials dialog box displays a check box to enable the saving of credentials.<br /> | 
| <a href="imsrdpclientnonscriptable5-allowpromptingforcredentials.md"><strong>AllowPromptingForCredentials</strong></a><br /> | Read/write<br /> | Specifies whether the Remote Desktop ActiveX control can prompt the user for credentials.<br /> | 
| <a href="imstscnonscriptable-binarypassword.md"><strong>BinaryPassword</strong></a><br /> | Read/write<br /> | This property is not supported.<br /> | 
| <a href="imstscnonscriptable-binarysalt.md"><strong>BinarySalt</strong></a><br /> | Read/write<br /> | This property is not supported.<br /> | 
| <a href="imstscax-cipherstrength.md"><strong>CipherStrength</strong></a><br /> | Read-only<br /> | The maximum encryption strength of the current control.<br /> | 
| <a href="imstscnonscriptable-cleartextpassword.md"><strong>ClearTextPassword</strong></a><br /> | Write-only<br /> | The Remote Desktop ActiveX control password, in plaintext format.<br /> | 
| <a href="imsrdpclient-colordepth.md"><strong>ColorDepth</strong></a><br /> | Read/write<br /> | Color depth of the current control.<br /> | 
| <a href="imstscax-connected.md"><strong>Connected</strong></a><br /> | Read-only<br /> | The connection state of the current control.<br /> | 
| <a href="imsrdpclient2-connectedstatustext.md"><strong>ConnectedStatusText</strong></a><br /> | Read/write<br /> | Text that is displayed in the client area of the control while the control is in the connected state.<br /> | 
| <a href="imstscax-connectingtext.md"><strong>ConnectingText</strong></a><br /> | Read/write<br /> | The text that appears centered in the control while the control is connecting.<br /> | 
| <a href="imsrdpclientnonscriptable3-connectionbartext.md"><strong>ConnectionBarText</strong></a><br /> | Read/write<br /> | The text string to display for the connection bar.<br /> | 
| <a href="imstscax-desktopheight.md"><strong>DesktopHeight</strong></a><br /> | Read/write<br /> | The current control's height, in pixels, on the initial remote desktop.<br /> | 
| <a href="imstscax-desktopwidth.md"><strong>DesktopWidth</strong></a><br /> | Read/write<br /> | The current control's width, in pixels, on the initial remote desktop.<br /> | 
| <a href="imsrdpclientnonscriptable3-devicecollection.md"><strong>DeviceCollection</strong></a><br /> | Read-only<br /> | The collection of PnP devices that are available for redirection.<br /> | 
| <a href="imsrdpclientnonscriptable5-disableconnectionbar.md"><strong>DisableConnectionBar</strong></a><br /> | Write-only<br /> | Specifies whether the Remote Desktop ActiveX control should disable the connection bar.<br /> | 
| <a href="imsrdpclientnonscriptable5-disableremoteappcapscheck.md"><strong>DisableRemoteAppCapsCheck</strong></a><br /> | Read/write<br /> | Specifies whether the Remote Desktop ActiveX control should not check the server for RemoteApp capabilities.<br /> | 
| <a href="imstscax-disconnectedtext.md"><strong>DisconnectedText</strong></a><br /> | Read/write<br /> | The text that appears centered in the control before a connection is terminated.<br /> | 
| <a href="imstscax-domain.md"><strong>Domain</strong></a><br /> | Read/write<br /> | The domain to which the current user logs on.<br /> | 
| <a href="imsrdpclientnonscriptable3-drivecollection.md"><strong>DriveCollection</strong></a><br /> | Read-only<br /> | The collection of disk drives that is available for redirection.<br /> | 
| <a href="imsrdpclientnonscriptable3-enablecredsspsupport.md"><strong>EnableCredSspSupport</strong></a><br /> | Read/write<br /> | Specifies whether CredSSP is enabled for this connection.<br /> | 
| <a href="imsrdpclient-extendeddisconnectreason.md"><strong>ExtendedDisconnectReason</strong></a><br /> | Read-only<br /> | Extended information about the client control's reason for disconnection.<br /> | 
| <a href="imsrdpclient-fullscreen.md"><strong>FullScreen</strong></a><br /> | Read/write<br /> | Indicates whether the control is in full-screen mode.<br /> | 
| <a href="imstscax-fullscreentitle.md"><strong>FullScreenTitle</strong></a><br /> | Write-only<br /> | The window title displayed when the control is in full-screen mode.<br /> | 
| <a href="imsrdpclientnonscriptable5-getremotemonitorsboundingbox.md"><strong>GetRemoteMonitorsBoundingBox</strong></a><br /> | Read-only<br /> | Specifies the bounding rectangle of the remote monitor.<br /> | 
| <a href="imstscax-horizontalscrollbarvisible.md"><strong>HorizontalScrollBarVisible</strong></a><br /> | Read-only<br /> | Indicates whether the control has displayed a horizontal scroll bar.<br /> | 
| <a href="imsrdpclientnonscriptable4-launchedviaclientshellinterface.md"><strong>LaunchedViaClientShellInterface</strong></a><br /> | Read/write<br /> | Specifies whether the user launched the client control by using the RD Web Access interface.<br /> | 
| <a href="imsrdpclientnonscriptable4-markrdpsettingssecure.md"><strong>MarkRdpSettingsSecure</strong></a><br /> | Read/write<br /> | Specifies whether RDP settings are marked as secure.<br /> | 
| <a href="imsrdpclient5-msrdpclientshell.md"><strong>MsRdpClientShell</strong></a><br /> | Read-only<br /> | The client settings for the web portal launcher.<br /> | 
| <a href="imsrdpclientnonscriptable3-negotiatesecuritylayer.md"><strong>NegotiateSecurityLayer</strong></a><br /> | Read/write<br /> | Specifies whether the NegotiateSecurityLayer setting is supported for this connection.<br /><blockquote>[!Note]<br />When <a href="imsrdpclientnonscriptable3-enablecredsspsupport.md"><strong>CredSspSupport</strong></a> is enabled and present on the client, or when Secure Sockets Layer (SSL) is enabled with user authentication, NegotiateSecurityLayer is ignored.</blockquote><br /> | 
| <a href="imstscnonscriptable-portablepassword.md"><strong>PortablePassword</strong></a><br /> | Read/write<br /> | This property is not supported.<br /> | 
| <a href="imstscnonscriptable-portablesalt.md"><strong>PortableSalt</strong></a><br /> | Read/write<br /> | This property is not supported.<br /> | 
| <a href="imsrdpclientnonscriptable3-promptforcredentials.md"><strong>PromptForCredentials</strong></a><br /> | Read/write<br /> | Specifies whether the prompt for credentials dialog box should be shown.<br /> | 
| <a href="imsrdpclientnonscriptable4-promptforcredsonclient.md"><strong>PromptForCredsOnClient</strong></a><br /> | Read/write<br /> | Specifies whether the client control displays a dialog box that prompts for credentials.<br /> | 
| <a href="imsrdpclientnonscriptable4-publishercertificatechain.md"><strong>PublisherCertificateChain</strong></a><br /> | Read/write<br /> | Specifies the publisher certificate chain. The chain is stored in a variant of type VT_BYREF that contains a pointer to a <a href="/windows/desktop/api/wincrypt/ns-wincrypt-cert_chain_context"><strong>CERT_CHAIN_CONTEXT</strong></a> structure.<br /> | 
| <a href="imsrdpclientnonscriptable3-redirectdynamicdevices.md"><strong>RedirectDynamicDevices</strong></a><br /> | Read/write<br /> | Specifies whether dynamically attached PnP devices that are enumerated while in a session are available for redirection.<br /> | 
| <a href="imsrdpclientnonscriptable3-redirectdynamicdrives.md"><strong>RedirectDynamicDrives</strong></a><br /> | Read/write<br /> | Specifies whether dynamically attached PnP drives that are enumerated while in a session are available for redirection.<br /> | 
| <a href="imsrdpclientnonscriptable4-redirectionwarningtype.md"><strong>RedirectionWarningType</strong></a><br /> | Read/write<br /> | Controls the presence and appearance of the redirection dialog box.<br /> | 
| <a href="imsrdpclientnonscriptable5-remotemonitorcount.md"><strong>RemoteMonitorCount</strong></a><br /> | Read-only<br /> | Specifies the number of remote monitors.<br /> | 
| <a href="imsrdpclientnonscriptable5-remotemonitorlayoutmatcheslocal.md"><strong>RemoteMonitorLayoutMatchesLocal</strong></a><br /> | Read-only<br /> | Specifies if the remote monitor layout is identical to the local monitor layout.<br /> | 
| <a href="imsrdpclient5-remoteprogram.md"><strong>RemoteProgram</strong></a><br /> | Read-only<br /> | The client RemoteApp setting.<br /> | 
| <a href="imsrdpclient7-remoteprogram2.md"><strong>RemoteProgram2</strong></a><br /> | Read-only<br /> | An object that supports the <a href="itsremoteprogram2.md"><strong>ITSRemoteProgram2</strong></a> interface.<br /> | 
| <a href="imsrdpclient10-remoteprogram3.md"><strong>RemoteProgram3</strong></a><br /> | Read-only<br /> | An object that supports the <a href="itsremoteprogram3.md"><strong>ITSRemoteProgram3</strong></a> interface.<br /> | 
| <a href="imstscax-securedsettings.md"><strong>SecuredSettings</strong></a><br /> | Read-only<br /> | A <a href="imstscsecuredsettings-interface.md"><strong>IMsTscSecuredSettings</strong></a> interface pointer.<br /> | 
| <a href="imsrdpclient-securedsettings2.md"><strong>SecuredSettings2</strong></a><br /> | Read-only<br /> | Pointer to the <a href="imsrdpclientsecuredsettings-interface.md"><strong>IMsRdpClientSecuredSettings</strong></a> interface, used to set secured settings for the client control.<br /> | 
| <a href="imsrdpclient7-securedsettings3.md"><strong>SecuredSettings3</strong></a><br /> | Read-only<br /> | An object that supports the <a href="imsrdpclientsecuredsettings2.md"><strong>IMsRdpClientSecuredSettings2</strong></a> interface.<br /> | 
| <a href="imstscax-securedsettingsenabled.md"><strong>SecuredSettingsEnabled</strong></a><br /> | Read-only<br /> | Indicates whether the <a href="imstscsecuredsettings-interface.md"><strong>IMsTscSecuredSettings</strong></a> interface is available.<br /> | 
| <a href="imstscax-server.md"><strong>Server</strong></a><br /> | Read/write<br /> | The name of the server to which the current control is connected.<br /> | 
| <a href="imsrdpclientnonscriptable3-showredirectionwarningdialog.md"><strong>ShowRedirectionWarningDialog</strong></a><br /> | Read/write<br /> | Specifies whether the redirection security warning dialog box should be shown before starting a session.<br /> | 
| <a href="imstscax-startconnected.md"><strong>StartConnected</strong></a><br /> | Read/write<br /> | Indicates whether the control will establish the RD Session Host server connection immediately upon startup.<br /> | 
| <a href="imsrdpclient5-transportsettings.md"><strong>TransportSettings</strong></a><br /> | Read-only<br /> | The client RD Gateway setting.<br /> | 
| <a href="imsrdpclient6-transportsettings2.md"><strong>TransportSettings2</strong></a><br /> | Read-only<br /> | The interface to <a href="imsrdpclienttransportsettings2.md"><strong>IMsRdpClientTransportSettings2</strong></a>.<br /> | 
| <a href="imsrdpclient7-transportsettings3.md"><strong>TransportSettings3</strong></a><br /> | Read-only<br /> | An object that supports the <a href="imsrdpclienttransportsettings3.md"><strong>IMsRdpClientTransportSettings3</strong></a> interface.<br /> | 
| <a href="imsrdpclient9-transportsettings4.md"><strong>TransportSettings4</strong></a><br /> | Read-only<br /> | An object that supports the <a href="imsrdpclienttransportsettings4.md"><strong>IMsRdpClientTransportSettings4</strong></a> interface.<br /> | 
| <a href="imsrdpclientnonscriptable4-trustedzonesite.md"><strong>TrustedZoneSite</strong></a><br /> | Read/write<br /> | Specifies whether the website from which the user launched the connection is in the trusted sites list of the client computer.<br /> | 
| <a href="imsrdpclientnonscriptable2-uiparentwindowhandle.md"><strong>UIParentWindowHandle</strong></a><br /> | Read/write<br /> | The window handle to be the parent window for the control. This allows any windows displayed by the control to be properly modal with respect to any windows displayed by the parent application.<br /> | 
| <a href="imsrdpclientnonscriptable5-usemultimon.md"><strong>UseMultimon</strong></a><br /> | Read/write<br /> | Specifies whether the Remote Desktop ActiveX control should use multiple monitors.<br /> | 
| <a href="imsrdppreferredredirectioninfo-useredirectionservername.md"><strong>UseRedirectionServerName</strong></a><br /> | Read/write<br /> | Whether to use the redirection server name.<br /> | 
| <a href="imstscax-username.md"><strong>UserName</strong></a><br /> | Read/write<br /> | The user name logon credential.<br /> | 
| <a href="imstscax-version.md"><strong>Version</strong></a><br /> | Read-only<br /> | The version number of the current control.<br /> | 
| <a href="imstscax-verticalscrollbarvisible.md"><strong>VerticalScrollBarVisible</strong></a><br /> | Read-only<br /> | Indicates whether the control displays a vertical scroll bar.<br /> | 
| <a href="imsrdpclientnonscriptable3-warnaboutclipboardredirection.md"><strong>WarnAboutClipboardRedirection</strong></a><br /> | Read/write<br /> | Specifies whether the security warning dialog box should include a warning about clipboard redirection before starting a session.<br /> | 
| <a href="imsrdpclientnonscriptable5-warnaboutdirectxredirection.md"><strong>WarnAboutDirectXRedirection</strong></a><br /> | Read/write<br /> | This property is not used.<br /> | 
| <a href="imsrdpclientnonscriptable4-warnaboutprinterredirection.md"><strong>WarnAboutPrinterRedirection</strong></a><br /> | Read/write<br /> | Specifies whether the redirection dialog box displays a message about printer redirection before starting a session.<br /> | 
| <a href="imsrdpclientnonscriptable3-warnaboutsendingcredentials.md"><strong>WarnAboutSendingCredentials</strong></a><br /> | Read/write<br /> | Specifies whether the security warning should include a warning about sending credentials to the remote server before starting a session.<br /> | 




 

## Requirements



| Requirement | Value |
|-------------------------------------|----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 10 \[desktop apps only\]<br/>                                            |
| Minimum supported server<br/> | Windows Server 2016<br/>                                                         |
| Type library<br/>             | <dl> <dt>MsTscAx.dll</dt> </dl> |
| DLL<br/>                      | <dl> <dt>MsTscAx.dll</dt> </dl> |
| CLSID<br/>                    | CLSID\_MsRdpClient10 is defined as C0EFA91A-EEB7-41C7-97FA-F0ED645EFB24<br/>     |



## See also

<dl> <dt>

[Remote Desktop ActiveX control classes](remote-desktop-activex-control-classes.md)
</dt> </dl>

