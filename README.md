# B460M-HD-Gaming-OC-EFI

# PC Configuration
<b>CPU :</b> Intel Core i5 10400<br/>
<b>GPU :</b> Intel UHD 630<br/>
<b>RAM :</b> 24GB<br/>
<b>Motherboard:</b> Gigabyte B460M Gaming HD<br/>
<b>WIFI:</b> TP Link USB Wifi TP Link WN725N<br/>
<b>Bluetooth:</b> TP-Link USB UB400 <br/>

# Change the default boot option to window
<ol>
  <li> make sure you have MISC -> Security -> AllowSetDefault -> True </li>
<li> on that boot selector screen, move your arrow to Windows and hit ctrl+return (next time when you boot that will be default)</li>
</ol>
https://www.reddit.com/r/hackintosh/comments/lc4ooz/anyonw_know_how_to_change_the_default_boot_option/



# Change the background Image in OpenCanopy (Open Core 0.6.6)

<ol>
    <li>Follow this to turn on OpenCanopy.</li>
    <li>You need a really big image! It seems this follows the same rules as any retina image, so you need an image double your resolution. I'm using an old 23-inch Cinema Display which is 1920x1200 so I need 3840x2400. It needs to be a png, name it Background.png, or as I am using the Modern Icons, ModernBackground.png</li>
  <li>Get <a href="https://github.com/chris1111/Icnspack-Builder"> chris1111/Icnspack-Builder </a> and install and launch</li>
    <li>Click run. Drop your image on Icnspack-Builder. Click ready. Click save and save it somewhere.</li>
    <li>You should now have a resources.zip folder. Unzip that thing!</li>
  <li>Inside the folder should be Background.icns, put that into EFI/OC/Resources/Image </li>
  <li>Reboot and make sure it works</li>
</ol>

# Custom icon builder for Open core 
https://github.com/chris1111/Icnspack-Builder
