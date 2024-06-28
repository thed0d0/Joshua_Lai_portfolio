# HEXAPOD ROBOT OF DOOM
<!--Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:-->

<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Joshua L. | The King's Academy | Mechanical Engineering | Rising Junior

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**-->

<img src="Joshua_L.JPG" width="756" height="1008">
  
# Final Milestone (June 25th, 2024)

<iframe width="560" height="315" src="https://www.youtube.com/embed/6z4TW805CYg?si=IorbK040iQL3y76S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!--

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE


-->
# Second Milestone (June 20th, 2024)
**Assemble and attatch legs, calibrate legs**
<!--
**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**
-->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ff6MvHW-BKg?si=la6IosAkhYMUmGY9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

  Since the first milestone, I've attatched the servos to the acrylic frame, assembled the legs, wired in the servos, calibrated the legs, added the given and extra cable management, and installed the WLAN module. Now, the hexapod is capable of fully cordinated walking and body manipulation. Using wifi to controll the hexapod, I can controll the X Y movement, rotation on a vertical axis, Z elevation movement, X Y location of the central body in relation to the contact points of the legs, and the roll and pitch of the central body. All the servos that are used to preform these movements are connected to pins on the bottom side of the controller and using given cord wraps and additional zipties I secured the extra wire from the servos to avoid any obstruction during movement. My previous assumption that the self tapping screws would be a pain to use again was revealed true but now I prepared for it using rubber bands to create a more comfortable grip of the small screwdriver. My final milestone is creating the remote controll but I also intend to add a cover for the top of the hexapod to hold the large battery before I call the hexapod complete.

<!--
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

-->

# First Milestone (June 13th, 2024)
**Install code to controller, assemble central body**
<!--**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/tXRV1RJAYvk?si=9CbVaSSGl9AUW2tx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

  My main project this summer is the freenove hexapod robot. The hexapod is built with a arduino mega as the controller for 18 servos which moves the legs. All of it is secured with screws onto an acrylic frame. So far I have used arduino IDE to upload the given programs to the controller and tested all the servos while conected to it. In addition, I connected a replacement power source to the controller and that to the acrylic frame. On the acrylic frame, I screwed discs for the servos to connect to using self tapping screws. That was the greatest challenge as the self tapping screws were stubborn and did not want to cut into a thread without a fight. Looking ahead to the many disks i'll have to screw in for the legs, I should to find a new efficeint method that doesn't kill my hands. Next up, I'll assemble the legs and calibrate them, then assemble the remote control. 

<!-- For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project-->



