# QR CODES MAZE
## Rachele Guzzon
### *Final Submission, DATA AND MACHINE LEARNING FOR CREATIVE PRACTICE*

# Artistic Quizzing

### Video submission: [https://youtu.be/fHp1HGgXSz0](https://youtu.be/fHp1HGgXSz0)

The QR Codes Maze project, integrates new machine learning technologies with the age-old art of encryption and envisions a transformative role in education. This documentation navigates through the technical intricacies while exploring the potential of this innovative tool to create a visually captivating and intellectually stimulating method of quizzing students.

### **Project Overview:**

I started this project as a fun way to quiz my family using postcard-shaped QR codes, drawing inspiration from the historical use of encrypted letters hiding important messages. My fascination with the power of postcards and communication through everyday means was further fuelled when I stumbled upon the [Dear Data Project](https://www.dear-data.com/theproject). In this project, two artists exchanged postcards to visually represent data they collected during the week, leaving a lasting impression on my perspective.

### **Technical Exploration: QR Code Generation and Beautification:**

The project sees the creation of  a Gradio app for the beautification of QR codes and a detailed description of process step by step .

Utilising Google Forms for link shortening and Antony's QR Toolkit for code generation, Qr codes can be generated by anyone with minimal technical knowledge. 

The Hugging Face model, [monster-labs/control_v1p_sd15_qrcode_monster](https://huggingface.co/monster-labs/control_v1p_sd15_qrcode_monster), is a control-net based on stable diffusion 1.5 that is able to keep QRs that can be scanned while creating artistic results. The model is extremely flexible giving the user the option to use different size images and transformations.

> *I encountered issues with the Gradio image upload functionality as it generated images in an erratic manner, resulting in unusable and aesthetically disappointing generations. Therefore, I recommend utilising Notion as a reliable alternative for uploading input images online. This solution has proven to be both straightforward and stable, consistently delivering optimal results.*
> 

<aside>
<img src="https://www.notion.so/icons/code-scan_gray.svg" alt="https://www.notion.so/icons/code-scan_gray.svg" width="40px" /> The complete procedure to create beautified quizzes is provided in the notebook

</aside>

### **Artistic Pipeline, Historical Narrative, and Educational Innovation:**

As suggested by a family member working as and high-school professor, the artistic narrative can extend into the realm of education. The QR Codes Maze project now envisions a more visually captivating and intellectually stimulating way to quiz students. Beyond the traditional question-and-answer format, the maze-like QR codes add an extra layer of engagement and excitement to the learning process.

Educators can leverage this tool to create visually interesting quizzes, transforming mundane assessments into interactive experiences. The QR code mazes, inspired by historical encryption practices, become educational artefacts that invite students to unravel information in a dynamic and creative manner.

### **Conclusion:**

In conclusion, the QR Codes Maze project integrates technology, history, and art to create a tool that transcends traditional quizzing methods. As the QR code mazes come to life, they carry the potential to revolutionise the way students engage with educational content.The QR Codes Maze stands poised at the intersection of creativity and learning, inviting educators to reimagine the possibilities of student engagement in the digital age.

![yulepuzzle.png](QR%20Codes%20Maze%20Artistic%20Quizzing%2065d0cabb28e8403c84add68dd0d44876/yulepuzzle.png)

This marks the completion of the final poster, where the background has been created using a diffusion model. 

While I've made attempts to print the poster, there have been challenges. Regrettably, only the last code can be reliably scanned through this method. The readability is significantly impacted by lighting conditions, in retrospective I would have allocated more time for extensive testing and refinement.

# Earlier attempts:

Before adopting the aforementioned model, I experimented with various others. Although they may not be scannable, I find it valuable to showcase some of the results. These iterations demonstrate interesting behaviours that could potentially be used in other generative projects.

![download (12).png](QR%20Codes%20Maze%20Artistic%20Quizzing%2065d0cabb28e8403c84add68dd0d44876/download_(12).png)

![Untitled](QR%20Codes%20Maze%20Artistic%20Quizzing%2065d0cabb28e8403c84add68dd0d44876/Untitled.png)

![Untitled](QR%20Codes%20Maze%20Artistic%20Quizzing%2065d0cabb28e8403c84add68dd0d44876/Untitled%201.png)

