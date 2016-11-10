---
title: "&#39;&lt;typename&gt;&#39; is a generic type and requires type arguments"
ms.custom: na
ms.date: "10/13/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-csharp"
ms.tgt_pltfrm: na
ms.topic: "article"
f1_keywords: 
  - "BC32076"
  - "vbc32076"
helpviewer_keywords: 
  - "BC32076"
ms.assetid: 57f63727-c544-4012-8f03-5d77fbdd1135
caps.latest.revision: 9
ms.author: "billchi"
manager: "douge"
translation.priority.ht: 
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "ru-ru"
  - "zh-cn"
  - "zh-tw"
translation.priority.mt: 
  - "cs-cz"
  - "pl-pl"
  - "pt-br"
  - "tr-tr"
---
# &#39;&lt;typename&gt;&#39; is a generic type and requires type arguments
A variable, procedure parameter, or function return is declared to have the type of a generic class or structure, but the declaration does not supply any type arguments.  
  
 By its nature, every generic class and structure is defined with at least one type parameter. When you use a generic type to declare a constructed class or structure, you must supply a type argument for every type parameter defined by the generic type.  
  
 **Error ID:** BC32076  
  
### To correct this error  
  
-   Add a type list to the declaration, enclosed in parentheses and beginning with the `Of` keyword.  
  
## See Also  
 [Generic Types in Visual Basic](../Topic/Generic%20Types%20in%20Visual%20Basic%20\(Visual%20Basic\).md)   
 [Of](../Topic/Of%20Clause%20\(Visual%20Basic\).md)   
 [Type List](../Topic/Type%20List%20\(Visual%20Basic\).md)