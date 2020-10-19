## Getting Started:


###### Description
 
 Serena Dimensions CM is a process-based software change & configuration management product that can cost-effectively eliminate the complexity of parallel development, seamlessly integrating and automating development practices through change and branch visualization, minimizing conflicts and improving team velocity while eliminating risk and assuring a high degree of release readiness.

 The actions execute the most commonly used or required DMCLI commands.

 Note, that not every single argument option is provided as doing so could make the actions cumbersome. Where an explicit argument option is not provided, these can always be passed via plain text in 'Optional arguments'.

###### Actions
 
1. Action Request - AC
2. Action Request Items - ACDI
3. SAdd Reqest Items to Project - ACDWS
4. Add Item Revision to Project - AIWS
5. Browse Request - BC
6. Create Request - CC
7. Create Stream - CS
8. Deliver to a Stream - DELIVER
9. Delete Steam - DS
10. Extract Request Items - ECDI
11. Extract Item - EI
12. Fetch Baseline Items - FBI
13. Fetch Request Items - FCDI
14. Fetch Item - FI
15. Fetch Project Items - FWI
16. Generic Command
17. List Projects - LWS
18. Move Project/Stream Directory - MWSD
19. Return Item - RI
20. Remove Item Revision from Project - RIWS
21. Report Requests - RPT
22. Update Project/Stream Attributes - UWA


###### Prerequisite:

1. Automation Engine should be installed.
2. Automic Package Manager should be installed.
3. ITPA Shared Action Pack should be installed. 

###### Steps to install action pack source code:

1. Clone the code to your machine.
2. Go to the package directory.
3. Run the command apm upload in the directory which contains package.yml (source/):
Ex. **apm upload -force -u <Name>/<Department> -c <Client-id> -H <Host> -pw <Password> -S AUTOMIC -y -ia -ru**

###### Package/Action Documentation

Please refer to the link for [package documentation](source/ae/DOCUMENTATION/PCK.AUTOMIC_DIMENSIONS.PUB.DOC.xml)


###### Useful References

1. [About Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_AboutPacksandPlugins.htm?Highlight=Action%20packs)
2. [Working with Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_WorkingWith.htm#link10)
3. [Actions and Action Packs](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#_Common/ReleaseHighlights/RH_Plugin_PackageManager.htm?Highlight=Action%20packs)
4. [PACKS Compatibility Mode](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#AWA/Variables/UC_CLIENT_SETTINGS/UC_CLIENT_PACKS_COMPATIBILITY_MODE.htm?Highlight=Action%20packs)
5. [Working with actions](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/AB_WorkingWith.htm#link4)
6. [Installing and Configuring the Action Builder](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/install_configure_plugins_AB.htm?Highlight=Action%20packs)

###### Distribution: 

In the distribution process, we can download the existing or updated action package from the Automation Engine by using the apm build command.
Example: **apm build -y -H AE_HOST -c 106 -u TEST/TEST -pw password -d /directory/ -o zip -v action_pack_name**
			
			
###### Copyright and License: 

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)
