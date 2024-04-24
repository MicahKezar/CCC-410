# SEC-300-71: Topics in Security - Spring 2024
Radio Frequency Security is a five week one credit section of SEC300 that touches on radio frequencies and associated security protocols and principles. This course will dive into the ways radio frequencies affect our daily lives and how common protocols like Wi-Fi, Bluetooth, Cellular, Radio function on a detailed level. Additional emphasis will be put on the security methods that are implemented in different protocols. Students will be able to gain hands-on experience working with RF hardware as well as learning the legal and ethical implications related to RF security.

## [Week 1: RF Basics](https://github.com/MicahKezar/CCC-410/tree/main/Radio%20Frequency%20Security/Week%201)
![image](https://github.com/MicahKezar/CCC-410/assets/71364527/a6d4f060-399b-4102-b39a-2e8a456c90bc)

This week will focus on the basic understanding of RF principles, including frequency, wavelength, etc. This will cover the basics on how RF signals are transmitted and received to transfer data. Which frequency ranges are used for what?
- Police and emergency response frequencies
- Medical device frequencies
- Wi-Fi (802.11) frequencies
- Bluetooth
- Cellular
- Microwaves and other household items
- Cabling and how physical cables use RF
- Radio (AM and FM)
  
Learning Outcomes:  
- Basic properties of RF
- How common RF is used in our world
  
Lecture on above content, talking specifically about the basics of RF: how it works, images showing how it works, what frequencies are used for different devices (shown above).

Module 1 Assignments:
- [Lab 1-1 Heatmap Site Survey](https://github.com/MicahKezar/CCC-410/blob/main/Radio%20Frequency%20Security/Week%201/Lab%201-1%20Heatmap%20Site%20Survey.pdf)
- Discussion post: [RF Device in the Wild](https://github.com/MicahKezar/CCC-410/blob/main/Radio%20Frequency%20Security/Week%201/RF%20Device%20in%20the%20Wild.png)
- [Useful Documentation](https://github.com/MicahKezar/CCC-410/blob/main/Radio%20Frequency%20Security/Week%201/Useful%20Documentation.pdf)
- [Week 1 Slides](https://github.com/MicahKezar/CCC-410/blob/main/Radio%20Frequency%20Security/Week%201/Week%201%20Slides_%20RF%20Basics.pptx)

## [Week 2: Legal and Ethical Aspects of RF](https://github.com/MicahKezar/CCC-410/tree/main/Radio%20Frequency%20Security/Week%202)
![image](https://github.com/MicahKezar/CCC-410/assets/71364527/5dc4e0b1-2851-49fc-94ef-d568206d9988)

This week we can focus on a lot of the Legality surrounding Information Transmission and Reception, Radio Frequency Laws, and the Fourth Amendment. There are various legal standards that you must be compliant with. Examples such as:
- The FCC
- The FTC
- The CTIA 
- The TCPA
  
Lastly, we can use examples of cases that relate to the Legal issues with Cellular Transmission, such as the case of Edward Snowden.  
  
Learning Outcomes:  
- Understand legal implications for improper use of RF
- Discover governing bodies associated with RF
- Research one example where RF was used illegally
  
Module 2 Assignments:  
- Discussion post: [Illegal RF Use Case Study](https://github.com/MicahKezar/CCC-410/blob/main/Radio%20Frequency%20Security/Week%202/Illegal%20RF%20Use%20Case%20Study.png)
- [Quiz 2-1: Wireless Security](https://github.com/MicahKezar/CCC-410/blob/main/Radio%20Frequency%20Security/Week%202/Quiz%202-1%20Wireless%20Security.png)
- [Lab 2-1: WiGLE](https://github.com/MicahKezar/CCC-410/blob/main/Radio%20Frequency%20Security/Week%202/Week%202%20Lab%20and%20In-Class%20Demo_%20WiGLE.pdf)
- 

## [Week 3: Cellular Network Protocols & Vulnerabilities](https://github.com/MicahKezar/CCC-410/tree/main/Radio%20Frequency%20Security/Week%203)
![image](https://github.com/MicahKezar/CCC-410/assets/71364527/d6912250-cb98-4fbe-add8-8b7543e2f7fc)

This week will focus on the specific protocols used in cellular network architectures. We will also look into the evolution of cellular data protocols from 1G to 5G. Then we will look at history of attacks related to SMS and cellular protocols. How have text messaging, cellular protocols, and RF been involved in cyber attacks. We will look into how certain types of attacks work, and ways to protect against them.  
Cellphone Network Examples:  
- GSM 
- CDMA 
- LTE 
- 5G
  
Attack/Vulnerabilities:  
- SMS Phishing
- SS7 Vulnerabilities
- SIM Swapping
- Network Jamming
- Unencrypted SMS eavesdropping

We will also look how these protocols directly interact with the RF principles.  

Module 3 Learning Outcomes:  
- Relate RF understanding and basics to cybersecurity principles
- Understand how RF contributes to cellular based attacks  
Module 3 Assignments:  
- Quiz on differences in cellular protocols  
- Research project, pick an attack/vulnerability and write a 1 page report on how it works, an example of when it was used in the wild, ways to protect against it

## [Week 4: Receiving Radio](https://github.com/MicahKezar/CCC-410/tree/main/Radio%20Frequency%20Security/Week%204)
![image](https://github.com/MicahKezar/CCC-410/assets/71364527/0fc4b5a7-584f-40ff-bd9a-05351116a4c8)

This week we will focus specifically on Radio Transmission and Receiving. How does radio transmission work? How do you receive these signals? What is the legal frequency range anybody can broadcast in? We will discuss the legal ranges people can transmit, as well as people with HAM licenses can transmit. We will also discuss the frequency ranges that are strictly off limits. 

Hardware we currently have:  
- LimeSDR Mini

Hardware ordered for class:

- 12x [RTL-SDR w/ Antenna Combo](https://www.amazon.com/RTL-SDR-Blog-RTL2832U-Software-Defined/dp/B0BMKB3L47/ref=sr_1_3?keywords=RTL%2B-SDR%2B(Dongle)&qid=1701298883&sr=8-3&th=1)


Learning Outcomes:  
- Practicing Safe Radio Transmission
- Learning how to receive Radio frequencies
- Understanding the legal responsibilities that surround RX and TX

Module 4 Assignments:  
We will use in-class tools such as the RTL-SDR to demonstrate how one can receive radio frequencies. 
  
## [Week 5: RFID / NFC](https://github.com/MicahKezar/CCC-410/tree/main/Radio%20Frequency%20Security/Week%205)
![image](https://github.com/MicahKezar/CCC-410/assets/71364527/19edb38d-2f3f-4ec1-a876-869619804b8c)

This week we can talk about different RFID protocols. We will look into how the RF in RFID/NFC works, and the frequency(s) that RFID/NFC use. It will also be interesting to look into the different RFID/NFC protocols and the way that they transfer data and store data. Good opportunity to do a demo with RFID/NFC cloning (would need permission from the school).   
  
Here are some RFID models that we could dive deeper into:  
- HID H10301
- HIDPRox
  
Hardware we currently have:
- Blank writeable/readable RFID cards
- Blank writeable/readable NFC 215 tags
- Proxmark3
- Flipper Zero

Learning Outcomes:  
- Writing and reading RFID/NFC
- The dangers of RFID/NFC and common threats associated
  
Module 5 Assignments:
- Hands on lab with RFID/NFC, write to an NFC tag and receive another students content
- Brief open answer quiz, one paragraph about the way RFID/NFC can be used maliciously, another paragraph about ways to protect against it

# [Syllabus](https://github.com/MicahKezar/CCC-410/blob/main/Radio%20Frequency%20Security/Radio%20Frequency%20Security%20_%20Syllabus-2.pdf)

## Class Day/Time
Tuesdays 4:00pm - 5:15pm
Location: Joyce 310

## Your Instructors
Instructors: Cole Davis-Brand, Micah Kezar, Adam Goldstein

## Course Description
Radio Frequency Security is a five week one credit section of SEC300 that touches on radio frequencies and associated security protocols and principles. This course will dive into the ways radio frequencies affect our daily lives and how common protocols like Wi-Fi, Bluetooth, Cellular, Radio function on a detailed level. Additional emphasis will be put on the security methods that are implemented in different protocols. Students will be able to gain hands-on experience working with RF hardware as well as learning the legal and ethical implications related to RF security.

## Learning Objectives
Upon completion of the course, students will be able to:  
● Understand the basic properties of radio frequency  
● Learn about how common radio frequencies are used in our daily lives  
● Grasp the legal implications for improper use radio frequencies  
● Discover governing bodies that are associated with the legality of radio frequencies  
● Perform case studies on real life examples of times radio frequencies were used with malicious intent  
● Relate radio frequency understanding to cybersecurity principles  
● Gain hands on experience practicing safe radio transmission and reception   
● Gather awareness of the legal responsibilities surrounding transmission and reception  
● Build RFID/NFC tags and understand the potential dangers associated with contactless communication  

## Teaching Methodology

### Lectures
Lectures will play a brief yet crucial role in each class, introducing new topics to provide a foundational understanding of key concepts and facts. These sessions are essential for grasping the details necessary for success in labs and discussion posts, helping students integrate theoretical knowledge with practical applications. Additionally, lectures will serve as a bridge, relating the content to upcoming lab and project activities.

### Labs
Hands-on learning is integral to this course, with labs serving as a crucial component. These labs play a dual role—reinforcing challenging concepts and offering real-life applications of the material. A strong emphasis is placed on self-teaching and problem-solving, encouraging students to independently navigate through challenges and troubleshoot issues. This approach not only deepens understanding but also cultivates valuable skills in tackling real-world problems.

### Readings
It is important to note that readings should not be anticipated on a weekly basis. Instead, they will be assigned as necessary and relevant throughout the course. When readings are assigned, students are expected to thoroughly engage with the material. It is emphasized that readings will not be given as busy work; they will only be assigned when the content is directly pertinent to the course.

### Discussion Posts
Discussion posts serve as an excellent platform for students to articulate their thoughts and share their research findings. These posts not only provide an opportunity for individual expression but also offer a collective insight into the diverse perspectives within the class.

### Quizzes
Quizzes in this course serve as focused assessments, designed to highlight essential details presented in lectures and class discussions. Their primary purpose is to reinforce key concepts and ensure a comprehensive understanding of the material. It's important to note that the intention behind quizzes is not to be tricky or present challenges through complex wording.

### Grading
Grades will be awarded in accordance with the Champlain College Grading System for undergraduate students. Final Grade Breakdown can be viewed in Canvas and is subject to change with notification.
This course is pass/fail.

## Class Policies

### Assignments/Homework & Late Work
In this course, assignments are expected to be submitted by the specified due dates. However, late submissions will still be accepted and graded without a point deduction. It is highly recommended to adhere to the original deadlines to make the most out of the learning experience. The course operates on a pass/fail grading system, emphasizing completion and participation over penalizing for tardiness.

### Attendance Policy
Attendance in this course constitutes 15% of your overall grade, and it will be recorded at each class session. Given the condensed nature of this 5-week course, it is imperative not to miss any class, as each week's attendance contributes significantly to your total class time.

### Respectful Environment
This class is committed to maintaining a respectful and inclusive learning environment. All students are expected to engage in discussions, activities, and interactions with courtesy and consideration for diverse perspectives. Disagreements and debates are welcome, but they should be conducted in a constructive and respectful manner. Discrimination, harassment, or any form of disrespectful behavior will not be tolerated.

### Confidentiality and Mandatory Reporting
As instructors, one of our responsibilities is to help create a safe learning environment on our campus. We also have a mandatory reporting responsibility related to our role as faculty members. It is our goal that you feel able to share information related to your life experiences in classroom discussions, in your written work, and in our one-on-one meetings. If you come to us with non-course-related concerns, we will seek to keep the information you share private to the greatest extent possible. However, please understand that we are legally required to share with designated Champlain College offices information regarding sexual misconduct such as sexual assault, sexual exploitation, and partner or relationship violence.
