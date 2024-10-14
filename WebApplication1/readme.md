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














2024-10-14T23:51:52.1854980Z ##[debug]Evaluating condition for step: 'Apply File Transformations on web.config'
2024-10-14T23:51:52.1855873Z ##[debug]Evaluating: SucceededNode()
2024-10-14T23:51:52.1856051Z ##[debug]Evaluating SucceededNode:
2024-10-14T23:51:52.1856553Z ##[debug]=> True
2024-10-14T23:51:52.1856757Z ##[debug]Result: True
2024-10-14T23:51:52.1856973Z ##[section]Starting: Apply File Transformations on web.config
2024-10-14T23:51:52.1881417Z ==============================================================================
2024-10-14T23:51:52.1881526Z Task         : File transform
2024-10-14T23:51:52.1881577Z Description  : Replace tokens with variable values in XML or JSON configuration files
2024-10-14T23:51:52.1881658Z Version      : 2.246.1
2024-10-14T23:51:52.1881713Z Author       : Microsoft Corporation
2024-10-14T23:51:52.1881768Z Help         : https://docs.microsoft.com/azure/devops/pipelines/tasks/utility/file-transform
2024-10-14T23:51:52.1881855Z ==============================================================================
2024-10-14T23:51:52.2256650Z ##[debug]Using node path: C:\Users\Administrator\agent\externals\node20_1\bin\node.exe
2024-10-14T23:51:52.4634326Z ##[debug]agent.TempDirectory=C:\Users\Administrator\agent\_work\_temp
2024-10-14T23:51:52.4635343Z ##[debug]loading inputs and endpoints
2024-10-14T23:51:52.4636027Z ##[debug]loading ENDPOINT_AUTH_PARAMETER_SYSTEMVSSCONNECTION_ACCESSTOKEN
2024-10-14T23:51:52.4773527Z ##[debug]loading ENDPOINT_AUTH_SCHEME_SYSTEMVSSCONNECTION
2024-10-14T23:51:52.4774986Z ##[debug]loading ENDPOINT_AUTH_SYSTEMVSSCONNECTION
2024-10-14T23:51:52.4776052Z ##[debug]loading INPUT_FILETYPE
2024-10-14T23:51:52.4776870Z ##[debug]loading INPUT_FOLDERPATH
2024-10-14T23:51:52.4777156Z ##[debug]loading INPUT_XMLTARGETFILES
2024-10-14T23:51:52.4777434Z ##[debug]loading INPUT_XMLTRANSFORMATIONRULES
2024-10-14T23:51:52.4777703Z ##[debug]loading SECRET_SYSTEM_ACCESSTOKEN
2024-10-14T23:51:52.4778163Z ##[debug]loaded 8
2024-10-14T23:51:52.4778434Z ##[debug]Agent.ProxyUrl=undefined
2024-10-14T23:51:52.4778700Z ##[debug]Agent.CAInfo=undefined
2024-10-14T23:51:52.4778969Z ##[debug]Agent.ClientCert=undefined
2024-10-14T23:51:52.4779245Z ##[debug]Agent.SkipCertValidation=undefined
2024-10-14T23:51:52.7308984Z ##[debug]check path : C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\task.json
2024-10-14T23:51:52.7309895Z ##[debug]adding resource file: C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\task.json
2024-10-14T23:51:52.7310679Z ##[debug]system.culture=en-US
2024-10-14T23:51:52.7346314Z ##[debug]check path : C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\module.json
2024-10-14T23:51:52.7347085Z ##[debug]adding resource file: C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\module.json
2024-10-14T23:51:52.7347847Z ##[debug]system.culture=en-US
2024-10-14T23:51:52.7502898Z ##[debug]folderPath=C:\Users\Administrator\agent\_work\3\a\Release
2024-10-14T23:51:52.7514938Z ##[debug]Finding files matching input: C:\Users\Administrator\agent\_work\3\a\Release
2024-10-14T23:51:52.7515942Z ##[debug]xmlTransformationRules=-transform **\*.Release.config -xml **\*.config
2024-10-14T23:51:52.7516265Z ##[debug]xmlTargetFiles=**/web.config
2024-10-14T23:51:52.7516534Z ##[debug]jsonTargetFiles=undefined
2024-10-14T23:51:52.7516827Z ##[debug]defaultRoot: 'C:\Users\Administrator\agent\_work\3\a\Release'
2024-10-14T23:51:52.7517130Z ##[debug]findOptions.allowBrokenSymbolicLinks: 'false'
2024-10-14T23:51:52.7517415Z ##[debug]findOptions.followSpecifiedSymbolicLink: 'false'
2024-10-14T23:51:52.7517703Z ##[debug]findOptions.followSymbolicLinks: 'false'
2024-10-14T23:51:52.7518011Z ##[debug]findOptions.skipMissingFiles: 'undefined'
2024-10-14T23:51:52.7518278Z ##[debug]matchOptions.debug: 'false'
2024-10-14T23:51:52.7519820Z ##[debug]matchOptions.nobrace: 'true'
2024-10-14T23:51:52.7520107Z ##[debug]matchOptions.noglobstar: 'false'
2024-10-14T23:51:52.7520373Z ##[debug]matchOptions.dot: 'true'
2024-10-14T23:51:52.7520648Z ##[debug]matchOptions.noext: 'false'
2024-10-14T23:51:52.7520913Z ##[debug]matchOptions.nocase: 'true'
2024-10-14T23:51:52.7521176Z ##[debug]matchOptions.nonull: 'false'
2024-10-14T23:51:52.7521449Z ##[debug]matchOptions.matchBase: 'false'
2024-10-14T23:51:52.7521719Z ##[debug]matchOptions.nocomment: 'false'
2024-10-14T23:51:52.7521982Z ##[debug]matchOptions.nonegate: 'false'
2024-10-14T23:51:52.7522253Z ##[debug]matchOptions.flipNegate: 'false'
2024-10-14T23:51:52.7522515Z ##[debug]pattern: '**\*.config'
2024-10-14T23:51:52.7522795Z ##[debug]findPath: 'C:\Users\Administrator\agent\_work\3\a\Release'
2024-10-14T23:51:52.7523077Z ##[debug]statOnly: 'false'
2024-10-14T23:51:52.7523362Z ##[debug]findPath: 'C:\Users\Administrator\agent\_work\3\a\Release'
2024-10-14T23:51:52.7523649Z ##[debug]findOptions.allowBrokenSymbolicLinks: 'false'
2024-10-14T23:51:52.7523933Z ##[debug]findOptions.followSpecifiedSymbolicLink: 'false'
2024-10-14T23:51:52.7524218Z ##[debug]findOptions.followSymbolicLinks: 'false'
2024-10-14T23:51:52.7524499Z ##[debug]findOptions.skipMissingFiles: 'undefined'
2024-10-14T23:51:52.7524788Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release (directory)
2024-10-14T23:51:52.7525109Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1 (directory)
2024-10-14T23:51:52.7525545Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\appsettings.Development.json (file)
2024-10-14T23:51:52.7525880Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\appsettings.json (file)
2024-10-14T23:51:52.7526214Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config (file)
2024-10-14T23:51:52.7526689Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.Release.config (file)
2024-10-14T23:51:52.7527039Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.deps.json (file)
2024-10-14T23:51:52.7527374Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.dll (file)
2024-10-14T23:51:52.7527715Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.exe (file)
2024-10-14T23:51:52.7528059Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.pdb (file)
2024-10-14T23:51:52.7528401Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.runtimeconfig.json (file)
2024-10-14T23:51:52.7528746Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot (directory)
2024-10-14T23:51:52.7529076Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\css (directory)
2024-10-14T23:51:52.7530144Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\css\site.css (file)
2024-10-14T23:51:52.7531008Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\favicon.ico (file)
2024-10-14T23:51:52.7531354Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\js (directory)
2024-10-14T23:51:52.7531682Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\js\site.js (file)
2024-10-14T23:51:52.7532024Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib (directory)
2024-10-14T23:51:52.7532364Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap (directory)
2024-10-14T23:51:52.7532714Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist (directory)
2024-10-14T23:51:52.7533065Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css (directory)
2024-10-14T23:51:52.7533929Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.css (file)
2024-10-14T23:51:52.7565694Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.css.map (file)
2024-10-14T23:51:52.7566195Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.min.css (file)
2024-10-14T23:51:52.7566591Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.min.css.map (file)
2024-10-14T23:51:52.7566968Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.rtl.css (file)
2024-10-14T23:51:52.7567350Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.rtl.css.map (file)
2024-10-14T23:51:52.7567745Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.rtl.min.css (file)
2024-10-14T23:51:52.7568131Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.rtl.min.css.map (file)
2024-10-14T23:51:52.7568510Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.css (file)
2024-10-14T23:51:52.7568878Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.css.map (file)
2024-10-14T23:51:52.7569256Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.min.css (file)
2024-10-14T23:51:52.7569634Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.min.css.map (file)
2024-10-14T23:51:52.7570218Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.rtl.css (file)
2024-10-14T23:51:52.7570622Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.rtl.css.map (file)
2024-10-14T23:51:52.7571001Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.rtl.min.css (file)
2024-10-14T23:51:52.7571375Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.rtl.min.css.map (file)
2024-10-14T23:51:52.7571749Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.css (file)
2024-10-14T23:51:52.7572129Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.css.map (file)
2024-10-14T23:51:52.7572510Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.min.css (file)
2024-10-14T23:51:52.7572891Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.min.css.map (file)
2024-10-14T23:51:52.7573265Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.rtl.css (file)
2024-10-14T23:51:52.7573643Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.rtl.css.map (file)
2024-10-14T23:51:52.7574027Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.rtl.min.css (file)
2024-10-14T23:51:52.7574415Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.rtl.min.css.map (file)
2024-10-14T23:51:52.7575258Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.css (file)
2024-10-14T23:51:52.7575618Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.css.map (file)
2024-10-14T23:51:52.7575988Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.min.css (file)
2024-10-14T23:51:52.7576523Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.min.css.map (file)
2024-10-14T23:51:52.7576894Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.rtl.css (file)
2024-10-14T23:51:52.7600691Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.rtl.css.map (file)
2024-10-14T23:51:52.7601173Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.rtl.min.css (file)
2024-10-14T23:51:52.7601570Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.rtl.min.css.map (file)
2024-10-14T23:51:52.7601951Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js (directory)
2024-10-14T23:51:52.7602322Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.bundle.js (file)
2024-10-14T23:51:52.7602700Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.bundle.js.map (file)
2024-10-14T23:51:52.7603077Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.bundle.min.js (file)
2024-10-14T23:51:52.7603443Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.bundle.min.js.map (file)
2024-10-14T23:51:52.7603947Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.esm.js (file)
2024-10-14T23:51:52.7604327Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.esm.js.map (file)
2024-10-14T23:51:52.7604709Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.esm.min.js (file)
2024-10-14T23:51:52.7605083Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.esm.min.js.map (file)
2024-10-14T23:51:52.7605444Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.js (file)
2024-10-14T23:51:52.7605809Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.js.map (file)
2024-10-14T23:51:52.7606180Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.min.js (file)
2024-10-14T23:51:52.7606550Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.min.js.map (file)
2024-10-14T23:51:52.7606909Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\LICENSE (file)
2024-10-14T23:51:52.7611534Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery (directory)
2024-10-14T23:51:52.7612237Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\dist (directory)
2024-10-14T23:51:52.7612855Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\dist\jquery.js (file)
2024-10-14T23:51:52.7613588Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\dist\jquery.min.js (file)
2024-10-14T23:51:52.7614444Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\dist\jquery.min.map (file)
2024-10-14T23:51:52.7614806Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\LICENSE.txt (file)
2024-10-14T23:51:52.7615160Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation (directory)
2024-10-14T23:51:52.7615520Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist (directory)
2024-10-14T23:51:52.7615892Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist\additional-methods.js (file)
2024-10-14T23:51:52.7616404Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist\additional-methods.min.js (file)
2024-10-14T23:51:52.7633856Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist\jquery.validate.js (file)
2024-10-14T23:51:52.7634529Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist\jquery.validate.min.js (file)
2024-10-14T23:51:52.7635368Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\LICENSE.md (file)
2024-10-14T23:51:52.7635890Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation-unobtrusive (directory)
2024-10-14T23:51:52.7636281Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation-unobtrusive\jquery.validate.unobtrusive.js (file)
2024-10-14T23:51:52.7636686Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation-unobtrusive\jquery.validate.unobtrusive.min.js (file)
2024-10-14T23:51:52.7637203Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation-unobtrusive\LICENSE.txt (file)
2024-10-14T23:51:52.7637585Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\WebApplication1.styles.css (file)
2024-10-14T23:51:52.7637892Z ##[debug]85 results
2024-10-14T23:51:52.7638140Z ##[debug]found 85 paths
2024-10-14T23:51:52.7638398Z ##[debug]applying include pattern
2024-10-14T23:51:52.7638696Z ##[debug]adjustedPattern: 'C:\Users\Administrator\agent\_work\3\a\Release\**\*.config'
2024-10-14T23:51:52.7638977Z ##[debug]2 matches
2024-10-14T23:51:52.7639228Z ##[debug]2 final results
2024-10-14T23:51:52.7639833Z Applying XDT Transformation from transformation file c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config -> source file C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config 
2024-10-14T23:51:52.7640497Z ##[debug]Running command: C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe s:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config t:c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config d:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config pw i verbose
2024-10-14T23:51:52.7673827Z ##[debug]which 'C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe'
2024-10-14T23:51:52.7674339Z ##[debug]found: 'C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe'
2024-10-14T23:51:52.7675116Z ##[debug]C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe arg: ["s:C:\\Users\\Administrator\\agent\\_work\\3\\a\\Release\\WebApplication1\\web.config","t:c:\\users\\administrator\\agent\\_work\\3\\a\\release\\webapplication1\\web.release.config","d:C:\\Users\\Administrator\\agent\\_work\\3\\a\\Release\\WebApplication1\\web.config","pw","i","verbose"]
2024-10-14T23:51:52.7676062Z ##[debug]C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe arg: ["s:C:\\Users\\Administrator\\agent\\_work\\3\\a\\Release\\WebApplication1\\web.config","t:c:\\users\\administrator\\agent\\_work\\3\\a\\release\\webapplication1\\web.release.config","d:C:\\Users\\Administrator\\agent\\_work\\3\\a\\Release\\WebApplication1\\web.config","pw","i","verbose"]
2024-10-14T23:51:52.7676687Z ##[debug]exec tool: C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe
2024-10-14T23:51:52.7677135Z ##[debug]exec tool: C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe
2024-10-14T23:51:52.7677484Z ##[debug]arguments:
2024-10-14T23:51:52.7677737Z ##[debug]arguments:
2024-10-14T23:51:52.7678024Z ##[debug]   s:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config
2024-10-14T23:51:52.7678363Z ##[debug]   s:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config
2024-10-14T23:51:52.7678698Z ##[debug]   t:c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config
2024-10-14T23:51:52.7679039Z ##[debug]   t:c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config
2024-10-14T23:51:52.7679367Z ##[debug]   d:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config
2024-10-14T23:51:52.7679697Z ##[debug]   d:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config
2024-10-14T23:51:52.7680457Z ##[debug]   pw
2024-10-14T23:51:52.7680694Z ##[debug]   pw
2024-10-14T23:51:52.7680938Z ##[debug]   i
2024-10-14T23:51:52.7681174Z ##[debug]   i
2024-10-14T23:51:52.7681481Z ##[debug]   verbose
2024-10-14T23:51:52.7681742Z ##[debug]   verbose
2024-10-14T23:51:52.7682525Z [command]C:\Users\Administrator\agent\_work\_tasks\FileTransform_8ce97e91-56cc-4743-bfab-9a9315be5f27\2.246.1\node_modules\azure-pipelines-tasks-webdeployment-common\ctt\ctt\ctt.exe s:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config t:c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config d:C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config pw i verbose
2024-10-14T23:51:53.6886586Z Start tranformation to 'C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config'.
2024-10-14T23:51:53.6887149Z Source file: 'C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config'.
2024-10-14T23:51:53.6887488Z Transform  file: 'c:\users\administrator\agent\_work\3\a\release\webapplication1\web.release.config'.
2024-10-14T23:51:53.6887846Z Transformation task is using encoding 'System.Text.UTF8Encoding'. Change encoding in source file, or use the 'encoding' parameter if you want to change encoding.
2024-10-14T23:51:53.6888063Z Executing SetAttributes (transform line 7, 97)
2024-10-14T23:51:53.6888347Z on /configuration/location/system.webServer/aspNetCore/environmentVariables/environmentVariable[@name='ASPNETCORE_ENVIRONMENT']
2024-10-14T23:51:53.6888613Z Applying to 'environmentVariable' element (no source line info)
2024-10-14T23:51:53.6888800Z Set 'name' attribute
2024-10-14T23:51:53.6888966Z Set 'value' attribute
2024-10-14T23:51:53.6889088Z Set 2 attributes
2024-10-14T23:51:53.6889223Z Done executing SetAttributes
2024-10-14T23:51:53.6889373Z Executing SetAttributes (transform line 8, 74)
2024-10-14T23:51:53.6889651Z on /configuration/location/system.webServer/aspNetCore/environmentVariables/environmentVariable[@name='CustomSetting']
2024-10-14T23:51:53.6889908Z Applying to 'environmentVariable' element (no source line info)
2024-10-14T23:51:53.6890277Z Set 'name' attribute
2024-10-14T23:51:53.6890442Z Set 'value' attribute
2024-10-14T23:51:53.6890562Z Set 2 attributes
2024-10-14T23:51:53.6890696Z Done executing SetAttributes
2024-10-14T23:51:53.6901474Z XML Transformations applied successfully
2024-10-14T23:51:53.6902527Z ##[debug]defaultRoot: 'C:\Users\Administrator\agent\_work\3\a\Release'
2024-10-14T23:51:53.6902837Z ##[debug]findOptions.allowBrokenSymbolicLinks: 'false'
2024-10-14T23:51:53.6903124Z ##[debug]findOptions.followSpecifiedSymbolicLink: 'true'
2024-10-14T23:51:53.6903404Z ##[debug]findOptions.followSymbolicLinks: 'true'
2024-10-14T23:51:53.6903665Z ##[debug]findOptions.skipMissingFiles: 'false'
2024-10-14T23:51:53.6903929Z ##[debug]matchOptions.debug: 'false'
2024-10-14T23:51:53.6904188Z ##[debug]matchOptions.nobrace: 'true'
2024-10-14T23:51:53.6904447Z ##[debug]matchOptions.noglobstar: 'false'
2024-10-14T23:51:53.6904704Z ##[debug]matchOptions.dot: 'true'
2024-10-14T23:51:53.6904965Z ##[debug]matchOptions.noext: 'false'
2024-10-14T23:51:53.6905212Z ##[debug]matchOptions.nocase: 'true'
2024-10-14T23:51:53.6905467Z ##[debug]matchOptions.nonull: 'false'
2024-10-14T23:51:53.6905728Z ##[debug]matchOptions.matchBase: 'false'
2024-10-14T23:51:53.6905982Z ##[debug]matchOptions.nocomment: 'false'
2024-10-14T23:51:53.6906236Z ##[debug]matchOptions.nonegate: 'false'
2024-10-14T23:51:53.6906498Z ##[debug]matchOptions.flipNegate: 'false'
2024-10-14T23:51:53.6906744Z ##[debug]pattern: '**/web.config'
2024-10-14T23:51:53.6907016Z ##[debug]findPath: 'C:\Users\Administrator\agent\_work\3\a\Release'
2024-10-14T23:51:53.6907287Z ##[debug]statOnly: 'false'
2024-10-14T23:51:53.6907554Z ##[debug]findPath: 'C:\Users\Administrator\agent\_work\3\a\Release'
2024-10-14T23:51:53.6907839Z ##[debug]findOptions.allowBrokenSymbolicLinks: 'false'
2024-10-14T23:51:53.6908269Z ##[debug]findOptions.followSpecifiedSymbolicLink: 'true'
2024-10-14T23:51:53.6908533Z ##[debug]findOptions.followSymbolicLinks: 'true'
2024-10-14T23:51:53.6908804Z ##[debug]findOptions.skipMissingFiles: 'false'
2024-10-14T23:51:53.6909092Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release (directory)
2024-10-14T23:51:53.6909390Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1 (directory)
2024-10-14T23:51:53.6909719Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\appsettings.Development.json (file)
2024-10-14T23:51:53.6910060Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\appsettings.json (file)
2024-10-14T23:51:53.6910387Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config (file)
2024-10-14T23:51:53.6911418Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.Release.config (file)
2024-10-14T23:51:53.6911835Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.deps.json (file)
2024-10-14T23:51:53.6912175Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.dll (file)
2024-10-14T23:51:53.6912509Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.exe (file)
2024-10-14T23:51:53.6912822Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.pdb (file)
2024-10-14T23:51:53.6913158Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\WebApplication1.runtimeconfig.json (file)
2024-10-14T23:51:53.6913501Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot (directory)
2024-10-14T23:51:53.6913825Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\css (directory)
2024-10-14T23:51:53.6914140Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\css\site.css (file)
2024-10-14T23:51:53.6914468Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\favicon.ico (file)
2024-10-14T23:51:53.6914906Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\js (directory)
2024-10-14T23:51:53.6915232Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\js\site.js (file)
2024-10-14T23:51:53.6915547Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib (directory)
2024-10-14T23:51:53.6915880Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap (directory)
2024-10-14T23:51:53.6917050Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist (directory)
2024-10-14T23:51:53.6917529Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css (directory)
2024-10-14T23:51:53.6917891Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.css (file)
2024-10-14T23:51:53.6918257Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.css.map (file)
2024-10-14T23:51:53.6918635Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.min.css (file)
2024-10-14T23:51:53.6947433Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.min.css.map (file)
2024-10-14T23:51:53.6947920Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.rtl.css (file)
2024-10-14T23:51:53.6948296Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.rtl.css.map (file)
2024-10-14T23:51:53.6948657Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.rtl.min.css (file)
2024-10-14T23:51:53.6949163Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-grid.rtl.min.css.map (file)
2024-10-14T23:51:53.6949538Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.css (file)
2024-10-14T23:51:53.6949904Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.css.map (file)
2024-10-14T23:51:53.6950276Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.min.css (file)
2024-10-14T23:51:53.6950645Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.min.css.map (file)
2024-10-14T23:51:53.6951003Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.rtl.css (file)
2024-10-14T23:51:53.6951371Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.rtl.css.map (file)
2024-10-14T23:51:53.6951746Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.rtl.min.css (file)
2024-10-14T23:51:53.6952117Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-reboot.rtl.min.css.map (file)
2024-10-14T23:51:53.6952484Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.css (file)
2024-10-14T23:51:53.6952838Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.css.map (file)
2024-10-14T23:51:53.6953207Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.min.css (file)
2024-10-14T23:51:53.6953590Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.min.css.map (file)
2024-10-14T23:51:53.6954023Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.rtl.css (file)
2024-10-14T23:51:53.6954389Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.rtl.css.map (file)
2024-10-14T23:51:53.6954747Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.rtl.min.css (file)
2024-10-14T23:51:53.6955122Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap-utilities.rtl.min.css.map (file)
2024-10-14T23:51:53.6955493Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.css (file)
2024-10-14T23:51:53.6955855Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.css.map (file)
2024-10-14T23:51:53.6956217Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.min.css (file)
2024-10-14T23:51:53.6956575Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.min.css.map (file)
2024-10-14T23:51:53.6956924Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.rtl.css (file)
2024-10-14T23:51:53.6957280Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.rtl.css.map (file)
2024-10-14T23:51:53.6962754Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.rtl.min.css (file)
2024-10-14T23:51:53.6963175Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\css\bootstrap.rtl.min.css.map (file)
2024-10-14T23:51:53.6963660Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js (directory)
2024-10-14T23:51:53.6964008Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.bundle.js (file)
2024-10-14T23:51:53.6964380Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.bundle.js.map (file)
2024-10-14T23:51:53.6964748Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.bundle.min.js (file)
2024-10-14T23:51:53.6965116Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.bundle.min.js.map (file)
2024-10-14T23:51:53.6965477Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.esm.js (file)
2024-10-14T23:51:53.6965833Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.esm.js.map (file)
2024-10-14T23:51:53.6966196Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.esm.min.js (file)
2024-10-14T23:51:53.6966562Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.esm.min.js.map (file)
2024-10-14T23:51:53.6966921Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.js (file)
2024-10-14T23:51:53.6967277Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.js.map (file)
2024-10-14T23:51:53.6967627Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.min.js (file)
2024-10-14T23:51:53.6967986Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\dist\js\bootstrap.min.js.map (file)
2024-10-14T23:51:53.6968392Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\bootstrap\LICENSE (file)
2024-10-14T23:51:53.6968729Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery (directory)
2024-10-14T23:51:53.6969058Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\dist (directory)
2024-10-14T23:51:53.6969399Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\dist\jquery.js (file)
2024-10-14T23:51:53.6977294Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\dist\jquery.min.js (file)
2024-10-14T23:51:53.6977662Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\dist\jquery.min.map (file)
2024-10-14T23:51:53.6978017Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery\LICENSE.txt (file)
2024-10-14T23:51:53.6978353Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation (directory)
2024-10-14T23:51:53.6978702Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist (directory)
2024-10-14T23:51:53.6979068Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist\additional-methods.js (file)
2024-10-14T23:51:53.6979451Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist\additional-methods.min.js (file)
2024-10-14T23:51:53.6979820Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist\jquery.validate.js (file)
2024-10-14T23:51:53.6980176Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\dist\jquery.validate.min.js (file)
2024-10-14T23:51:53.6980652Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation\LICENSE.md (file)
2024-10-14T23:51:53.6981008Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation-unobtrusive (directory)
2024-10-14T23:51:53.6981459Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation-unobtrusive\jquery.validate.unobtrusive.js (file)
2024-10-14T23:51:53.6981852Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation-unobtrusive\jquery.validate.unobtrusive.min.js (file)
2024-10-14T23:51:53.6982290Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\lib\jquery-validation-unobtrusive\LICENSE.txt (file)
2024-10-14T23:51:53.6982633Z ##[debug]  C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\wwwroot\WebApplication1.styles.css (file)
2024-10-14T23:51:53.6982934Z ##[debug]85 results
2024-10-14T23:51:53.6983178Z ##[debug]found 85 paths
2024-10-14T23:51:53.6983418Z ##[debug]applying include pattern
2024-10-14T23:51:53.6983708Z ##[debug]adjustedPattern: 'C:\Users\Administrator\agent\_work\3\a\Release\**/web.config'
2024-10-14T23:51:53.6983985Z ##[debug]1 matches
2024-10-14T23:51:53.6984216Z ##[debug]1 final results
2024-10-14T23:51:53.6998470Z ##[debug]system.accessToken=***
2024-10-14T23:51:53.7026981Z ##[debug]system.taskDisplayName=Apply File Transformations on web.config
2024-10-14T23:51:53.7027311Z ##[debug]build.requestedFor=Anvesh Muppeda
2024-10-14T23:51:53.7027588Z ##[debug]agent.retainDefaultEncoding=false
2024-10-14T23:51:53.7027864Z ##[debug]DistributedTask.Agent.FailJobWhenAgentDies=True
2024-10-14T23:51:53.7028125Z ##[debug]agent.useWorkspaceId=true
2024-10-14T23:51:53.7028406Z ##[debug]build.binariesdirectory=C:\Users\Administrator\agent\_work\3\b
2024-10-14T23:51:53.7028695Z ##[debug]build.queuedBy=Anvesh Muppeda
2024-10-14T23:51:53.7028952Z ##[debug]system.stageName=Build
2024-10-14T23:51:53.7029358Z ##[debug]DistributedTask.Agent.AgentEnablePipelineArtifactLargeChunkSize=True
2024-10-14T23:51:53.7029649Z ##[debug]DistributedTask.Agent.Rosetta2Warning=True
2024-10-14T23:51:53.7029921Z ##[debug]build.definitionFolderPath=\IIS
2024-10-14T23:51:53.7030172Z ##[debug]FAIL_DEPRECATED_BUILD_TASK=true
2024-10-14T23:51:53.7030436Z ##[debug]agent.LogToBlobstorageService=true
2024-10-14T23:51:53.7030696Z ##[debug]agent.isselfhosted=1
2024-10-14T23:51:53.7030960Z ##[debug]agent.homedirectory=C:\Users\Administrator\agent
2024-10-14T23:51:53.7031230Z ##[debug]agent.name=Win-Build-Server
2024-10-14T23:51:53.7031489Z ##[debug]AZP_75787_ENABLE_NEW_LOGIC_LOG=false
2024-10-14T23:51:53.7031740Z ##[debug]USE_MSDEPLOY_TOKEN_AUTH=true
2024-10-14T23:51:53.7032006Z ##[debug]DistributedTask.Agent.UseGitLongPaths=True
2024-10-14T23:51:53.7032267Z ##[debug]system.jobName=__default
2024-10-14T23:51:53.7032512Z ##[debug]agent.os=Windows_NT
2024-10-14T23:51:53.7032769Z ##[debug]build.sourceBranchName=test
2024-10-14T23:51:53.7033035Z ##[debug]build.buildUri=vstfs:///Build/Build/162
2024-10-14T23:51:53.7033287Z ##[debug]System.JobPositionInPhase=1
2024-10-14T23:51:53.7033550Z ##[debug]build.sourceVersionMessage=test
2024-10-14T23:51:53.7033807Z ##[debug]appPoolName=WebApplication
2024-10-14T23:51:53.7034060Z ##[debug]DistributedTask.Agent.MountWorkspace=True
2024-10-14T23:51:53.7034337Z ##[debug]task.displayname=Apply File Transformations on web.config
2024-10-14T23:51:53.7034614Z ##[debug]build.sourceVersionAuthor=Anvesh Muppeda
2024-10-14T23:51:53.7034873Z ##[debug]build.repository.provider=TfsGit
2024-10-14T23:51:53.7035129Z ##[debug]resources.triggeringAlias=
2024-10-14T23:51:53.7035410Z ##[debug]build.artifactstagingdirectory=C:\Users\Administrator\agent\_work\3\a
2024-10-14T23:51:53.7035690Z ##[debug]AGENT_USE_FETCH_FILTER_IN_CHECKOUT_TASK=true
2024-10-14T23:51:53.7036016Z ##[debug]system.postLinesSpeed=500
2024-10-14T23:51:53.7036278Z ##[debug]ENABLE_ISSUE_SOURCE_VALIDATION=true
2024-10-14T23:51:53.7036549Z ##[debug]build.requestedForId=5ffaafb4-c216-6693-9bda-57b102958e2d
2024-10-14T23:51:53.7036813Z ##[debug]USE_MSAL=true
2024-10-14T23:51:53.7037186Z ##[debug]agent.TempDirectory=C:\Users\Administrator\agent\_work\_temp
2024-10-14T23:51:53.7037466Z ##[debug]build.requestedForEmail=anvesh.muppeda@swbc.com
2024-10-14T23:51:53.7037760Z ##[debug]system.TeamFoundationServerUri=https://dev.azure.com/anveshmuppeda/
2024-10-14T23:51:53.7038044Z ##[debug]VSTSAGENT_DOCKER_ACTION_RETRIES=true
2024-10-14T23:51:53.7038364Z ##[debug]RETIRE_AZURERM_POWERSHELL_MODULE=true
2024-10-14T23:51:53.7038633Z ##[debug]AZP_ENABLE_RESOURCE_UTILIZATION_WARNINGS=true
2024-10-14T23:51:53.7038898Z ##[debug]websiteName=WebApplication
2024-10-14T23:51:53.7039168Z ##[debug]agent.disablelogplugin.TestResultLogPlugin=true
2024-10-14T23:51:53.7039451Z ##[debug]task.skipTranslatorForCheckout=False
2024-10-14T23:51:53.7039715Z ##[debug]build.sourceBranch=refs/heads/test
2024-10-14T23:51:53.7039974Z ##[debug]system.jobDisplayName=Job
2024-10-14T23:51:53.7040237Z ##[debug]DistributedTask.Agent.EnableIssueSourceValidation=True
2024-10-14T23:51:53.7040519Z ##[debug]system.stageId=6884a131-87da-5381-61f3-d7acc3b91d76
2024-10-14T23:51:53.7040801Z ##[debug]system.timelineId=6f89fef7-c4bf-4338-b3b8-23b073240cde
2024-10-14T23:51:53.7041073Z ##[debug]DistributedTask.Agent.UploadBuildArtifactsToBlob=False
2024-10-14T23:51:53.7041369Z ##[debug]DistributedTask.Agent.ContinueAfterCancelProcessTreeKillAttempt=True
2024-10-14T23:51:53.7041657Z ##[debug]DistributedTask.Agent.FailDeprecatedTask=True
2024-10-14T23:51:53.7041907Z ##[debug]system.phaseName=Job1
2024-10-14T23:51:53.7042157Z ##[debug]buildConfiguration=Release
2024-10-14T23:51:53.7042432Z ##[debug]build.sourceVersion=3015845f64c403cb2325feeef346a969469827c5
2024-10-14T23:51:53.7042714Z ##[debug]build.repository.localpath=C:\Users\Administrator\agent\_work\3\s
2024-10-14T23:51:53.7042991Z ##[debug]agent.jobstatus=Succeeded
2024-10-14T23:51:53.7043304Z ##[debug]USE_GIT_LONG_PATHS=true
2024-10-14T23:51:53.7043573Z ##[debug]build.sourcesdirectory=C:\Users\Administrator\agent\_work\3\s
2024-10-14T23:51:53.7043854Z ##[debug]system.teamProjectId=b13f62a5-9ecc-43dd-8c2f-b44c0867e577
2024-10-14T23:51:53.7044121Z ##[debug]system.jobTimeout=60
2024-10-14T23:51:53.7044391Z ##[debug]agent.workfolder=C:\Users\Administrator\agent\_work
2024-10-14T23:51:53.7044674Z ##[debug]system.teamFoundationCollectionUri=https://dev.azure.com/anveshmuppeda/
2024-10-14T23:51:53.7044974Z ##[debug]system.artifactsdirectory=C:\Users\Administrator\agent\_work\3\a
2024-10-14T23:51:53.7045303Z ##[debug]DistributedTask.Agent.EnableResourceUtilizationWarnings=True
2024-10-14T23:51:53.7045581Z ##[debug]system.collectionId=4ee44710-e935-4fab-969f-bd79343a4f6c
2024-10-14T23:51:53.7060451Z ##[debug]agent.ToolsDirectory=C:\Users\Administrator\agent\_work\_tool
2024-10-14T23:51:53.7060942Z ##[debug]pipeline.repository.name=IIS-Web-App
2024-10-14T23:51:53.7061468Z ##[debug]system.collectionUri=https://dev.azure.com/anveshmuppeda/
2024-10-14T23:51:53.7062201Z ##[debug]FAIL_DEPRECATED_TASK=true
2024-10-14T23:51:53.7062477Z ##[debug]system.pullRequest.isFork=False
2024-10-14T23:51:53.7062750Z ##[debug]build.queuedById=5ffaafb4-c216-6693-9bda-57b102958e2d
2024-10-14T23:51:53.7063010Z ##[debug]system.stageAttempt=1
2024-10-14T23:51:53.7063266Z ##[debug]USE_LATEST_GIT_VERSION=true
2024-10-14T23:51:53.7063543Z ##[debug]agent.builddirectory=C:\Users\Administrator\agent\_work\3
2024-10-14T23:51:53.7063805Z ##[debug]system.isScheduled=False
2024-10-14T23:51:53.7064078Z ##[debug]DistributedTask.Agent.FixPossibleGitOutOfMemoryProblem=False
2024-10-14T23:51:53.7064368Z ##[debug]DistributedTask.Agent.UseDockerComposeV2CompatibleMode=False
2024-10-14T23:51:53.7064641Z ##[debug]build.definitionName=IIS-Website-Web-App
2024-10-14T23:51:53.7065004Z ##[debug]System.OidcRequestUri=https://dev.azure.com/anveshmuppeda/b13f62a5-9ecc-43dd-8c2f-b44c0867e577/_apis/distributedtask/hubs/build/plans/6f89fef7-c4bf-4338-b3b8-23b073240cde/jobs/83516c17-6666-5250-abde-63983ce72a49/oidctoken
2024-10-14T23:51:53.7065510Z ##[debug]DistributedTask.Agent.ReadOnlyVariables=True
2024-10-14T23:51:53.7065786Z ##[debug]AZP_AGENT_IGNORE_VSTSTASKLIB=true
2024-10-14T23:51:53.7066048Z ##[debug]DistributedTask.Agent.DockerActionRetries=True
2024-10-14T23:51:53.7066313Z ##[debug]System.TotalJobsInPhase=1
2024-10-14T23:51:53.7066570Z ##[debug]FAIL_JOB_WHEN_AGENT_DIES=true
2024-10-14T23:51:53.7066835Z ##[debug]DistributedTask.Agent.EnableResourceMonitorDebugOutput=True
2024-10-14T23:51:53.7067122Z ##[debug]AZP_ENABLE_RESOURCE_MONITOR_DEBUG_OUTPUT=true
2024-10-14T23:51:53.7067409Z ##[debug]build.stagingdirectory=C:\Users\Administrator\agent\_work\3\a
2024-10-14T23:51:53.7067675Z ##[debug]AZP_75787_ENABLE_COLLECT=true
2024-10-14T23:51:53.7067951Z ##[debug]DistributedTask.Agent.USENEWNODEHANDLERTELEMETRY=True
2024-10-14T23:51:53.7068240Z ##[debug]agent.disablelogplugin.TestFilePublisherPlugin=true
2024-10-14T23:51:53.7068521Z ##[debug]DistributedTask.Agent.LogToBlobstorageService=True
2024-10-14T23:51:53.7068788Z ##[debug]agent.machinename=EC2AMAZ-0S0GDC5
2024-10-14T23:51:53.7069057Z ##[debug]DistributedTask.Agent.UseLatestGitVersion=True
2024-10-14T23:51:53.7069318Z ##[debug]system.hosttype=build
2024-10-14T23:51:53.7069607Z ##[debug]system.pipelineStartTime=2024-10-14 23:51:21+00:00
2024-10-14T23:51:53.7069911Z ##[debug]system.taskDefinitionsUri=https://dev.azure.com/anveshmuppeda/
2024-10-14T23:51:53.7070181Z ##[debug]system.servertype=Hosted
2024-10-14T23:51:53.7070427Z ##[debug]projectName=WebApplication1
2024-10-14T23:51:53.7070687Z ##[debug]AZP_PS_ENABLE_INVOKE_PROCESS=true
2024-10-14T23:51:53.7070940Z ##[debug]build.buildId=162
2024-10-14T23:51:53.7072535Z ##[debug]build.reason=Manual
2024-10-14T23:51:53.7072809Z ##[debug]build.definitionVersion=3
2024-10-14T23:51:53.7073076Z ##[debug]system.enableAccessToken=SecretVariable
2024-10-14T23:51:53.7073335Z ##[debug]build.containerId=30942763
2024-10-14T23:51:53.7073709Z ##[debug]AZP_75787_ENABLE_NEW_PH_LOGIC=true
2024-10-14T23:51:53.7073987Z ##[debug]system.jobId=83516c17-6666-5250-abde-63983ce72a49
2024-10-14T23:51:53.7074243Z ##[debug]ROSETTA2_WARNING=true
2024-10-14T23:51:53.7074512Z ##[debug]DistributedTask.Tasks.CopyFilesOverSSHV0UseQueue=False
2024-10-14T23:51:53.7074806Z ##[debug]AZURE_HTTP_USER_AGENT=VSTS_4ee44710-e935-4fab-969f-bd79343a4f6c_build_9_0
2024-10-14T23:51:53.7075108Z ##[debug]common.testresultsdirectory=C:\Users\Administrator\agent\_work\3\TestResults
2024-10-14T23:51:53.7075394Z ##[debug]agent.version=3.245.0
2024-10-14T23:51:53.7075677Z ##[debug]agent.ServerOMDirectory=C:\Users\Administrator\agent\externals\vstsom
2024-10-14T23:51:53.7075937Z ##[debug]agent.id=19
2024-10-14T23:51:53.7076183Z ##[debug]system.isazurevm=0
2024-10-14T23:51:53.7076456Z ##[debug]DistributedTask.Tasks.RetireAzureRMPowerShellModule=True
2024-10-14T23:51:53.7076727Z ##[debug]system.jobIdentifier=Build.Job1.__default
2024-10-14T23:51:53.7077010Z ##[debug]DistributedTask.Agent.LogTaskNameInUserAgent=True
2024-10-14T23:51:53.7077287Z ##[debug]DistributedTask.Agent.IgnoreVSTSTaskLib=True
2024-10-14T23:51:53.7077562Z ##[debug]DistributedTask.Agent.FailDeprecatedBuildTask=True
2024-10-14T23:51:53.7077834Z ##[debug]DistributedTask.Agent.EnableAdditionalMaskingRegexes=True
2024-10-14T23:51:53.7078128Z ##[debug]system.defaultworkingdirectory=C:\Users\Administrator\agent\_work\3\s
2024-10-14T23:51:53.7078406Z ##[debug]system.jobParallelismTag=Private
2024-10-14T23:51:53.7078675Z ##[debug]DistributedTask.Agent.UploadTimelineAttachmentsToBlob=False
2024-10-14T23:51:53.7078948Z ##[debug]agent.readOnlyVariables=true
2024-10-14T23:51:53.7079240Z ##[debug]build.repository.uri=https://anveshmuppeda@dev.azure.com/anveshmuppeda/anveshmuppeda/_git/IIS-Web-App
2024-10-14T23:51:53.7079520Z ##[debug]system.culture=en-US
2024-10-14T23:51:53.7079793Z ##[debug]build.repository.id=6ed174ab-26ce-4e23-9db7-680647b56385
2024-10-14T23:51:53.7080146Z ##[debug]DistributedTask.Tasks.Node.SkipDebugLogsWhenDebugModeOff=True
2024-10-14T23:51:53.7080548Z ##[debug]system.phaseDisplayName=
2024-10-14T23:51:53.7080804Z ##[debug]AZP_AGENT_LOG_TASKNAME_IN_USERAGENT=true
2024-10-14T23:51:53.7081079Z ##[debug]agent.taskRestrictionsEnforcementMode=Enabled
2024-10-14T23:51:53.7081358Z ##[debug]system.phaseId=572c5e49-83d5-5271-390a-e6dc77f89c6b
2024-10-14T23:51:53.7081615Z ##[debug]agent.osarchitecture=X64
2024-10-14T23:51:53.7081891Z ##[debug]agent.RootDirectory=C:\Users\Administrator\agent\_work
2024-10-14T23:51:53.7082166Z ##[debug]build.repository.clean=False
2024-10-14T23:51:53.7082426Z ##[debug]system.planId=6f89fef7-c4bf-4338-b3b8-23b073240cde
2024-10-14T23:51:53.7082697Z ##[debug]task.publishTelemetry=True
2024-10-14T23:51:53.7082949Z ##[debug]agent.jobname=Job
2024-10-14T23:51:53.7083190Z ##[debug]system.stageDisplayName=Build
2024-10-14T23:51:53.7083447Z ##[debug]resources.triggeringCategory=
2024-10-14T23:51:53.7083723Z ##[debug]pipeline.workspace=C:\Users\Administrator\agent\_work\3
2024-10-14T23:51:53.7084682Z ##[debug]Logging.LogLevel.Default=Warning
2024-10-14T23:51:53.7084985Z ##[debug]DistributedTask.Agent.UseWorkspaceId=True
2024-10-14T23:51:53.7085257Z ##[debug]system.taskInstanceName=FileTransform
2024-10-14T23:51:53.7085509Z ##[debug]build.buildNumber=20241014.16
2024-10-14T23:51:53.7085759Z ##[debug]system.phaseAttempt=1
2024-10-14T23:51:53.7086031Z ##[debug]VSTS_PROCESS_LOOKUP_ID=vsts_9d5c2fb7-1472-4b88-8eab-b1e72b56df05
2024-10-14T23:51:53.7086311Z ##[debug]DistributedTask.Agent.ForceUpdateToLatest2Version=False
2024-10-14T23:51:53.7086594Z ##[debug]AGENT_ENABLE_PIPELINEARTIFACT_LARGE_CHUNK_SIZE=true
2024-10-14T23:51:53.7086858Z ##[debug]GIT_TERMINAL_PROMPT=0
2024-10-14T23:51:53.7087102Z ##[debug]build.Repository.name=IIS-Web-App
2024-10-14T23:51:53.7087393Z ##[debug]MSDEPLOY_HTTP_USER_AGENT=VSTS_4ee44710-e935-4fab-969f-bd79343a4f6c_build_9_0
2024-10-14T23:51:53.7087676Z ##[debug]agent.cloudid=
2024-10-14T23:51:53.7087926Z ##[debug]DistributedTask.Agent.UseMsalLibrary=True
2024-10-14T23:51:53.7088276Z ##[debug]system.teamProject=anveshmuppeda
2024-10-14T23:51:53.7088549Z ##[debug]system.workfolder=C:\Users\Administrator\agent\_work
2024-10-14T23:51:53.7088837Z ##[debug]system.taskInstanceId=3ba22354-3d75-51a9-b444-fc920f181353
2024-10-14T23:51:53.7089108Z ##[debug]AZP_AGENT_MOUNT_WORKSPACE=true
2024-10-14T23:51:53.7089372Z ##[debug]AZP_AGENT_CHECK_FOR_TASK_DEPRECATION=true
2024-10-14T23:51:53.7089628Z ##[debug]system.jobAttempt=1
2024-10-14T23:51:53.7089882Z ##[debug]build.repository.git.submodulecheckout=False
2024-10-14T23:51:53.7090152Z ##[debug]system.definitionName=IIS-Website-Web-App
2024-10-14T23:51:53.7090416Z ##[debug]AZP_75787_ENABLE_NEW_LOGIC=false
2024-10-14T23:51:53.7090664Z ##[debug]system.isdockercontainer=0
2024-10-14T23:51:53.7090917Z ##[debug]system.definitionId=9
2024-10-14T23:51:53.7091191Z ##[debug]VSTSAGENT_CONTINUE_AFTER_CANCEL_PROCESSTREEKILL_ATTEMPT=true
2024-10-14T23:51:53.7111432Z ##[debug]system=build
2024-10-14T23:51:53.7111716Z ##[debug]system.debug=true
2024-10-14T23:51:53.7111990Z ##[debug]DistributedTask.Agent.UseFetchFilterInCheckoutTask=True
2024-10-14T23:51:53.7112242Z Initiated variable substitution in config file : C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config
2024-10-14T23:51:53.7112519Z ##[debug]Detecting file encoding using BOM
2024-10-14T23:51:53.7287660Z ##[debug]Unable to find node with tag 'applicationSettings' in provided xml file.
2024-10-14T23:51:53.7302023Z ##[debug]Unable to find node with tag 'appSettings' in provided xml file.
2024-10-14T23:51:53.7309864Z ##[debug]Unable to find node with tag 'connectionStrings' in provided xml file.
2024-10-14T23:51:53.7311468Z ##[debug]Unable to find node with tag 'configSections' in provided xml file.
2024-10-14T23:51:53.7343656Z Skipped Updating file: C:\Users\Administrator\agent\_work\3\a\Release\WebApplication1\web.config
2024-10-14T23:51:53.7345804Z XML variable substitution applied successfully.
2024-10-14T23:51:53.7359643Z ##[section]Finishing: Apply File Transformations on web.config
