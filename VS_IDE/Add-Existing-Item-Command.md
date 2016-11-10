---
title: "Add Existing Item Command"
ms.custom: na
ms.date: 10/03/2016
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - vs-ide-general
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 41f56131-d4c7-4f81-83b7-bdac713ea870
caps.latest.revision: 13
manager: ghogen
translation.priority.ht: 
  - cs-cz
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - pl-pl
  - pt-br
  - ru-ru
  - tr-tr
  - zh-cn
  - zh-tw
---
# Add Existing Item Command
Adds an existing file to the current solution and opens it.  
  
## Syntax  
  
```  
File.AddExistingItem filename [/e:editorname]  
```  
  
## Arguments  
 `filename`  
 Required. The full path and file name, with extension, of the item to add to the current solution. If the file path or file name contains spaces, enclose the entire path in quotation marks.  
  
## Switches  
 /e: `editorname`  
 Optional. Name of the editor in which the file will be opened. If the argument is specified but no editor name is supplied, the **Open With** dialog box appears.  
  
 The /e:`editorname` argument syntax uses the editor names as they appear in the **Open With Dialog Box**, enclosed in quotation marks. For example, to open a style sheet in the source code editor, you would enter the following for the /e:`editorname` argument.  
  
```  
/e:"Source Code (text) Editor"  
```  
  
## Remarks  
 Autocompletion tries to locate the correct path and file name as you type.  
  
## Example  
 This example adds the file, Form1.frm, to the current solution.  
  
```  
>File.AddExistingItem "C:\public\solution files\Form1.frm"  
```  
  
## See Also  
 [Visual Studio Commands](../VS_IDE/Visual-Studio-Commands.md)   
 [Command Window](../VS_IDE/Command-Window.md)   
 [Find/Command Box](../VS_IDE/Find-Command-Box.md)   
 [Visual Studio Command Aliases](../VS_IDE/Visual-Studio-Command-Aliases.md)