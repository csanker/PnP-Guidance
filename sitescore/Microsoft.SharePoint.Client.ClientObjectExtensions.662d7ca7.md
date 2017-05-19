# ClientObjectExtensions.EnsureProperties Method  
 Ensures that particular properties are loaded on the   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void EnsureProperties(T clientObject, Expression<Func<T, Object>>[] propertySelector)
```
### Parameters
#### clientObject  
&emsp;&emsp;Type: T  
&emsp;&emsp; Ensures that particular properties are loaded on the   

  

#### propertySelector  
&emsp;&emsp;Type: System.Linq.Expressions.Expression&lt;System.Func&lt;T, System.Object&gt;&gt;[]  
&emsp;&emsp;Lamda expressions containing the properties to ensure (e.g. w => w.HasUniqueRoleAssignments, w => w.ServerRelativeUrl)  

  

### Return Value
Type: void  
Property value  


## Remarks
  
## See also
- [ClientObjectExtensions](Microsoft.SharePoint.Client.ClientObjectExtensions.md) 
- Microsoft.SharePoint.Client.ClientObject
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 