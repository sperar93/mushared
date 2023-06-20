# mushared

Proyecto de servidor Mu Online para la comunidad de Uruguay.

Requisitos:

- Visual C++ Redistributable para Visual Studio 2012
- Microsoft SQL Server 2008 R2

Installacion:

;=====================================
; Change CustomerName and HardwareID
;=====================================
* 00 - MHPServer\MHPServer.ini
* 01 - ConnectServer\ConnectServer.ini
* 02 - JoinServer\JoinServer.ini
* 03 - DataServer\DataServer.ini
* 04 - GameServer\DATA\GameServerInfo - Common.dat
* 05 - GameServerCS\DATA\GameServerInfo - Common.dat
* Data\MapServerInfo.xml

;=====================================
; Change IP
;=====================================
* 01 - ConnectServer\ServerList.xml
* Data\MapServerInfo.xml
 
;=====================================
; Change MAIN_INFO/MainInfo.ini
;===================================== 
	CustomerName
	ServerIpAddress	
	ServerName
	WindowName
	MHPServerIpAddress

;=====================================
; Execute GetMainInfo.exe
; Copy & Paste to AH_INFO
;=====================================
	MHPClient.dll 
	MHPVerify.dll	
	main.exe	
	Main.dll
	Protect.sse

;=====================================
; Change IP AH_INFO\ClientInfo.ini
;=====================================	
	CustomerName 
	IpAddress 
	ServerName 
	
;=====================================
; Execute GetClientInfo.exe
; Copy & Paste to Client
;=====================================
	MHPClient.dll 
	MHPVerify.dll	
	main.exe	
	Main.dll
	Protect.sse
	ah.emu 
	
;=====================================
; OPEN PORTS
;=====================================
44405 - ConnectServer
55901 - GameServer01
55902 - GameServer02
55903 - GameServer03
55919 - GameServerCS
55999 - HackServer