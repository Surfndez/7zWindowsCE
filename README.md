# 7zWindowsCE
Solution Files for Building Windows CE ARMv4i console from source code

Prerequisites for building your own binary:

Visual Studio 2008 Pro ( https://archive.org/details/en_visual_studio_2008_professional_x86_dvd_x14-26326 )

Visual Studio 2008 Pro SP1 ( https://www.microsoft.com/en-us/download/details.aspx?id=13276 )

Windows CE 5.0: Standard Software Development Kit (SDK) ( https://www.microsoft.com/en-us/download/details.aspx?id=17310 )

7-Zip Source code ( https://www.7-zip.org/download.html I used https://www.7-zip.org/a/7z1900-src.7z )

Download 7z-AloneProjectFiles.zip and copy the Alone.vcproj and Alone7z.sln to 7z1900-src\CPP\7zip\Bundles\Alone7z to open the sln and build the solution. Upon sucess you can tweak the optimizations to your liking.
I've included my unicode supported 7zr-releaseU.small.exe binary in the release as well. I optimized for small code over speed.
