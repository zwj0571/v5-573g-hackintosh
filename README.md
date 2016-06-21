# v5-573g-hackintosh


what works:

  - Audio, the device is alc282. we use AppleAlc.kext to make my hackintosh "sing", the kext is placed in clover/kexts/10.11. With this kext, we do not need patch AppleHDA.kext any more or install dummyAudio.kext to SLE.
  - keyboard and touchpad, my touchpad is ELANTECH. if yours is SY, you may need modify dsdt. Hot key, such as Fn + -> or Fun + <- all work. we can use them to change audio volume, brightness
  - CPU, my model is i5 4200U. by using ssdt.aml,it works well. Turbo state has not beed tested yet.
  - Graphic, HD4400 works, nvidia 750M disabled. the graphic memory is extended to 2GB, graphic glich still exists when boot.
  - network work, not wifi device.
 
what not works:

  - wifi and bluetooth, I will change it to AR5B195. later I will update dsdt and config.list to make it work