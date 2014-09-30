--------------------------------------------------------------------------------
patchLibv3 (c) 2010 atom0s [atom0s@live.com]
Readme.txt - Updated 11/03/2010

For support, questions, and forums please visit:
    http://67.210.99.128/patchlib/
--------------------------------------------------------------------------------

    Thank you for downloading patchLib, please take a moment to read through this ReadMe. 
    If you still need further assistance, please use the url above.

    ---------------------------------------
    Table of Contents
    ---------------------------------------
        I. Introduction
            o What is patchLib?
            o Credits
        II. Installation and Usage
            o Compiling Requirements
            o Runtime Requirements
            o Project Requirements
        III. Legal Information
            o Copyright
            o Misc. Information


--------------------------------------------------------------------------------
I. Introduction     o   What is patchLib?
--------------------------------------------------------------------------------

    patchLibv3 is a static library built using Visual Studio 2010 that is used
    to create a dynamic Gdi Gui driven application that can be both templated 
    using Xml or fully created during runtime. The purpose behind patchLib is 
    to mimic a program known as uPPP which creates patch files used for crack
    or keygen style applications.
    
    uPPP is created by ufo-pu55y from Seek'n Destroy (SnD).


--------------------------------------------------------------------------------
I. Introduction     o   Credits
--------------------------------------------------------------------------------

    A full listing of credits can be viewed on the website:
    http://67.210.99.128/patchlib/

    Many thanks to all of those whom have contributed to this project.
    
--------------------------------------------------------------------------------
II. Installation and Usage     o   Compiling Requirements
--------------------------------------------------------------------------------

    o Visual Studio 2010 - http://www.microsoft.com/
        patchLibv3 is built using VS2010. It may compile under different, previous,
        versions, but I will not support anything under 2010. patchLibv3 is only
        officially tested using VS2010.

    o Boost - http://www.boost.org
        patchLibv3 has been rewritten using a few new resources. The main new
        resource being Boost. Boost is required in order to compile and use
        patchLibv3, and future versions of patchLib.
   
        You do not need to compile any parts of Boost though, you simply need
        the headers. patchLib only uses header based parts of Boost.
   
    o alphaBlend, pngLib, tinyXML, uFMOD
        All three of these are required to compile and use patchLib as well.
        These are included with the patchLib package for your convinence and
        are already compiled and ready to be used. You should not need to alter
        any settings for these to be used properly.


    o Lua 5.1 - http://www.lua.org [Optional]
    o Luabind - http://www.rasterbar.com/products/luabind.html [Optional]
        Lua and Luabind are optional depending on if you compile patchLib to use
        the Lua script engine. If Lua is enabled, Luabind is required as well.
        
        Because the default test package uses some customizations, a custom Lua
        package can be obtained from the patchLib site which contains all the
        alterations done to the Lua package.
        
        
--------------------------------------------------------------------------------
II. Installation and Usage     o   Runtime Requirements
--------------------------------------------------------------------------------

    o Windows XP, Vista, 7
    
        Because patchLib makes use of Gdi and layered windows, versions of
        Windows below Windows 2000 are not able to use patchLib. Also, due
        to Microsoft dropping support for Win2k a few years back, the only
        valid and support versions of Windows are:
            o Windows XP w/SP3
            o Windows Vista
            o Windows 7
            
        patchLibv3 was developed and fully tested on Windows 7 Ultimate.
        

--------------------------------------------------------------------------------
II. Installation and Usage     o   Project Requirements
--------------------------------------------------------------------------------

    patchLib has been reworked to help ensure outside projects do not need
    any of the .lib files to be compiled into them in order to work properly.
    
    The only lib file that is required to be added is patchLibv3.lib
    
    Other then this, you are only required to include the header files that
    are used by your project.
    
    For a very slim project, you should only need patchLib.h

--------------------------------------------------------------------------------
III. Legal Information      o   Copyright
--------------------------------------------------------------------------------

	patchLib is free software: you can redistribute it and/or modify
	it under the terms of the GNU Lesser General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.

	patchLib is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU Lesser General Public License for more details.

	You should have received a copy of the GNU Lesser General Public License
	along with patchLib.  If not, see <http://www.gnu.org/licenses/>.

--------------------------------------------------------------------------------
III. Legal Information      o   Misc. Information
--------------------------------------------------------------------------------

    I, atom0s, am not responsible for what you make with patchLib. Any
    illegal software is not permitted. You are fully responsible for
    anything you use patchLib with. 
    
    If you do not agree to this, you are not welcome to use patchLib.
    