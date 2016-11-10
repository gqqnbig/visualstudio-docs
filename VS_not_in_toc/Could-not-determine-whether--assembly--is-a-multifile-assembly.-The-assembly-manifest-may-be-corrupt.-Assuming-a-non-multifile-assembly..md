---
title: "Could not determine whether &#39;assembly&#39; is a multifile assembly. The assembly manifest may be corrupt. Assuming a non-multifile assembly."
ms.custom: na
ms.date: 10/01/2016
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-csharp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: be49d3f2-b091-488c-8579-e27ef09d9c80
caps.latest.revision: 8
manager: douge
translation.priority.ht: 
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - ru-ru
  - zh-cn
  - zh-tw
translation.priority.mt: 
  - cs-cz
  - pl-pl
  - pt-br
  - tr-tr
---
# Could not determine whether &#39;assembly&#39; is a multifile assembly. The assembly manifest may be corrupt. Assuming a non-multifile assembly.
The project system was unable to read an assembly referenced by your project, such that the project system is unable to determine whether you are referencing a multifile assembly. Therefore, the assembly may not be copied properly to the output directory.  
  
 **To correct this error**  
  
-   Reinstall Visual Studio (if the assembly came with Visual Studio or the .NET Framework).  
  
     \- or -  
  
-   Reinstall the appropriate third-party control.  
  
     This error will not prevent the project from building. However, a run-time error is possible.  
  
## See Also  
 [Troubleshooting Broken References](../VS_IDE/Troubleshooting-Broken-References.md)   
 [NIB How to: Add or Remove References By Using the Add Reference Dialog Box](assetId:///3bd75d61-f00c-47c0-86a2-dd1f20e231c9)   
 [Assemblies in the Common Language Runtime](assetId:///33a0bc6a-6bb3-44c7-ada7-4a046e8c0945)