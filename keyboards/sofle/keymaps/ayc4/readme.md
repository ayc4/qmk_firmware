Keyboard: Sofle v1
Layout: Standard US layout (Capslock replaced by tilde)

> make sofle:ayc4

**WARNING:**
This may somewhat brick your slave side controller by making it harder to reset.  
I use a V4 Elite-C on the master side and a Pro-Micro on the slave side.  
The firmware currently on my slave board came from modifying the default layout  
on the qmk.fm online configurator so I cannot verify if this will cause the same issues.

Changes:
* Removed colemak layer
* Removed functions related to aforementioned colemak layer
* Reverted base layer to a more traditional layout
* Slave side encoder now toggles secondary layer when pressed
* Master screen is now revised to show:
  - Numeric/Caps/Scroll lock status
  - Current active layer
  - Raw typing speed in WPM

 Special thanks to @j-inc for the original WPM implementation

<img src="https://cdn.discordapp.com/attachments/242588884138065920/750738226108563526/IMG_8354.jpg" width="378" height="504">
