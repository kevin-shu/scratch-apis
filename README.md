# scratch-apis

## Project API:
* Create project:   
``Post https://projects.scratch.mit.edu/internalapi/project/new/set/?v=v442&_rnd=0.8944945121183991&title=Untitled``
* Get Project Object:  
``GET http://cdn.projects.scratch.mit.edu/internalapi/project/91285513/get/``
* Save Project:  
``POST https://projects.scratch.mit.edu/internalapi/project/118828855/set/?v=v448&_rnd=0.27443298837170005``

## Library:
* Scratch.FlashAppView
* `Scratch.FlashApp.ASobj.ASgetProject`
* 

## Editor:
透過 SWFobject.js 函式庫操控 SWF: `var ASobj = swfobject.getObjectById("scratch");`
(以下用法可以在 project_base.js 中找到)
* ASobj.ASdownload()
* ASobj.ASisEditMode()
* ASobj.ASsetEditMode()
* ASobj.ASwasEdited()
* ASobj.ASsetTitle()
* ASobj.ASloadProject()
* ASobj.ASisEmpty()
* ASobj.ASisUnchanged()
* ASobj.ASshouldSave()
* ASobj.ASgetProject() - 儲存成 JSON
* ASobj.ASdumpRecordThumbnail()
* ASobj.AScanShare()

