# Photograph Showing The Project IRL
<img width="569" alt="image" src="https://github.com/user-attachments/assets/aac026fc-4e20-4957-b326-a717a84c489c">

# Short Explanation Of The Project
This is my project for a Seminar/Project course in my Undergraduate professional study of Mechatronics at Zagreb University of Applied Sciences.
In short, the project you can see in the [above image](https://github.com/Emil-J/RC522_Lock-STM32-Project/blob/main/README.md#photograph-showing-the-project-irl) shows a F446RE Nucleo board, relay, solenoid lock, an LCD, a buzzer, an LED and a RC522 module for the MIFARE Cards. The bulk of the project was prgoramming the communication between all the devices withing the nucleo board. The hardest part was making the RC522 module work, before my project there were no projects that had a functioning RC522 module work with a F446RE Nucleo board. The ISO standards are a [part of the files](https://github.com/Emil-J/RC522_Lock-STM32-Project/blob/main/README.md#overview-of-all-the-files) of the project because without them, understanding the module and also programming the communication between the MIFARE cards and the RC522 module would be practically impossible.

# Photograph Showing The Wiring Schematic
<img width="854" alt="KTM_Shema_Projekta" src="https://github.com/user-attachments/assets/9c6f10f4-bb50-4a0f-a597-80379fb77e1b">

# Overview Of All The Files
* STM32CUBEMX_CONFIG.mp4 -> This is a video that shows the STM32CUBEMX configuration of the project that is inside the STM32F446RE Nucleo board.
* RFID_c-Function-Explanation -> This pdf file, has in some extent, explained the most important functions. In this document you have also the wiring of all the used componenets and pinouts,etc, etc.
* ISO-14443-3a && ISO-14443-2 -> These files show the standards that have been used to make this possible and explainable. These are standards for the PCD(RC522 module) to communicate with the PICC(Mifare 1k card) and vice-versa.
* MF1S50YYX_V1 -> This file is the datasheet of the MIFARE cards.
* MFRC522 -> This file is the datasheet of the RC522 "module".
* rfid-solenoid-lock.mp4 -> This is a video that shows how it is working IRL.
