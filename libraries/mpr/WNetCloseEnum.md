
## Function name : WNetCloseEnum
Group: Windows Networking - Library: mpr    
***  


#### The WNetCloseEnum function ends a network resource enumeration started by a call to the WNetOpenEnum function.
***  


## Code examples:
[Enumerating network resources](../../samples/sample_313.md)  

## Declaration:
```foxpro  
DWORD WNetCloseEnum(
  HANDLE hEnum   // handle to enumeration
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER WNetCloseEnum IN mpr;
	INTEGER hEnum  
```  
***  


## Parameters:
hEnum 
[in] Specifies a handle that identifies an enumeration instance. This handle must be returned by the WNetOpenEnum function.   
***  


## Return value:
If the function succeeds, the return value is NO_ERROR.   
***  
