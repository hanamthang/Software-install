# Install Libre office without Windows previlege 

1. Download and extract the .msi installation file into a folder
2. From a command prompt: dir *.msi
3. Run msiexec /a LibO_<version>_Win_x86_multi.msi
4. Select a local folder to install the new version of LO (C:\Users\hnt7\Documents\software\libreofice\71\)

# Error: LO can not find vcruntime140.dll and vcruntime140_1.dll
Copy vcruntime140.dll and vcruntime140_1.dll from C:\Windows\System32 to the installed folder of Libre Office and here you go.

# Original post: 
https://wiki.documentfoundation.org/Installing_in_parallel/Windows
