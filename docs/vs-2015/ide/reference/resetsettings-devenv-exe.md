---
title: "-ResetSettings (devenv.exe) | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "Devenv, /ResetSettings switch"
  - "ResetSettings switch"
  - "/ResetSettings Devenv switch"
ms.assetid: 1d41021c-6f58-4bd5-b122-d1c995812192
caps.latest.revision: 14
author: gewarren
ms.author: gewarren
manager: "ghogen"
---
# /ResetSettings (devenv.exe)
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [-ResetSettings (devenv.exe)](https://docs.microsoft.com/visualstudio/ide/reference/resetsettings-devenv-exe).  
  
  
Restores [!INCLUDE[vsprvs](../../includes/vsprvs-md.md)] default settings and automatically launches the [!INCLUDE[vsprvs](../../includes/vsprvs-md.md)] IDE. Optionally resets the settings to a specified .vssettings file.  
  
 The default settings are determined by the profile that was selected when [!INCLUDE[vsprvs](../../includes/vsprvs-md.md)] was first launched.  
  
## Syntax  
  
```  
Devenv /ResetSettings SettingsFile  
```  
  
## Arguments  
 `SettingsFile`  
 The full path and name of the .vssettings file to apply to [!INCLUDE[vsprvs](../../includes/vsprvs-md.md)].  
  
 To restore the General Development Settings profile, use `General`.  
  
## Remarks  
 If no `SettingsFile` is specified, you will be prompted to select a default collection of settings the next time you start [!INCLUDE[vsprvs](../../includes/vsprvs-md.md)].  
  
## Example  
 The following command line applies the settings stored in the file `MySettings.vssettings`.  
  
```  
Devenv.exe /ResetSettings "C:\My Files\MySettings.vssettings"  
```  
  
## See Also  
 [Customizing Development Settings in Visual Studio](http://msdn.microsoft.com/en-us/22c4debb-4e31-47a8-8f19-16f328d7dcd3)   
 [Devenv Command Line Switches](../../ide/reference/devenv-command-line-switches.md)


