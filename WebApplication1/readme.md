Author       : Microsoft Corporation
Help         : https://docs.microsoft.com/azure/devops/pipelines/tasks/utility/file-transform
==============================================================================
Applying XDT Transformation from transformation file c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config -> source file C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config 
C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe s:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config t:c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config d:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config pw i verbose
Start tranformation to 'C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config'.
Source file: 'C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config'.
Transform  file: 'c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config'.
Transformation task is using encoding 'System.Text.UTF8Encoding'. Change encoding in source file, or use the 'encoding' parameter if you want to change encoding.
Executing SetAttributes (transform line 7, 97)
on /configuration/location/system.webServer/aspNetCore/environmentVariables/environmentVariable[@name='ASPNETCORE_ENVIRONMENT']
Applying to 'environmentVariable' element (no source line info)
Set 'name' attribute
Set 'value' attribute
Set 2 attributes
Done executing SetAttributes
Executing SetAttributes (transform line 8, 74)
on /configuration/location/system.webServer/aspNetCore/environmentVariables/environmentVariable[@name='CustomSetting']
Applying to 'environmentVariable' element (no source line info)
Set 'name' attribute
Set 'value' attribute
Set 2 attributes
Done executing SetAttributes
XML Transformations applied successfully
Initiated variable substitution in config file : C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config
Skipped Updating file: C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config
XML variable substitution applied successfully.
Finishing: Apply File Transformations on web.config
