# Magic Mirror
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

<!---You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:-->

<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Ammar S. | Dublin High School | Mechanical Engineering | Incoming Junior

<!--- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.** -->

<img src="Headshot.png" width="248" height="330.75" />

  
# Final Milestone

<!--- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<!--- <iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

<!--- For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE -->



# Second Milestone

<!--- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<!--- <iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BnCfWkVadUs?si=U_ZmSntP_oZweoud" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!--- For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone -->
My second milestone mainly consisted of planning out the final build and attaching the display and Raspberry Pi to the cardboard backboard. I am very surprised by how fast things are moving along in my project- I completed my first milestone yesterday morning and am already done with my second. After finalizing the calendar and weather modules, I was able to swiftly finish all the OS related issues right before my original SD card broke, which contained all the code I was working on. However, in just a few hours, I was able to recover all my progress and continue the building process of my Smart Mirror. I am now waiting on a 3D printed part that will allow me to do the final assembly of the Smart Mirror, and still allowing me to access the Raspberry Pi to add any software modifications before my final milestone.
# First Milestone

<!--- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<!--- <iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LYNAZDGK9Ak?si=VZCwPjNqCTDcz1XT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!--- For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project -->
For my first milestone, I planned to get MagicMirror OS up and running and modify some of the modules to integrate into my life. For the physical project, I have a one-way mirror which a small screen will sit behind, allowing the modules to be visible while still being able to use the object as a mirror. The MagicMirror OS is running with a Raspberry Pi 4, which also allows me to easily customize, edit, and add anything I want using the Linux based Raspbian OS. Later on in the building process, I have plans to mount the Raspberry Pi to the back of the display using a removable yet secure method. So far, I have been able to install MagicMirror OS onto the Raspberry Pi and configure the different pre-installed modules. I added my iCloud account to the calendar module using vdirsyncer, a calendar syncing software, which allows my iCal (Apple Calendar) to sync to the MagicMirror calendar module on it's own. For the weather module, I used OpenWeatherMap's free account to create an API key, which is a unique code that allows an application to identify a user from an external software. I then found the location ID for my city and added it to the code, allowing the weather module to get the weather forecast for my location. Both the weather and calendar modules took a long time to configure, however I ended up being able to get it to work at the end through trial and error. Since the OS is fully configured to my liking, I will start to work on the frame for the mirror and attaching the components to the frame.

# Schematics 
<!--- Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. -->
<img src="Schem1.png" width="489" height="302" />
<img src="Schem2.png" width="489" height="302" />
<img src="Schem3.png" width="489" height="302" />
<img src="Schem4.png" width="489" height="302" />

# Code
<!--- Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
``` -->

# Bill of Materials
<!--- Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| CanaKit Raspberry Pi 4 4GB Starter PRO Kit | What the item is used for | $139.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| 15.6'' FHD IPS Portable Monitor | Display for the Raspberry Pi, allowing the MagicMirror OS to be visible | $81.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| "Anker New Nylon USB C to USB C Cable (6ft 60W, 2-Pack)" | Cables to power the Raspberry Pi 4 and Display | $10.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Nekmit Dual Port USB C Wall Charger, 40W PD | Power brick for the 2 USB-C cables | $26.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Starter Project ~ Calculator

<iframe width="560" height="315" src="https://www.youtube.com/embed/11uO045UJXM?si=Js6uuijvQxL4Y_IX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

When creating my starter project, I was able to explore the functions of switches, panels, microcontrollers, and batteries and how all of them could interact to create something. Through this project, I was able to learn soldering, which is melting some metal (solder) using a hot rod (soldering iron) to create conductive connections, and effective troubleshooting methods to solve problems that I may also encounter when creating my main project. When creating my calculator, one part of the 7-segment display was not lighting up as expected. After trying to resolder some connections and messing with the display pins, I found that a metal adapter was missing from the microcontroller board. I fixed this by taking some copper wire and solder to create my own adapter, which ended up working. While soldering, the soldering iron wasn't getting hot at the tip, which made soldering some of the pins closer together much harder than expected. Using the helping hands, a tool to help hold up boards and other components at any angle while working on them, I was able to slightly heat up the pins of the components allowing the solder to melt easier.
