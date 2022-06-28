# X250_T450_Hackintosh_EFI_Complete_version (OpenCore072)
This is an EFI project for Thinkpad X250, T450 Hackintosh, based on [CLAY-BIOS
/Lenovo-ThinkPad-T450s-Hackintosh-OpenCore] and the intel wireless drivers and bluetooth drivers were alredy ootb

#What works[TESTED]:
(Almost Everything)
Intel AC-7265 Dual Band + Bluetooth Module (*Bluetooth switch patched)
Intel HD 5500 Graphics
trackpad, trackpoint
Complete ACPI Supports(*including complete power managements functions)
Sound Card Module
audio speaker/mic
etc

FIXED comparing to CLAY-BIOS:
*(1)Fixed Bluetooth Switches:

![image](https://user-images.githubusercontent.com/100339054/176080062-664111a0-0a2a-49a0-97e6-54e3fa1d5ca7.png)


*(2):Bluetooth, Wlan ootb (preinstalled):

![image](https://user-images.githubusercontent.com/100339054/176080436-3888dda8-86df-4540-9aa5-81bbfb71c77f.png)

*(3):With Proper Graphics (driver)indetify(Fixed in newer version in CLAY_BIOS):

![image](https://user-images.githubusercontent.com/100339054/176080642-bb04377b-342e-4978-afab-c377544dc0be.png)

*(4)The function issue about cant wake up after closing the lid for a while(when it went into sleeping status)

IN ORDER TO MAKE THIS FUNCTION WORK; Please CHECK your bios settings and please make sure its exactly the same，you can find my configuration in the /BIOS-CONF File (bios_configuration pics are from https://github.com/exxncss/x250-hackintosh)

#How to install:
1:mount your EFI(ESP) partition

2:delete the old EFI file(if there is one)

3:paste the /X250_T450_Hackinstosh_EFI/EFI folder into the EFI(ESP) [root directory]

4:reboot

5:There you go~

#EVERYONE‘S WELCOMED TO TEST THIS OUT!

#X250 BigSur TESTED; Worked perfectly fine
