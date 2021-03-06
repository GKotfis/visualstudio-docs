---
title: "IDebugThread2::GetProgram | Microsoft Docs"
ms.date: "11/04/2016"
ms.topic: "conceptual"
f1_keywords: 
  - "IDebugThread2::GetProgram"
helpviewer_keywords: 
  - "IDebugThread2::GetProgram"
ms.assetid: 8c9c5ea1-2031-472e-bc8f-30e22e754566
author: "gregvanl"
ms.author: "gregvanl"
manager: jillfra
ms.workload: 
  - "vssdk"
---
# IDebugThread2::GetProgram
Gets the program in which a thread is running.  
  
## Syntax  
  
```cpp  
HRESULT GetProgram (   
   IDebugProgram2** ppProgram  
);  
```  
  
```csharp  
int GetProgram (   
   out IDebugProgram2 ppProgram  
);  
```  
  
#### Parameters  
 `ppProgram`  
 [out] Returns an [IDebugProgram2](../../../extensibility/debugger/reference/idebugprogram2.md) object that represents the program this thread is running in.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugThread2](../../../extensibility/debugger/reference/idebugthread2.md)   
 [IDebugProgram2](../../../extensibility/debugger/reference/idebugprogram2.md)