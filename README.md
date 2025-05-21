clone of https://sourceforge.net/projects/eidauthenticate/

Changes added by @andrysky to start dropping XP support

Using msbuild, the solution builds without WIX but needs the Cryptographic Provider Development Kit https://www.microsoft.com/en-us/download/details.aspx?id=30688

Build by installing Build Tools for Visual Studio https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2022  

This link provides information on how to start linking VSCode and old Visual Stuido 2022 projects.

Tasks:
- [ ] test the code and see if it works.
- [ ] move to a build system that works better with VSCode
- [ ] Finish removing XP support.
