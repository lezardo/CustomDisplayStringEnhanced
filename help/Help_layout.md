
| **Name** | ** Custom Display String Enhanced** | **Version** | 
| --- | --- | --- |
| **Updated by** | Mathias PFAUWADEL | 1.1 |


## Patch Notes

* 1.1 : Adding pop to all object if it's exist
* 1.0 : 1st version working

## To be Done


## Description 
Allow you to modify the custom display string to be more flexible

## Screen Shot
<img src="https://raw.githubusercontent.com/nevakee716/CustomDisplayStringEnhanced/master/screen/1.jpg" alt="Drawing" style="width: 95%;"/>

## Node setup

```
if the {objectType}_diagram_popout exist, it will automatically add the pop icon
if you want a specific pop out use that syntax
<@{name}@> GDPR <#process_diagram_popout#>
```

## Options


### URL to the object Page : 

If you put <@ @>, only the part inside will be clickable on drive you to the objectPage

### Diagram pop-out :

If you put <#nameofthePopOut #>, this will create an icon, when clicking it will open the popOut

### Disable the automatic icon

Go into src\cdsEnhanced.js
````var popOutEnableByDefault = true;````
put the value to false





