Copyright (c) Prolog Development Center SPb
PdcVipSolutions
Version 3.0

The PdcVipSolutions  - is the set of tools, examples, and projects as the additions to PDC Visual Prolog official product.
The current version is built by Vip version 902.

All content must be placed to one directory with the structure and  names as shown below
SpbRSolutions (the root directory may have any other name)
    SpbExamples (corresponds to SpbExamples in GitHub)
    SpbProjects (must be created)
        DelFiles (corresponds to DelFiles in GitHub)
        WS_Manager  (corresponds to WS_Manager in GitHub)
    SpbVipTools (corresponds to SpbVipTools in GitHub)
        SpbVipTools is the set of packages to support projects and examples and to demonstrate how it works.

Do not hesitate to ask via email victorYukhtenko@pdc.spb.su or victor.a.yukhtenko@gmail.com.

Version 3.0

The Version 3.0 content repeats version 2.0 and is extended by the Application Frame - a set of  project templates (also called AppFrame), which can serve as the basis for applications that 

    * have a client-server architecture in the form of FrontEnd and BackEnd, interacting either within a single mono-application or through HTTP
    * based on the use of the control panel (ribbon)

and have the following distinctive features:

    * control panel (ribbon)
          o can be described, including as an XML structure
          o can be easily expanded and customized
    * allows you to expand the functions of the application by connecting plug-ins made using the PZL technology (see VipPzlSystem )
    * use custom dictionaries for user interface elements, including to obtain multilingual applications
    * provides the possibility of both synchronous and asynchronous exchange of information between FrontEnd and BackEnd.

AppFrame templates are placed to the directory SpbVipTools\AppData\ProjectTemplates\Febe.
The AppFrameCookBook is accessible from here and also is placed as the WinHelp  SpbVipTools\Doc\AppFrame\AppFrameCookBookEn.chm.
The directory SpbExamples\Febe contains the example of the created set of projects.
The best way to compile all projects is to use the WorkSpaceManager.exe application placed at SpbVipTools\Bin directory and use the workspace data SpbVipTools\UserWS\DemoWorspace.wsm

Version 2.0

The main purpose of version 2.0 is the demonstration of the WorkSpace Manager Tool.

Version 2.0 contains the executables and source codes of applications.

The executables of applications are placed at SpbRSolutions/SpbVipTools/Bin.
The documentation for the WorksSpace Manager placed at SpbRSolutions/Bin/wsmAppData, where you can find
    ReadMe(En/Ru).pdf - the instruction how to build and run applications
    WorkSpaceManager(En/Ru).pdf - the general Info regarding the tool
    wsm_help(En/Ru).chm    -  the standard MS Help, which also may be called from the WorkSpaceManager.exe application.

WorkSpaceManager also is represented as the integration of http-based backend and http-based frontend. This is the first step toward the applications based on the microservice ideas.
    It has NO multy-user functionality supported.
    It has NO reaction on the not started backend.
The main purp[ose was to get the list of tasks to be solved in the future.

The examples, which are included to the versionj 2.0, was built many years ago. They have updated just to feet the VIP9x status.




