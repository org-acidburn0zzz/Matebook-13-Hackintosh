First open core version for our matebook 13

*i have very little time to work on this project because of my work and my exams, but thanks to the help provided by the guys in our awesome group, we've now have a pretty stable opencore version*




Just put EFI folder in EFI partition.
Deleting clover footprint by following this guide https://github.com/dortania/OpenCore-Desktop-Guide/tree/master/clover-conversion

**Try this only if you have an usb with bootloader, or system backup to enter system in case of EFI corruption**
 <details>
<summary>Changelog</summary>
 06/06/2020
- Fixed brigthness keys(thanks to Kitsu Liu)
- Fixed logo ridimensioning during boot
  
 </details>
Improvements
<details>
<summary>Fix alt and ctrl inverted</summary>

> Go in settings>keyboard and click on "Modifier keys", invert options and command key. Voila!
</details>

<details>
<summary>Enable HIDPI (Many thanks to Xzhih)</summary>
  
> 1 -  bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"

> 2 -  Select 1 Enable HIDPI

> 3 -  Select 3 MacBook Pro

> 4 -  Select 6 Manual input resolution and insert: 2160x1440 1920x1280 1600x1066 1280x854 1080x720
</details>