# Personal QMK CorneKeyboard Layout
 
 This is my personal QMK config file and keymap oriented to developers in Mac OS. I included a PDF version of the layout, useful for having a printed referece.

## Required Knowledge

QMK = The keyword [Firmware.](https://qmk.fm/) (it would be a good idea if you get familiarize with it first)

TapDance =  you can have keys do something different depending on the amount of times you press it. In This layout i have only 1 tapDance key on Layer 0.

## Installation Process

****Install QMK first, link above***

Clone the repo after installing QMK
```
cd qmk-firmware/keyboards/crkbd/keymaps && git clone https://github.com/rcuevaspantoja/personal-cornekeyboard-layout.git rodolfocuevas

```

Configure QMK
```
qmk config user.keyboard=crkbd/rev1 && qmk config user.keymap=rodolfocuevas
```

Compile
```
qmk compile
```

Final Step
Now you created a file that you need to flash it on EACH keyboard (2). For this you can use an app called [QMK ToolBox](https://github.com/qmk/qmk_toolbox) . Easy as open it, select the file created and flash each piece. After that the keyboard will ready to use.

If you need any help at any step feel free to contact me on [email](https://rodolfocuevas.com) or [Instagram](https://www.instagram.com/rudd.dev)

## Layout

![CKBDLayout](/diagrams/QMK%20Configurator_pages-to-jpg-0001.jpg)
![CKBDLayout](/diagrams/QMK%20Configurator_pages-to-jpg-0002.jpg)

