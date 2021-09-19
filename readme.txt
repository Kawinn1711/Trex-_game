/*
* © 2020-2021 Jeb2Six All Rights Reserved
* 
* Easy to use Keyboard(WASD) to XInput(XBox 360 controller) conversion software
* Have analog movement in games with your normal keyboard!
*
*
* Release notes 1.0.3:
* Added ability to change the Alt+0, but it is still confined to using the Alt key + another key. Change this in the .ini file "hotkey = 0x30" 0x30 = 0, 0x31 = 1 using Microsofts virtual key codes: https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes
* Added the ability to independently alter the "diagonal" momentum based on whether +forward or +backwards was applied. Previously direction applied with +forward and +backwards used the same value.
* process priority has been set to "above normal"
*
*
* Release notes 1.0.2:
* Upped the windows priority for the process because we want keystrokes to be processed immediately, always.
* Interaction with an already running old version has been improved to make sure the latest version loads.
* Added an SOCD option in the .ini file: 0=SIP and 1=Neutral (SIP is default) // to learn more see https://www.hitboxarcade.com/blogs/cross-up/what-is-an-socd
*
* 
* Setup:
*   - Download and install(if you haven't installed this already): https://github.com/ViGEm/ViGEmBus/releases
*       this will add a virtual device to your computer that allows us to emulate a XBox 360 controller.
*   - Start Keys2XInput from any folder
*
*   + If "block keys" is disabled, then your game may interpret a different input than the intended joystick input, this is because your game could be combining both joystick and keyboard inputs together
*   + A Global Hotkey ALT+'0' has been requested to Windows for the enable/disable functionality
*   + To use non-printable characters, for ex.: the arrow keys, you need to specify the hexadecimal representation for those keys in the .ini file
*     here is a link where you can get the value for each key: https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes
*			Common non-printable characters:
*			Lshift: 			0xA0
*			Lctrl:				0xA2
*			CAPSLOCK:			0x14
*			Tab:				0x09
*			Alt (Left Menu):		0xA4
*
* Games:
*    - Fortnite: change Fortnite's settings: "Lock input method as mouse" to 'on'
*/

Disclaimer:
This SOFTWARE PRODUCT is provided by THE PROVIDER "as is" and "with all faults." THE PROVIDER makes no representations or warranties of any kind concerning the safety, suitability, lack of viruses, inaccuracies, typographical errors, or other harmful components of this SOFTWARE PRODUCT. There are inherent dangers in the use of any software, and you are solely responsible for determining whether this SOFTWARE PRODUCT is compatible with your equipment and other software installed on your equipment. You are also solely responsible for the protection of your equipment and backup of your data, and THE PROVIDER will not be liable for any damages you may suffer in connection with using, modifying, or distributing this SOFTWARE PRODUCT.
