# **Mission 1: Computer Basics**


## TASK 1: NETWORKING FUNDAMENTALS

**What is Internet?**

Internet is a distributed packet switched network. Internet was a result of an experiment called “ARPANET”. ARPANET stands for **Advanced Research Project Agency Network.**

Paul Baran was figuring out to make a communication system which could survive a nuclear attack. He had the idea of breaking messages into blocks and sending them as fast as possible in every direction of a **mesh network.** 

**Who’s Incharge of Internet?**

Nobody and Everybody!

Internet is made of independently operating smaller networks. It is fully distributed and there’s no central control. So basically, there is n:n connectivity. 

**The Internet Wires and Cables and More:**

Imagine How does a picture or a message gets sent from one device to another?

It’s no magic, it’s actually Internet. Internet works conceptually like postal services. 

Data is divided into packets which are made up of bits and bytes.  Bits are the atoms of computer networking. Bits are sent through **electricity, light **and **radio waves**.

**BrainDuck Question:**

0 and 1 are the binary values which are represented by a single bit. Suppose there is a system of communication via electricity between two persons sitting on House A and House B. when Person from A switch on the light, it marks 1 and light off marks 0. Same goes for person from B. 

Suppose they want to sent 5 consecutive 1’s to each other, what solution can be devised?

**ANSWER: Just add a clock timer. Suppose 1 second is given to sent one bit. So bits per second can be an ideal solution to send consecutive 1’s or 0’s.**

To speed up the transmission, the bandwidth needs to be increased. Bandwidth is the maximum transmission capacity of a device. Bandwidth is measured by bit rate, which is the number of bits per second a system can transmit. Measure of speed is the latency, which is the amount of time it takes for a bit to travel from sender to receiver (source to destination).

When electricity is used as a transmission medium, there needs to be wires and connections all around which cause the loss in signals. To send the data across large distances, optical fibres are used which do not result in any signal loss. In fibre optics, signals are sent as light signals.

Fibre is very costly.

**How to send things wirelessly:**

Radio signals are used to send bits as radio waves. 

So basically whatever the medium be, everything on the internet, be it pictures, videos, files or anything else, everything comes down as 0s and 1s being transferred. 

**The Internet : HTTP and HTML**

What happens when you type in a web address in your browser and press enter?

You computer starts talking to another computer called the server, usually thousands of miles away. This communication is carried under a protocol called http. HTTP stands for **Hyper Text Transfer Protocol**. A communication between a host and server is usually carried by “GET” requests. When a person wants a page from a web server, he typically takes a GET request asking for the same page. 

HTML stands for **Hyper-Text Markup Language**. It tells the browser how to display a web document. HTML is used to display data on a web page. 

It is important to learn that the text is automatically rendered as HTML code but the images and videos have a separate HTTP requests and Separate URLS. A URL stands for **Uniform Resource Locator. **

Not every time the host requests the information from the server. At time, for example in case of filling up a form, the data needs to be sent from HOST to the SERVER. This is achieved using a HTTP POST request. 

**Concept of Cookies:**

Every time a HOST sends a POST login request, if the user is authenticated and authorised, the Web Server sends the request web page. But along with the page, the SERVER also send some other information to handle the user’s identity called a Cookie. 

A cookie is basically an ID card for the user. So next time, when the user refreshes the page, or basically requests anything from the SERVER, along with the request, the cookie is also sent from the HOST to SERVER so that the SERVER verifies the identity for the request.

Now, since the Internet is completely Open, and all information is sent in text which shared networks. This might make is easy for hacker to dive in the network and gain unauthorised access. To prevent this, websites use a safe communication channel using SSL which stands for** Secure Sockets Layer **and **Transport Layer Security. **These security layer just cover our communication channel to prevent unauthorised access. These are represented by the little **green lock** appearing on the address bar next to **https.** The safe websites are given a Digital Certificate, failing to own which the browser prompts a security warning to the user. 

## TASK 2 : COMPUTER FUNDAMENTALS:

**What is a computer?**

A computer is an electronic device that has the ability to store, retrieve and process data. A computer takes data as input from the user and processes the data inputs using a set of instructions understood by the computer (called commands) and conducts an action and gives output. 

**How Do Computers Communicate?**

Transistor circuits help computers store data. Since these microscopic switches have only two states 0 and 1, so computers understand and only understand the language of Binary. 

Basically every data can be represented as binary

**For Digits**: Binary based number system (e.g: 9 can be represented as 1001 in binary)

**For text**: Each letter corresponds to a number and each number has an associated binary value so a text is a bunch of binary values (e.g 1001100 101010101 1010101)

**For Images: **Each image is constituted of pixels, with each pixel having some intensity or RGB value which can be broken down into binary.

**For Videos:** Pixels in a  Frame per second can be represented in Binary

**For Sound:** The waveform representation allows to assign a decimal value to amplitude and later correspond it to an equivalent binary.


## TASK 3 : EVOLUTION OF COMPUTER NETWORKING:

Originally, computers were treated as larger complex machines and were operated by specially trained people. After WAN was discovered in 1965 by Thomas Marill and Lawrence Roberts who were the researchers at MIT, the interest started rapidly evolving. 

Over the course of time, the high-performance computing (HPC) systems became very powerful, agile and less costly. Cloud Computing played an important role here. Cloud Computing is the on demand delivery of compute power and is the future of networking. Cloud Computing has accelerated the evolution of high performance computing by allowing the self-service provisioning of IT services in minutes. 



