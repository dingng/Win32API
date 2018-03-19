
## Function name : IsMenu
Group: Menu - Library: user32    
***  


#### The IsMenu function determines whether a handle is a menu handle. 
***  


## Code examples:
[Programmatically removing submenus from VFP main menu](../../samples/sample_258.md)  
[Reading the structure of VFP main menu](../../samples/sample_337.md)  
[Accessing Adobe Reader 7.0 main menu from VFP application](../../samples/sample_495.md)  
[How to control Adobe Reader 9.0 (SDI mode) from VFP application](../../samples/sample_550.md)  

## Declaration:
```foxpro  
BOOL IsMenu(
	HMENU hMenu
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER IsMenu IN user32;
	INTEGER hMenu  
```  
***  


## Parameters:
hMenu
[in] Handle to be tested. 
  
***  


## Return value:
If hMenu is a menu handle, the return value is nonzero.   
***  