# Schematics 
![schematics](freenove's schematics.png)
![remote schematics](remote controll schematic.png)
![cover schematic](schematic for cover.png)

<!-- Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->

# Bill of Materials
<!--Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Acrylic parts | the frame of the hexapod (included in kit) | $126.95 | <a href="https://www.amazon.com/Freenove-Raspberry-Crawling-Detailed-Tutorial/dp/B07FLVZ2DN/ref=sr_1_1_sspa?crid=3GRGXL8PEZT3U&dib=eyJ2IjoiMSJ9.hyUjFCpcxtDvB6cSLdESXXxW_VlbfCW2sOuFZvcbQOIGmEBuC7OEUMaQFc9QwW4IXwx7Zam6zEOeONweFsjLFZKuOqUCxQ5HgmvRD4UQFOYNFty3scPqGq5J1g0TbtR_2bIyILUc5M0WNMqrnGrTWylHLQa3aQ613NmcWejs9wWrqJxOj5YOl3gf1PQej0RBbHZ0JXoReeEgeIy4xsbSajM-ZdqX12H5uQ_PnnmQRkQ.Nc_RRueNOp6PjfXo9382ZkI3SC-BbbYPBJXb0-GxLOo&dib_tag=se&keywords=freenove%2Bhexapod%2Brobot&qid=1718322574&sprefix=freenove%2Bhexapod%2Brobo%2Caps%2C133&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| Freenove Crawling Robot Controller Arduino | central controller for servos (included in kit) | $126.95 | <a href="https://www.amazon.com/Freenove-Raspberry-Crawling-Detailed-Tutorial/dp/B07FLVZ2DN/ref=sr_1_1_sspa?crid=3GRGXL8PEZT3U&dib=eyJ2IjoiMSJ9.hyUjFCpcxtDvB6cSLdESXXxW_VlbfCW2sOuFZvcbQOIGmEBuC7OEUMaQFc9QwW4IXwx7Zam6zEOeONweFsjLFZKuOqUCxQ5HgmvRD4UQFOYNFty3scPqGq5J1g0TbtR_2bIyILUc5M0WNMqrnGrTWylHLQa3aQ613NmcWejs9wWrqJxOj5YOl3gf1PQej0RBbHZ0JXoReeEgeIy4xsbSajM-ZdqX12H5uQ_PnnmQRkQ.Nc_RRueNOp6PjfXo9382ZkI3SC-BbbYPBJXb0-GxLOo&dib_tag=se&keywords=freenove%2Bhexapod%2Brobot&qid=1718322574&sprefix=freenove%2Bhexapod%2Brobo%2Caps%2C133&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| Servos (18x) | moves the segments of the hexapod (included in kit)| $19.99 X 5 | <a href="https://www.amazon.com/4-Pack-MG996R-Torque-Digital-Helicopter/dp/B07MFK266B/ref=sr_1_5?crid=2H6AEQNM44N4Y&dib=eyJ2IjoiMSJ9.Xjft-sUgM8c06EWiLToCu4ud5JSQpFSGJkvQnX4fus4I4PZyuINWhqg8p_LC5gLj_WbPwzSBaCeuv9W8TU16xJX3hTjftpNiGKlHRg2As16eOZ_18xgwUxwDYlzBNfwAPVHV8bDeOypgJtwh8UaEFKnHrh_KhZkdZOMwB2N0BPTe0lg1xbiRREm8Wn7elwv8GPZ1WwKvHjTgFhAxY4aYllPVPwE9K74gp6ATOxvrDQCs1uLhONY2X6ngr4CrnhUNcqNpcSkbdPo9ARfqQw2EdlQ86Tt8fVau2DRaFNaw9nk.XTGqJoZ8VaXxMYT7SIcKoguYgE1NZvnKonSMce5t_3g&dib_tag=se&keywords=servo&qid=1718408609&sprefix=servo%2Caps%2C776&sr=8-5&th=1"> Link </a> |
| ESP8266 Wi-Fi Module | enables remote controll from phone/remote (included in kit) | $6.59 | <a href="https://www.amazon.com/DIYmall-ESP8266-ESP-01S-Serial-Transceiver/dp/B00O34AGSU/ref=sr_1_5?crid=3GOL6I3EBGMIH&dib=eyJ2IjoiMSJ9.px4FtI_71QkacyvDpqIgx5j1tyPiXy_PgILs48PN144lSZvCaKm2AOFPYgKCqSVIdZhyHrZDfihzbCAuRbWKXKiFtMR5tJ1mXERCLMzlSv1VXnAFYJQOXPCdbwhg-g-zGNtYK9nyL_OQiNxUHS6AYFskb5BtUFB5zVvsY6_7l7JdjoqmRSY8haWrQoFlIBxIAcY5iK5PUNYkw2KlUztoKh_Iku1NaPCtwa3b7hNmbwg.7qZaFQ9e98Zz9RaFN0CEo8BdSPigvtGldXWbx9T1DMA&dib_tag=se&keywords=ESP8266+Wi-Fi+Module+x1&qid=1718408880&sprefix=esp8266+wi-fi+module+x1%2Caps%2C136&sr=8-5"> Link </a> |
| Cable Tidy | to wrap up and keep cables neat (included in kit) | $12.99 | <a href="https://www.amazon.com/D-Line-Spiral-Management-Solution-Organize/dp/B00OTRUW7G?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=AIVUHJ2NABNJF&th=1"> Link </a> |
| NiMH sub-C batteries x6 | the power source | $3.99 x 6 | <a href="https://power.tenergy.com/tenergy-propel-sub-c-3000mah-nimh-flat-top-rechargeable-battery/"> Link </a> |
| 4 inch zipties x6 | for extra cable management | $11.29 | <a href="https://www.amazon.com/Monday-HS-Plastic-Self-Locking-Electronics-Electrical/dp/B078NT5F2B/ref=sr_1_6?crid=36KQE6KZ5T53Y&dib=eyJ2IjoiMSJ9.7Ue6x10STH4mwycfHZtSsKN24UvTGoqsZwaXErIeGgf_UHp51xjXhJBfDgAGmW45-Jma28IuTEEnxB_CyUAurI4UEn0ylTYVNm_bvyo5sjHzI8xl94xSdnbu7ifK56rV3pMNzgIw87gN_U3WEDLK4Fm30xjNrhbSSouhDofYWChxoGgV6-r8vtWa3na5h3s_wgia_n8Y4OVGO9aDOuahK7lI0YwLVUMbyjoTZhifsig.j0IozqhEFrwj2F5okU1KEVnSyWD-Oso_CBUUIVqS-J8&dib_tag=se&keywords=zip%2Bties%2B4%2Binch&qid=1718750635&sprefix=zip%2Bties%2B4%2Binch%2Caps%2C131&sr=8-6&th=1"> Link </a> |


<!--| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
-->

# Other Resources/Examples
 - Freenove's given files ( instuctions, code, part details) : <a href="https://github.com/Freenove/Freenove_Hexapod_Robot_Kit"> link </a>

<!--
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
# Starter Milestone (June 11th, 2024)

<!--**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/qlhCMnZTruI?si=ikTGbaKnIwISUNnV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my starter project I made a retro gaming console. Most of the work consisted of soldering which is something I newly learned this week. To make it I was solder on a switch, buttons, a usb port, displays, batterys, and a buzzer. All the code for the games that it could play was already loaded onto the CPU on the board so the challenge was to solder all the components neatly and seperate in order to avoid a short. Through a few mistakes I made and what I did to fix it, I learned the importance of the amount of solder used and how to desolder.
