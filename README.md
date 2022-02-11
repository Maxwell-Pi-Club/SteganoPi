<div id="top"></div>

<h1 align="center"> Steganography GUI  </h1>

<p align="center">
    <a alt="Version">
        <img src="https://img.shields.io/github/v/release/RabihND/SteganographyGUI?color=14adfa&logo=Semantic%20Web&logoColor=14adfa&style=for-the-badge" /></a>
    <a  alt="Downloads">
        <img src="https://img.shields.io/github/downloads/RabihND/SteganographyGUI/total?logo=App%20Store&logoColor=white&style=for-the-badge" /></a>
    <a href="https://github.com/RabihND/SteganographyGUI/graphs/contributors" alt="Contributers">
        <img src="https://img.shields.io/github/contributors/RabihND/SteganographyGUI?color=6fd671&logo=WhiteSource&style=for-the-badge" /></a>
    <a href="https://github.com/RabihND/SteganographyGUI//network/members" alt="Forks">
        <img src="https://img.shields.io/github/forks/RabihND/SteganographyGUI?color=cccccc&logo=Node-RED&style=for-the-badge" /></a>
    <a href=" https://github.com/RabihND/SteganographyGUI/stargazers">
        <img src="https://img.shields.io/github/stars/RabihND/SteganographyGUI?color=8e6be8&logo=Ethereum&logoColor=8e6be8&style=for-the-badge" alt="Stars" /></a>
    <a alt="Visitors">
        <img src="https://visitor-badge-reloaded.herokuapp.com/badge?page_id=RabihND/SteganographyGUI?color=14adfa&logo=Android&style=for-the-badge" /></a>
    <a href="https://github.com/RabihND/SteganographyGUI/master/LICENSE.txt">
        <img src="https://img.shields.io/github/license/RabihND/SteganographyGUI?color=%2363afdb&logo=letsencrypt&style=for-the-badge" alt="License"></a>
    
</p>

<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center"> Steganography 📟</h3>
  <p align="center"><img src="./stuff/wing.png" width="250"></p>
  <p align="center">
    A GUI Steganography Application for Windows Using C# or C++
    <br />
    <a href="https://github.com/RabihND/AP2021-2022-Final"><strong>Explore the documents »</strong></a>
    <br />
    <br />
  </p>
</div>


---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary> 
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#parts">Parts</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#refenences">Refenences</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<p align="center"> <img  src="https://media.wired.com/photos/594db1717c1bde11fe06f341/master/w_120" width="1000" > </p>  
<p align="justify"><b>Steganography</b> (/ˌstɛɡəˈnɒɡrəfi/) is the practice of concealing a message within another message or a physical object. In computing/electronic contexts, a computer file, message, image, or video is concealed within another file, message, image, or video.</p>

<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

Major frameworks/libraries used in this project:

* [C#](https://en.wikipedia.org/wiki/C_Sharp_(programming_language))
* [Visual Studio 2019](https://visualstudio.microsoft.com/vs/community/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- PARTS -->
## Parts
**1. Steganography software**

<p align="justify"> Steganography software is employed to perform a range of functions to cover data, including encoding the information in order to organize it to be hidden inside another file, keeping track of which bits of the quilt computer file contains hidden data, encrypting the info to be hidden and extracting hidden data by its intended recipient. There are proprietaries furthermore as open-source and other free-to-use programs available for doing steganography. <b><a href="https://www.openstego.com/">OpenStego</a></b> is an open-source steganography program; other programs will be characterized by the kinds of information which will be hidden still as what forms of files that data may be hidden inside. Some online steganography software tools include <b>Xiao Steganography</b>, accustomed hide secret files in BMP images or WAV files; <b>Image Steganography</b>, a Javascript tool that hides images inside other image files; and <b>Crypture</b>, a command-line tool that's wont to perform steganography.</p>

 
**2.  What are the advantages of steganography over cryptography?** 

<p align="justify">What are the benefits of steganography over cryptography? Steganography is distinct from cryptography, but using both together can help improve the safety of the protected information and forestall detection of the key communication. If steganographically-hidden data is additionally encrypted, the info should be safe from detection -- though the channel will not be safe from detection. There are advantages to using steganography combined with encryption over encryption-only communication. The primary advantage of using steganography to cover data over encryption is that it helps obscure the actual fact that there's sensitive data hidden within the file or other content carrying the hidden text. Whereas an encrypted file, message or network packet payload is clearly marked and identifiable intrinsically, using steganographic techniques helps to obscure the presence of the secure channel.</p>

> Check screenshot below to see how it can be done:

<details>
<summary>Preview</summary>
  <body>
    <img src="https://www.openstego.com/image/screenshot/01.png">
  </body>
</details>

**3.  How is steganography used today?** 

<p align="justify">In modern digital steganography, data is first encrypted or obfuscated in our way and then inserted, employing a special algorithm, into data that's an element of a particular file format sort of a _JPEG image, audio,_ or _video file_. The key message is often embedded into ordinary data files in many alternative ways. </p>

<p align="justify">One technique is to hide data in bits that represent the identical color pixels repeated during a row in an exceeding picture file. By applying the encrypted data to this redundant data in some inconspicuous way, the result is visiting be an image file that appears an image for the primary image but that has "noise" patterns of ordinary, unencrypted data. 
The practice of adding a watermark -- a trademark or other identifying data hidden in multimedia or other content files -- is one common use of steganography. Watermarking may be a method often utilized by online publishers to identify the source of media files that are found to be shared without permission. While there are many alternative uses of steganography, including embedding sensitive information into file types, one in all the foremost common techniques is to embed a document into an image file. When this can be often done, anyone viewing the image file mustn't be able to see a difference between the initial image file and thus the encrypted file; this can be often accomplished by storing the message with decreased bites within the record. This process could also be completed manually or with the employment of a steganography tool.</p>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- RESULTS -->
## Results


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the GPL-3.0 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- REFERENCES -->
## Refenences

🔎

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contacts


Rabih ND - [@RabihND](https://github.com/RabihND) 

**Project Link:** [https://github.com/RabihND/SteganographyGUI](https://github.com/RabihND/SteganographyGUI)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap


<p align="right">(<a href="#top">back to top</a>)</p>


---
<div align="center">
<p>
<img src="./stuff/mainlogo.png" width="110">
<p align="center"><b>
Maxwell-Pi Club</b>

(Organization)
</p>
</p>
</div>



