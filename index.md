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
| CanaKit Raspberry Pi 4 4GB Starter PRO Kit | Running, processing, and controlling MagicMirror OS | $139.99 | <a href="https://www.amazon.com/CanaKit-Raspberry-4GB-Starter-Kit/dp/B07V5JTMV9/ref=sr_1_3?crid=1YL03XF51I6SD&dib=eyJ2IjoiMSJ9.4tX4qJd4-AxDDD69js_G-neZZayZnLPkOAoMKlA68Ex_k5w7ncQWqkgdh65x4T130CTlsRsEOWcJQJ5TBn8QZuEinB1Q_wrw26rm_gi1B8CwcqJ_ZszCHhL9UxActIa-1DUkDkvjAhMCPASLEDe7F2n_Rjb5vk6E5wAS8dcUXnVU-Oves62PyW_SzXHflBbLGT6w_I0iPc9yslfIdRMCjqBfYzwmnquSeQBnsOG66EI.2syIQEXkDMj28bUQ7cm2Yzya6HENDkbXZCSfgqqw_JY&dib_tag=se&keywords=canakit%2Braspberry%2Bpi%2B4%2Bpro%2Bstarter%2Bkit&qid=1720490000&sprefix=canakit%2Braspberry%2Bpi%2B4%2Bpro%2Bstrater%2Bkit%2Caps%2C135&sr=8-3&th=1"> Link </a> |
| 15.6'' FHD IPS Portable Monitor | Display for the Raspberry Pi, allowing the MagicMirror OS to be visible | $81.99 | <a href="https://www.amazon.com/Ingnok-15-6-FHD-Portable-Monitor/dp/B0CP7XRW9S/ref=sr_1_1_sspa?crid=2EZFSJU4EG811&dib=eyJ2IjoiMSJ9.KQEIPfIoRG5gQIylWvCL_B_YvetHYFlSZWqUypU0huFmpmMzKkkWo41Lc_IQrFVjqq7SBrMk7tHzlTYCEQd3Ms-bgfs91vonTM2d2ll4nVcEMJ2d17mLoXT6QKFn_tsZ0gsCXaDr2nsM67hD7mC3ROhMhL9P__CCFy0MUtw5yc5vRW6QNQkarOy-hgUXK7xlM3GZR2ZSFQYf_sRyPHBeR8S7GPk-pTj4kia8VkhHTlk.0QKZCsNeL-X37HjfA4_EpfTenncpFn6vMTmGHlIiO3k&dib_tag=se&keywords=ingnok%2Bportable%2Bmonitor%2B15.6&qid=1720490229&sprefix=Ingnok%2B%2Caps%2C208&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| Anker New Nylon USB C to USB C Cable (6ft 60W, 2-Pack) | Cables to power the Raspberry Pi 4 and Display | $10.99 | <a href="https://www.amazon.com/dp/B088N7KPZN/ref=twister_B0D2DK8YP3?th=1"> Link </a> |
| Nekmit Dual Port USB C Wall Charger, 40W PD | Power brick for the 2 USB-C cables | $26.99 | <a href="https://www.amazon.com/Nekmit-Charger-Charging-Adapter-MacBook/dp/B0BRMR4HCZ/ref=sr_1_12?crid=3LISJP0DQ00EU&dib=eyJ2IjoiMSJ9.P_mbD3pMIXTJBeI-ZP9-zQwDT9fpYsPrPz_553-NDdzutM7N0ZzSTI5FxZw3jBtwQU_B-vfo6APBjnl4-lAhMtuRI4oGGpvD8IuTIgcjQorIZvwyFH-wryUcDFdNs8eRGlJRfmvA8gXwploZk27xRfvVkreAaLkL53MuMbcMrzyXDC5IwIsOcEy7DdnAwqEnXg0sksKlBBklk8xJ66yBMn1z7ozKm1XMskxVml1327DEoQk1N7fDb4zgsUZd8eMv7EtXKxX3E_CZr8xXRkSW5n8SXApIL8rQqjtPgkoc3yM._J8h3qkufHsekb4Ov90Rzqvth-30jTn2Kkv3VRGBDGU&dib_tag=se&keywords=dual%2Busb%2Bc&qid=1719590221&s=industrial&sprefix=dual%2Busb%2Bc%2Bcha%2Cindustrial%2C603&sr=1-12&th=1"> Link </a> |
| 12x18 Picture Frame (2-pack) | External frame for the MagicMirror | $22.59 | <a href="https://www.amazon.com/Americanflat-12x18-Picture-Frame-Black/dp/B0BPN4YQCC/ref=sr_1_3_sspa?crid=2NOOHPTHF5NF1&dib=eyJ2IjoiMSJ9.gZJfT0xHiVic7nvFJ1IUroZhzbQ5ZK9xrJEvaVXYmbmEZaDIBcp5_itXosxfJu_n2c0Q2_IaNQKSSHuBFYF5816p-6vGvvrO3zid8Pl35eRjLn99gIIXks0ccfzsHR9Q4yZjeCm92_PP2EQmWcz_zeoWXW9KWZdv9NnvpzqW5-i4cPwYVpYHATRECONejPe16Ge6bFESuuGxC-XHm4WuxniOTqRdI0n_b87csGeljdVpqPOwL62ummWHiiW7JiFOHYVHoi9thofwRzcFwPaoZgS3HGjR-9mIyLai5kBjfoY.M7DG2Kx5w1_f-8shJacfTg6MMrXlFixGGpDfO4HL_g4&dib_tag=se&keywords=12X18+frame&qid=1720538808&sprefix=12x18+frame%2Caps%2C147&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| Cardboard | Filler for empty space (can also be from boxes) | $4.39 | <a href="https://www.amazon.com/EcoSwift-Chipboard-Cardboard-Scrapbook-Sheets/dp/B0B29JMJL2/ref=sr_1_1?crid=292F89G0MLRCV&dib=eyJ2IjoiMSJ9.afk3XS5SGSrwEcCWLMftn_k-Yj9xaRhYgWvkQpnN3tOTDHE-G4au5dJCjNAWAq6N8X8DldmM59YJGt89VOsyLXe4whjecJsQoDOcbqhKNCJgI_jAgVk8ieZDOQbJ5T1OxPIBUqvbqsRZYHEhXxZD7jgApOuj6c4qy_vpd47FqXCih-lOuImmaOsbN1kMHWwI-aXIWP2HqFyW-rL5P07w3SEfL6A5d2S2ctKZ2HhYGCxZvfRZHXLA8Jjt6zzaLsK4XZaubjAD-Iu3Q7V5-ZPoqnbXQHrzQAQibW_sfgIPb78.qfHZkbh92MU09EUS9GWwZKFNDiejTvJ-tVwfhPzoClc&dib_tag=se&keywords=cardboard&qid=1720538442&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&sprefix=cardboard%2Caps%2C145&sr=8-1"> Link </a> |
| 24 Sheets Black Cardstock, 80lb | To fill area around the monitor | $8.99 | <a href="https://www.amazon.com/Cardstock-Goefun-Printer-Invitations-Scrapbooking/dp/B0BQ7JNBV5/ref=sr_1_1_sspa?crid=2NZ00MSXGOBUK&dib=eyJ2IjoiMSJ9.N37BD02Na4TZ0KziVcW_yBynBiOvDk4GyACfYNF4ynKAl1h4PnoqQ8lh0a3wRCkD1kA1zuZ6GDLJeXIp4o2BSW81wNkh3jb7UXql7iVxaq2pzOkgKtP6H6LPa5OxdXq4-f9g8HMmaPKoqQcS3PULUgEn864URPQi9etDGNiXUWcrAcTADca2FFuh0X2xHOKsDeugb6pREw3VZc4q2E5bFa28JKyub_2bW4F1o1NyhVWWJdOUhJw4F1m4Fhc8mOzrWCq_8Az2AgROCzGvCfpzpX_-vUxqBPMay643SQOiPYk.1_k2Oc5Ze0HiIIl8qGS_APZD-vgZqsC45IiNfZAV_O0&dib_tag=se&keywords=black%2Bpaper&qid=1720538620&sprefix=black%2Bpaper%2Caps%2C139&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| 12 x 18 x 0.04 Inch Acrylic See-Through Mirror | Mirrored acrylic for the MagicMirror | $29.99 | <a href="https://www.amazon.com/0-04-Acrylic-See-Through-Mirror-Transparent/dp/B07F7RT17K/ref=sr_1_2?crid=2G8WXOG2L1MB6&dib=eyJ2IjoiMSJ9.W-Njxz3W5aXZUmBzdZiQTdcXNAXcP0D7-FMn666i_swUsmbnrPrTi7K7WLsC0ghem8hpwv7OOGI14XVz4T3hXjnB93W10OpRObIpo4wwoSuiq96Drypla1BKVGzCphDJGEBV1Nco6-3p9QuitviJiNjD8QrcvHvwQnluo5m9wsQcmgvMn-EmWaqIFrvtVquprV6Df9Qu8-E36qYaGGJ_PydN-5DUngNe3RGXPlXH8xrb0oZvs2FoXbjaBzJbv2og3sQmkxIM0FZILPYhYKZFkxKcG82xoNTg187Qo7s4N2c.Ty-C3eL23pSSWmlrxQXItFkswULFSB_iIEMru87ckKs&dib_tag=se&keywords=12X18%2B1mm%2Bacrylic%2Bsee-through%2Bmirror&qid=1720538765&sprefix=12x18%2B1mm%2Bacrylic%2Bsee-through%2Bmirror%2Caps%2C125&sr=8-2&th=1"> Link </a> |
| Gorilla Heavy Duty Double Sided Mounting Tape | Assembling the MagicMirror | $12.24/roll | <a href="https://www.amazon.com/Gorilla-Heavy-Double-Sided-Mounting/dp/B082TQ3KB5/ref=sr_1_1_sspa?crid=3ECPY5NA68DEX&dib=eyJ2IjoiMSJ9.3qhDIMc72DmDSIjB7_8-042J7XwT3CfpWsdXD3u9BK_i97L9d3gu5F8qGLtnfM2KSgSMZWJ8alRB51OuIqg8TQFZuXh8wmz-fLNK1TSoexaM4O5UAxU3LBOJoJtUb3poUdichYUUZCy_oA8Rm93xEyLrHAulNo32HBXd0EzysB8PSlntDLTxFBBWJrtg1sqNOnvU7wJFyGCmOEmEQNI74CamS9aW108u7eQO6aMWynIbZWRnucrGr9ZRVPEjJDqh2S_i4j2AHBKUoRsSKJ-r03MavH06afmaufcbsM_LXdY.NvdSFD17wfZ-jLi7Pi1F5F2E-_3BjJ4MdIciCMUZy50&dib_tag=se&keywords=gorilla%2Bmounting%2Btape&qid=1720539095&sprefix=Gorilla%2Bmount%2Caps%2C144&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| Scotch Painter's Tape | Assembling the MagicMirror | $13.99/roll | <a href="https://www.amazon.com/ScotchBlue-Original-Multi-Surface-Painters-inches/dp/B00004Z4DU/ref=sr_1_5?crid=2V51BRBTTCGB6&dib=eyJ2IjoiMSJ9.TWyVW2Z5SRmjScpS793uYElaROfAg8zvl5GfbzIdbWDUUHc0FDJLUhRgWBsGdXX6M2nVBr_qRMbbFD9Zls-LZdsQBvHRitxfHweeQ9X4SNMp9iWuWro2l_WRZnxCUUGX2yPqcYAU_C8E4Obh5QpaEemzFrbWDn1-ag587sEDto5k8_67LbrIvP-BEAyqdJLtD_egRCUUklYAmVs7_OTCWFeN8cmncaBI2pLbJGQ9eQQTklWr4IoH_C6oR1hMSlF-v_2lLlk_KBhcDfMWIMQXBaXItC4h1YAix8J2mTyaWMI.tnNNDI0Rho4A8x3QzeT_WkuMjJjipKWfzPW5d6HVC90&dib_tag=se&keywords=scotch%2Bblue%2Btape&qid=1720539191&sprefix=scotch%2Bblue%2Btap%2Caps%2C149&sr=8-5&th=1"> Link </a> |

# Starter Project ~ Calculator

<iframe width="560" height="315" src="https://www.youtube.com/embed/11uO045UJXM?si=Js6uuijvQxL4Y_IX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

When creating my starter project, I was able to explore the functions of switches, panels, microcontrollers, and batteries and how all of them could interact to create something. Through this project, I was able to learn soldering, which is melting some metal (solder) using a hot rod (soldering iron) to create conductive connections, and effective troubleshooting methods to solve problems that I may also encounter when creating my main project. When creating my calculator, one part of the 7-segment display was not lighting up as expected. After trying to resolder some connections and messing with the display pins, I found that a metal adapter was missing from the microcontroller board. I fixed this by taking some copper wire and solder to create my own adapter, which ended up working. While soldering, the soldering iron wasn't getting hot at the tip, which made soldering some of the pins closer together much harder than expected. Using the helping hands, a tool to help hold up boards and other components at any angle while working on them, I was able to slightly heat up the pins of the components allowing the solder to melt easier.
