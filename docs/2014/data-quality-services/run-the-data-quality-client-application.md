---
title: "Run the Data Quality Client Application | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.technology: data-quality-services
ms.topic: conceptual
f1_keywords: 
  - "sql12.dqs.browseforservers.f1"
  - "sql12.dqs.connecttoserver.f1"
ms.assetid: 0b2aa202-7ab2-4c9d-b0f1-802588053a1e
author: lrtoyou1223
ms.author: lle
manager: craigg
---
# Run the Data Quality Client Application
  You can use [!INCLUDE[ssDQSnoversion](../includes/ssdqsnoversion-md.md)] (DQS) by running [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)], and logging on to a [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)].  
  
##  <a name="BeforeYouBegin"></a> Before You Begin  
  
###  <a name="Prerequisites"></a> Prerequisites  
 You must have completed the [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)] installation by running the DQSInstaller.exe file. For more information, see [Run DQSInstaller.exe to Complete Data Quality Server Installation](install-windows/run-dqsinstaller-exe-to-complete-data-quality-server-installation.md).  
  
###  <a name="Security"></a> Security  
  
####  <a name="Permissions"></a> Permissions  
 You must have one of the three DQS roles (dqs_adminstrator, dqs_kb_editor, or dqs_kb_operator) granted on the DQS_MAIN database to be able to log on to [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)].  
  
##  <a name="Run"></a> Run Data Quality Client  
 To run [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)] on the computer where you have installed it, proceed as follows:  
  
1.  Click **Start**, point to **All Programs**, click **[!INCLUDE[ssCurrent](../includes/sscurrent-md.md)]**, click **Data Quality Services**, and then click **Data Quality Client**.  
  
2.  In the **Connect to Server** dialog box:  
  
    1.  Specify the server that you want to connect the [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)] application to. Select **(LOCAL)** to connect to [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)] on the local computer. You can also click the down arrow and select **\<Browse network for more servers>** to connect to a different server (or to connect to the local server by name). The **Browse for Servers** dialog box will be displayed. You can select a server in the **Local Servers** tab or in the **Network Servers** tab.  
  
    2.  If you want to encrypt data transfer between [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)] and [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)], click **Options**, and then select the **Encrypt Connection** check box.  
  
3.  Click **Connect**.  
  
 The [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)] home screen appears. For more information, see [Data Quality Client Home Screen](../../2014/data-quality-services/data-quality-client-home-screen.md).  
  
  
