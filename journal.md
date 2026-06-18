# la journale
>  17 38. ay. <br/>

this is the journal for my pendant submission! projects are due tomorrow so dev logs are gonna b pretty packed <br/>
* my submission is based on the [Arcane Potion](https://official-defend-the-statue.fandom.com/wiki/Class_Potions#Arcane_Potion) from [Defend The Statue: Nostalgic Proctors](https://www.roblox.com/games/6911596531/Defend-the-Statue), a roblox game i have way too much hours in lmao

### started: 6/17/26

## 6/17/26 - comin up with ideas, drawing outlines
today i came up with some ideas for pendant <br/>
there's not that much criteria for pendant other than making it look pretty and being under 4 inches, so i started comin up with some ideas: <br/>
<img width="1049" height="585" alt="image" src="https://github.com/user-attachments/assets/39d4bbf8-0e10-4fc0-a253-833d2b592c11" /> <br/>
in the end i decided to do the fluid simulation idea with the arcane potion <br/>
* i feel like doing a fluid simulation with a more unusual shape like the star would be interesting + defend the statue was and is still now one of my fav games on roblox <br/>
* i also wanna experiment with different pcb colors other than my usual black and white silkscreen

after getting my idea sorted, i started work on my outline
* i chose figma to do this since ion really know any other vector drawing software other than like illustrator (in which my school booted my license) <br/>
<img width="815" height="640" alt="image" src="https://github.com/user-attachments/assets/dcdeee51-e2f6-4586-9c0f-3bd6d17677b4" /> <br/>
the corners of the star are supposed to be sharper tbh but im planning to make the case for it wrap and sandwich the pcb around it so

### hours spent: 1.5 hours

## 6/18/26 (part 1) - coming up with general layout, schematic work
i should've came up with my layout before making my layout but whatever <br/>
anyways back to the excalidraw mines <br/>
<img width="690" height="515" alt="image" src="https://github.com/user-attachments/assets/068462b6-9ea5-46ef-8595-530d21efac84" /> <br/>
thankfully i have a bunch of mpu6050 sensors from a project i planned to do but never did so i dont have to order those <br/>
after that, i went onto kicad to make my schematic <br/>
<img width="1112" height="633" alt="image" src="https://github.com/user-attachments/assets/71fd2962-6234-4245-82ae-f03c7d1bd393" />
* i initially wanted to recreate an led matrix for my pendant, but after digging around and finding the [adafruit schematic for their neopixel matrix](https://github.com/adafruit/Adafruit-NeoPixel-8x8-Matrix/blob/master/Adafruit_NeoMatrix_8x8%20v2.sch), i realized that its quite literally just the same type of config i've been using for my rgb lights but with extra capacitors and a resistor lmao <br/>
* i also tossed in a slide power switch so that i dont burn all of my battery when i permanently solder my board together. i initially thought i was gonna have to buy new slide switches, but i found one lying around in my stash of electronic parts
* i wired up the accelerometer according to this [handy article](https://lastminuteengineers.com/mpu6050-accel-gyro-arduino-tutorial/#mpu6050-module-pinout) by last minute engineers (idk what else to say)

### hours spent: 2 hours






