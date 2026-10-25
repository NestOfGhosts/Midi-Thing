# Midi-Thing
Basic midi device, also can be played live with headphones

<img width="1365" height="851" alt="image" src="https://github.com/user-attachments/assets/506c84e9-0112-40d2-9ee6-9b5eff4df67b" />

## BOM
|Item                    |Qty|Supplier|Cost/item|Total Cost|link                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|------------------------|---|--------|---------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Switches                |50 |Amazon  |$0.08    |$4.00     |https://www.amazon.ca/gp/product/B0GVSBNSHM?smid=&psc=1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|Keycaps                 |24 |Amazon  |$0.41    |$9.84     |https://www.amazon.ca/Mechkeeb-Profile-Switches-Keyboard-Replacement/dp/B0BWDTBF1L?crid=17D24DACDDXK7&dib=eyJ2IjoiMSJ9.QgzrbHYNnySbWz_C8JOt7rSGQp54UpmJIuUW7RZGzSMhlxsqRpD4ByujW6NLF5VClUPdJ7uM4nQ8F1Wo1ICEtZLIsUh5DFbeM6mQrp3peg8PTgZnUxkqFvN2t2KJmAUsvgxP33V13MaYIHIlzXmSsfT07KRJhDBgixe5str7y4PYlFrjQzKIyweJUwUIdNhgg6qZyp8ZMlW65B0i-uvvX06MY4sBke1bJfpvTXwIA8cM7RHbJqhZMl9JY1I73jYi5AkKh6-AJLnbDJc98ZBc_Pu7R-gI93cZwj5XZ4giP6E.ocRhOoAWpWF7jiiZ7ZU1jz1r0Lgcl5A6FctMVWPJO_U&dib_tag=se&keywords=10%2Bpack%2Bkeycaps&qid=1792860838&refinements=p_76%3A3276484011&rnid=3276483011&rps=1&s=electronics&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=10%2Bpack%2Bkeycaps%2Celectronics%2C151&sr=1-12&th=1|
|Round Potentiometer     |1  |Mouser  |$4.53    |$4.53     |https://www.mouser.ca/en/ProductDetail/Alpha-Taiwan/RD901F-40-15R1-B100K-00DL1?qs=1mbolxNpo8czbLgndpJJVQ%3D%3D                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|Long Potentiometer      |1  |Mouser  |$2.13    |$2.13     |https://www.mouser.ca/en/ProductDetail/652-PTA3432010CIB103                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|Teensy 4.0              |1  |Amazon  |$27.22   |$27.22    |https://www.amazon.ca/gp/product/B07W5J3WNH?smid=A33HV3N1GS7LPU&psc=1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|Audio shield for Teensy |1  |Amazon  |$17.37   |$17.37    |https://www.amazon.ca/gp/product/B07Z6NW913?smid=A33HV3N1GS7LPU&psc=1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|PCB                     |5  |JLCPCB  |$2.06    |$10.30    |https://jlcpcb.com                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|Estimated total shipping|1  |        |         |$42.68    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
- PCB: use [the production files](https://github.com/NestOfGhosts/Midi-Thing/blob/main/Pcb%20Production/production.zip) and a pcb printing service like [JLCPCB](https://jlcpcb.com/) to get.

- Switches and caps: use whatever as long as is cherry mx 5 pin compatible

## Assembly 

- Enter the teensy's bootloader mode by pressing the button. You can tell it works if the led turns off

<img width="640" height="436" alt="image" src="https://github.com/user-attachments/assets/bc6aae13-032d-4187-89ea-3a4641f19eec" />

- Load the firmware .hex using the [Teensy Loader](https://www.pjrc.com/teensy/loader.html) (found in [midee](https://github.com/NestOfGhosts/Midee))

- Solder the teensy onto the shield, and the shield to the pcb (using the header pins).

Placeholder ADD IMAGE

- Solder the keys, and the pots

ADD images

- Attach the caps and stuff

Add more images

Should work now. I dunno dude rn im not done coding yet so i dunno exact process.

## Optional stuff

- Modify the code by copying [midee](https://github.com/NestOfGhosts/Midee) and recompiling with platformIO

- Print the [holder](https://github.com/NestOfGhosts/Midi-Thing/tree/main/holder)

<img width="456" height="438" alt="image" src="https://github.com/user-attachments/assets/18de0cf4-65b1-4d27-8844-a664cd2122fc" />


