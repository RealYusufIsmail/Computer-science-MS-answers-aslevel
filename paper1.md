# This readme can not and is not allowed to be redstrubuted for any means without the owners approval or by inserting the license in the content used.

# If this is found to be breached then action will be taken.

# Paper 1

## Characteristics of Contemporary Processors

### Structure and Function of the Processor

- **Name and describe three buses used to convey information between the special registers.**
    - Control bus…
…transmits control signals from the
control unit (to other parts of the
processor)
  - Data bus…
…carries the data (from one place to
another)
  - Address bus…
…carries the location address
(register) where the data is going (to or
from)

- **Program Counter (PC):**
  - Is needed to store the address of the next instruction (to be processed)
  - Value is then sent to the MAR
  - After sending the value the PC is incremented / changed to address held in CIR if the operation is a Jump
  - The location of the next instruction (to be fetched).


- **Memory Address Register (MAR)**
  - Contains the address of the instruction (to be accessed in memory)…
  - …address of instruction sent from PC
– Contains the address of the data (to be accessed in memory)… …address of data sent from CIR
  - Stores the memory location of the
data to be fetched/ stores the memory
location 50 [1]

- **Memory Data Register (MDR)**
  - Contains the instruction which has been accessed from memory
  - Contains the data which has been accessed from memory
  - That is referenced by the MAR / Instruction sent to CIR
  - acts as a buffer
  - Stores the data from memory location specified by MAR / Stores the data 
from memory location 50 [1]

- **Address Bus:**
  - Transfers the memory location to access the data (to be fetched)/ transfers the memory location 50 [1]

- **Data Bus:**
   - Transfers the data from the memory location specified by MAR / Transfers the data from the memory location 50       

- **fast clock speed:**
    - Gives more cycles per second
    - More instructions can be executed per second
    - So the program takes less time to run 

- **large cache memory:**
    - More space for data / instructions in cache memory
    - RAM needs to be accessed less frequently
    - Accessing cache is quicker than accessing the RAM (1 per -, Max 2)
 

- **Describe two ways in which the accumulator is used.**
  - Temporary storage for data being processed / during calculations
  - I/O in processor…
  - … used as a buffer / gateway

- **Describe the use of special registers and their functions during the fetch decode-execute cycle, including jump instructions, reading from and writing to memory.**
  - Registers
    - Mentions CIR MDR MAR PC and
ACC
    - Jump instruction CIR sends
address to PC
    - PC incremented
    - MDR copies data to CIR
    - CIR holds the data to be decoded..
…into opcode and operand
  - Saving
    - CIR sends address to MAR..
…sends data to MDR
    - All data to be saved uses the ACC
  - Other relevant points
    - All arithmetic and logical operations
use the ACC
    - Mention of buses (Address Data or
Control)
    - Control unit for synchronisation
    - Mention of Interrupt Register
    - ALU performs calculations

- **Describe the role of the control unit in the processor.**
    - Decodes instructions. [1]
    - Sends control signals to coordinate
movement of data through the
processor / execute instruction. [1]
     - Controls buses [1]

- **Discuss what measures can be taken to improve Dan’s computer’s performance.**
    - Methods of improving performance
        - Replace CPU with faster CPU
        - Add more/Faster RAM
        - Add a graphics card
        - Upgrade to faster secondary storage
        - Update OS
        - Install a lighter weight OS
        - Defragment the hard disk
        - Check for viruses and spyware
    - The selected knowledge/examples should
be directly related to the specific question.
The example below is not prescriptive or
exhaustive:
        - A newer CPU may have a faster clock
speed and so execute more
instructions per second. It may have
multiple cores and so be able to
execute several programs
simultaneously (or one in parallel).
It may have more cache meaning
comparatively slower RAM can be
accessed less frequently.
        - More RAM means more programs can
be open simultaneously without the
need to use much slower virtual
memory.
        - Adding a graphics card will speed up
the rendering of 3D graphics as GPU
has specialist instructions and can
apply the same instruction to multiple
pieces of data simultaneously.
        - The slower the secondary storage the
longer it takes to load
files/program/data. A faster secondary
storage device can improve this. May
choose to use flash memory (i.e. SSD)
        - OS makers often release updates and
some of these will improve
performance.
        - Some lighter weight operating systems
use fewer system resources allowing
the system to devote more to running
the user’s applications.
        - A fragmented HDD runs slowly as time
is spent finding parts of the files. This is
reduced by defragmenting and storing
the parts of the file contiguously.
    - Malware can slow down a computer.
Removing it will improve performance
      - Evaluation
         - The following is indicative of possible
evaluation points that candidates may refer
to but is not prescriptive or exhaustive:
        - Hardware improvements (i.e. CPU, RAM,
secondary storage and GPU) have costs
attached but likely to have most impact.
        - The higher performance the hardware,
the more cost incurred.
        - (NB candidates aren't expected to know
relative costs of components.)
        - GPU unlikely to benefit student in this
scenario (unless their course requires
graphics processing). 
        - Defragmenting HDD is free and so should
be performed.
        - Running anti-malware programs is free/low
cost and should be done as a precaution
against losing data anyway.
        - Moving to lighter weight software can
potentially be free if the user considers
open source software.

### Types of Processor

- **CISC (Complex):**
    - Each instruction may take multiple cycles
Single register set
    - Instructions have variable format
    - Many instructions are available
    - Many addressing modes are available
    - Complicated processor design
    - Integrated circuit is expensive
    - CISC many address modes
    - CISC may have more registers
    - CISC
takes many cycles to complete one
instruction

- **RISC (Not-Complex):**
    - An instruction performs a simple task
    - Limited number of instructions available
    - Complex tasks can only be performed by
combining multiple instructions
    - Simple processor design
    - Programs run faster… …due to simpler instructions
    - RISC requires more RAM
    - RISC takes one machine cycle
    - RISC fixed number of bytes
    - Requires less cooling to be built in.

- **Von Neumann:**
    - instructions are executed in a linear sequence
    - Single control unit
    - One instruction at a time
    - Uses fetch execute cycle
    - Single ALU
    - Data and Instructions stored in the same memory / format(1)
    - Program & data stored together / program & data in same format
    - A register is a small piece of memory used for storing data within the processor

- **Harvard architecture**
    - processors benefit from having separate data and instruction memories.
 
<img width="524" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/9ad7a5ac-b04d-4e10-b978-0b0997171c9e">

<img width="533" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/f561e5f1-291d-425d-bcf0-e61e4a33db70">



- **fetch-decode-execut**
    - **fetch**
        - The next instruction is fetched
from main memory/address
    - **decode**
        -  The instruction is interpreted /
translated / split into opcode and
operand (in the CIR)
    - **execut**
        - The appropriate
instruction/opcode is carried out on the
operand. 


### Input, Output and Storage

- **Magnetic hard drives**
    - work by magnetic
patterns being read off platters that
mechanically spin at high speeds.
    - can be noisy (due
to parts moving at high speed), this can be
undesirable and distracting whilst gaming.
Conversely flash drives operate silently.
    - Due to their high storage capacity
magnetic hard disks are the best choice. A
gamer could have many games installed at
one time.
    - require enough
space for their moving parts 
    - magnetic hard drives can be
susceptible to damage if moved quickly
(1 – AO3.3) due to the head coming
into contact with the platter

- **cloud storage**
    - Potentially vulnerable to
hacking.
    - Reliant on an internet connection/requires a fast enough internet connection.
    - Reliant on company servers.

- **Flash hard drives**
    - use memory chips.
These can have their contents erased and
subsequently overwritten when an
electrical charge is applied.
    - tend to have much
higher read / write speeds than magnetic
hard disks.
    - have no moving parts
and therefore tend to have lower power
consumption and are not affected by their
device moving.
    - Whilst performance is not quite
that of flash drives, to have a similarly
sized flash drive would be prohibitively
expensive.
    - flash memory has no moving
parts and so is not affected

- **output device**
    - A printer -  to print (hard copies) of
photographs / relevant documentation
    - A monitor - which may be of a larger size / higher quality than that on her laptop making editing easier. 

- **RAM**
    -  Is volatile
    -  Is editable
    -  Is larger
    -  The contents of RAM are wiped
    -  Stores User files / software / OS currently in use
        - User must be able to alter contents of file / computer needs access to software but needs to be able to replace it
        - RAM offers direct access.
        - RAM operates at a much faster speed than most secondary storage devices.

- **ROM**
    - is not volatile
    - cannot be altered
    - is smaller
    - cannot be altered so there is no chance of the OS being accidentally or maliciously changed (on what is a safety critical system)
    - is quick to start up so the system can be started up quickly (in an emergency) (1).
    - Stores Boot file / program / BIOS
    - Must be available when computer switched on ( therefore must be stored on medium which is non–volatile)
    - The boot program / BIOS must not be deleted / unintentionally amended (and therefore is best stored on a read–only medium.)
    - The software will not need updating

- **Cache**
    - Cache memory is temporary storage for frequently accessed data.
    -  Cache memory is very quick to access because it is closer to the CPU than other types of memory like RAM.
    -  Level 1 cache is the smallest level (less than a megabyte) but it is also the fastest.
    -  Level 2 cache is larger than level 1 (up to 8 megabytes) but slightly slower.
    -  Level 3 cache is located outside of the CPU core which makes it slower than the first two levels but it is much larger (up to 50 megabytes).
    -  Cache memory is closer to the CPU than RAM, meaning that it can provide data and instructions to the CPU at a faster rate.
    -  A computer with more cache memory (e.g. 8MB instead of 4MB) should have a higher performance because repeatedly used instructions can be stored and accessed faster.
    -  Larger level 1 and level 2 cache sizes will improve a computer's performance as data can be accessed extremely quickly.
    -  Cache memory is costly, so most computers only have a small amount.
    -  Multiple cache misses will result in data latency (delay) as information is accessed from RAM which is further away from the CPU.

- **Lossless**
    - Lossless rewrites original data in more efficient format
    - Lossless is able to recreate the original file
    - Lossless keeps original quality
    - Lossless: the video will buffer more / slower to start watching the video

- **Lossy**
    - Lossy permanently removes data
    - Lossy is not able to recreate the original file
    - Lossy reduces quality of videos
    - Lossy file size is smaller than if lossless were used
    - Lossy: compression ratio may be adjusted depending on bandwidth
    - Resulting in a noticeable decrease in quality on slower connections.
    - Lossy: the video will buffer less / quicker to start watching the video
 
- **questionair**
     - Format that OMR can detect (e.g. lozenges).
     - Primarily use closed questions / multiple choice. [1]
     - Consistent format for answers (e.g. if 1 is not agree at all and 5 is agree entirely not switching round) [1]
     - Logical ordering of questions. [1]
     - Sensible use of space
     - Storing documents being / waiting to be printed.

## Software and Software Development

### Systems Software

- **real-time**
    - The system gives a response within a
guaranteed time frame 
    - response is immediate
    - no delay in response

- **FIFO**
    - Once a job starts it prevents other jobs
from being processed
    - A job using a slow resource (eg printer)
wastes processor time 

- **other scheduling methods.**
    - Round robin
    - Time slice to each user in turn
    - Length of job
    - Shortest job first 

- **scheduling**
    - Process as many jobs as possible…
…in least possible time / quicker
Ensure all jobs are processed (fairly)
Maximise number of interactive users…
…with fast response times / real time
Efficient use of resources / processor time    

- **memory management**
    - Organise the use of (main) memory… …by converting logical addresses to physical addresses
    - Allows programs to share memory / allocate memory… …& protect programs / data from each other
    - Allows programs larger than main memory
to run

- **paging**
    - Partitioning memory
    - Pages are fixed size
    - Pages are physical divisions
    - Used for virtual memory
    - Parts of a program divided into equal size pieces
    - Use virtual memory / backing store to swap parts of programs
    - Allows programs to be stored in memory noncontiguously

- **segmentation**
    - Parts of a program divided into unequal sizes
    - Uses logical divisions
    - Use virtual memory / backing store to swap parts of programs
    - Programs can be stored non-contiguosly, though they work better contiguously

- **CPU interrupt.**
    - Complete the current FDE Cycle
    - Check the priority of the incoming interrupt.
    - If its of a higher priority than the current task.
    - Contents of registers stored in memory..
    - … in a stack.
    - The relevant interrupt service routine is loaded …
    - ..by loading the relevant value into the program counter.
    - When the ISR is complete the previous state is popped from the stack
    - And are loaded back into the registers.

- **Supercomputer**
    - The CPUs can work in parallel
    - … on the same problem
  - try multiple keys simultaneously…
    - …to break the code
    - Super computers can have multiple
processors (and GPUs).

- **Operating systems**
    - Provide a user interface
    - Provide System Security
    - Manage hardware
    - Provide utilities
    - Provide a platform from which software can be installed/run
    - Schedule jobs
    - Handle interrupts
    - Manage memory
    - OS is loaded up by the BIOS which carries otu checks prior to the loading.

- **Operating systems utilities**
    -  Disk Defragmente
    -  Compression Utility
    -  Disk Checker
    -  Virus checker
    -  File manager

- **Types of Operating System**
    - Distributed
        - Run across multiple devices, allowing the load to be spread across multiple computer processors when a task is run.
        - A system which shares processing (between the processors on a network) / shares the data between different systems (on a network in order to reduce bottlenecks).
    -Embedded
        - Built to perform a small range of specific tasks and catered towards a specific device such as a household appliance. They are limited in their functionality and hard to update although they consume significantly less power than other types of OS.
    - Multi-tasking
        - Multi-tasking operating systems enable the user to carry out tasks seemingly simultaneously. This is done by using time slicing to switch quickly between programs and applications in memory.
    - Multi-user
        - Multiple users make use of one computer. A scheduling algorithm is used to ensure processor time is shared fairly between jobs and prevent processor starvation.
    - Real Time
        - Commonly used in time-critical computer systems, a real time OS is designed to perform a task within a guaranteed time frame. Examples of use include the management of control rods at a nuclear power station or within self-driving cars: any situation where a response within a certain time period is crucial to safety.

- **network operating system**
    -  File handling… …allowing Access to, and manipulation of, files dependent on the identity of the user
    -  Handling communication… …controls the movement of data around the network (by use of agreed protocol)
    -  Resource sharing / resource management… …ensure fair allocation of resources / volume of printout allowed / etc
    - Automatic backup… …so that data is not lost if it is corrupted 


- **Virutal Machine**
    - A virtual machine is a piece of software that behaves in the same way as an actual computer
    - Allows you to save space, time and cost of setting up multiple OS.
    - Requires a power computer
    - Apps will run slower as less ram is provided.
    - Realistically physical machines will have to be used at some point to be
100% sure everything works as it should.

- **Device driver**
    - A program/software
    - That controls a piece of hardware
    - Providing an interface/bridge between the device and (operating) system
 
### Applications Generation

- **utility**
    - performs a specific task (1) and is usually related to the upkeep of the system
    - Examples of a utility include a virus checker (1) / disk defragmenter (1).

- **assembler**
    - convert code into machine code.

- **File handlers**
    - Manages data storage / organises data storage
    - Used for the deletion / sorting / moving / copying / creation of files / folders
    - Manage the storage of software
    - Manage the storage of stock files
    - To access files 

- **Hardware drivers**
    - Enable peripheral and OS to communicate
    - To configure hardware
    - e.g. would be used to install a new keyboard; mouse; printer (accept any examples sensible within context)

- **Backup utility**
    - Automatically makes a copy of files
    - Storing them in a different location / medium
    - To make Incremental back–ups
    - Ensure that sales / stock data is backed up

- **open source software**
    - Source code is freely available
    - for others to amend / examine / recompile 

- **Java**
    - One version needs be written and can be used on any device / OS combination that has the Java Virtual Machine rather than having to write multiple versions.
    - Code running on a VM tends to be slower than compiled.
    - Multiple devices can include devices other than PCs (i.e. phones, tablets)
    - People with unusual operating systems or architectures would have access to the application.
    - It makes commercial sense to sell to as wide an audience as possible.
    - The speed reduction compared to compiled code will likely be noticeable with such a processor intensive task. As running on a VM coders will have limited (if any) access to some of the low level features (e.g. access to the GPU) which can optimise the program.

- **C++**
    - Multiple versions of the code will need to be maintained for different architectures… …however there may be minimal differences between them, and then just need compiling with different compilers.
    - Program will run quicker than alternatives.
    - Some less used architectures may not be developed for as not commercially viable.
    - Compiled code will run quicker than the other options. This is likely to be noticeable given the nature of the task.
    - Easier to get access to lower level features (such as GPU access).
    - Compiled code is not human readable helping to preserve intellectual property

- **JavaScript**
    - As interpreted likely to be by far the slowest option.
    - Will run in any browser.
    - Most people have web browsers so by far most compatible option (don't even need VM).
    - The slow speed may be frustrating… …though as no user interaction is needed this may be a trade off worth making. Source code is visible (though can be obfuscated) meaning it can easily be copied and amended.
    - A programming language that runs in a web browser
    -  that can be embedded into HTML
    -  JavaScript is likely to be run on a variety of machines (1) with different processors / architectures (1).
    -  Compiled code is machine dependent (1) whereas interpreters run on high level code (1) which is machine independent (1).

### Programming Languages

- **Little Man Computer**
    - <img width="458" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/9adb074e-a708-4749-ae85-b3e35e97beab">
        - It outputs 3
    - SUB - Subtract
    - result is held at the accumulator
    - BRP - The program flow jumps to a (designated) label / another point in the program
  - If the value in the accumulator is positive.
  - BRZ, BRP, BRA - change contents in program counter
  - STA copys the content of the accumaltor when emmory is excuted.


## Exchanging Data 

### Databases

- **primary key**
    - A field that has a unique value / a unique identifier (1) for every record in hat table (1)
- **secondary key**
    - A secondary key is indexed allowing for faster searching
- **flat file**
    -  A flat file is a database that consists of a single file
- **entity-relationship**
    - three tables

<img width="194" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/8b6209a1-aac1-4fa3-9d7b-3115a6e2f999">

- **double entry**
    - Data inputed twice
    - The two input are compared by computer to make sure thay are correct

- **validation check**
    -  Range check
    -  Length check
    -  Type check / character check
    -  Format check / input mask

### Networks

- **TCP/IP**
    - Stands for “Transmission Control Protocol / Internet Protocol”… (1)
    - Protocol(s)/set of rules… (1)
    - …for communicating across a network / the internet. (1)
    - Each protocol belongs to a different layer. (1)
    - The layers are: Application, Transport, Internet, Link (1)
    - (Starting at the Application layer) data is further encapsulated as it as it is passed to the next layer. (1) 

- **peer to peer network**
    - Devices on the network have equal status/no (central) server.
    - Devices on the network share data
    - <img width="572" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/9918cddd-5144-4ed4-bdc6-009ac6ba15b9">

- **Client-server**
    - Client-server networks consist of terminals known as clients connected to a server
    - The server is a powerful, central computer.
    - The server holds all of the important information and resources and has greater processing power than the terminals.
    - <img width="506" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/c55e0b9c-5c6c-4fd4-9284-40df6a95cf9d">

- **LAN**
    - A LAN covers a small geographical area (e.g. a building or campus). [1]
    - A LAN uses connections owned by the organisation that owns it. [1]
    - More secure than a WAN [1]

- **WAN**
    - A WAN covers a large geographical area.[1]
    - A WAN often uses third party connections.[1]
    - Less secure than a LAN [1] 

 - **Logical protocol**
     - A set of rules… [1]  …that define the communication of data [1]
     - focusing on how data is represented [1]
     - appropriate e.g. character set / baud rate [1]
       
- **Protocol**
    - A set of rules for communication between two devices.
    - Example include HTTP/S, TCP/IP, and FTP.

- **high bit rate**
    - determines the quality of a connection
        - Video streaming requires a large amount of data…
        - …In a short period of time [1]
        - Video streaming is time sensitive [1]
        - Or else there are interruptions in the video [1]
     
- **Ip handle**
    - (Customers enter) domain name and this is sent to DNS servers.
    - DNS servers map this domain to an IP address
    - If the DNS server can't resolve, it passes the request (recursively) to another DNS server.
    - DNS Server sends the IP address to browser
    -  so it can retrieve the website from server on which it is hosted.

### Paper 1 programming examples 

- **Html**

<img width="398" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/e5ab13b8-b357-441d-b323-755f4600fed6">

<img width="196" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/2799576a-a341-41ca-b58a-f0eb85c97ef9">

- **Css**
  
<img width="357" alt="image" src="https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/c2f2d49b-8b04-4f11-8817-06ea0e44da3d">

```css
#warning {
    color: red;
    font-family: monospace;
}
```
### Legal, Moral, Cultural and Ethical Issues

- **Data Protection Act**
    -  Customer has the right to see the data and to ask for it to be corrected if wrong so that they are not responsible for incorrect data
    -  Data must be lawfully collected so that customer rights are not flouted
    -  Data can only be accessed by/changed by authorised people so that malicious alterations are not made
    - Authorised people must be notified to the DPR so that they are accountable
    - Data is only used for the specified purpose so that junk mail is not encouraged
    - Data collected should not be excessive so that irrelevant data is not stored
    - Data should be accurate and up to date so that customers are not held responsible for goods they have not bought
    - Data should not be kept longer than necessary so that customers can leave an organisation
    - Data should be protected by adequate security measures so that people with malicious intent cannot gain access
    - Data should not be transferred out of the EU so that data remains subject to DPA.

- **Computers impact on wellbeing**
    -  Computers have reduced the monotony of some jobs….
    - …Meaning people find their work more challenging and rewarding.
    - They allow workers to collaborate with colleagues across the world…
    -  …Meaning people can enjoy sharing ideas.
    -  They have meant having strong ICT skills a fundamental part of many jobs…
    -  ..Which can put pressure on people to acquire/keep up to date these skills.
    -  They have allowed people to work more flexibly including working from home…
    -  …meaning they can have a better work/life balance…
    -  but can lead to them feeling isolated.
    - … and potentially feeling pressured into working outside of normal hours.

- **Computers affect on soceity**
    - People are becoming more reliant on portable computer systems
    - Instant access to data
    - Accessible anywhere (where there is a signal)
    - Problems for those in society who are technologically unaware
    - Problem with divided society, the haves and the have nots
    - Social interaction apps make contacts more plentiful
    - No difficulty in contacting individuals or groups of individuals
    - Problems caused by social pressures to conform and use them
    - Problems caused by online bullying
    - Loss of traditional means of communication

- **Use of technolgy in homes**
    - …leading to increased free time...
        -  Automatic washing, machines/dishwashers/...
        -  …leading to increased free time...
        -  …increased leisure time/more family time/...
        -   …chance to go to work because of time freed up, leading to...
        -  …increased family wealth 
    -   Chance to work from home:
        - More time spent in productive work
        - Chance to plan work around home life
        - Because of advances in communication and...
        -  …and availability of more accessible technology
    - More recent advances including:
        -  Intelligent larders which know what food is in them and place automatic orders...
        -  ...delivered by supermarket and placed in larder from outside
        -  reduces the need for shopping
        -  Robotic cleaners...
        -  ...reducing the need for cleaning by hand
        -  GPT - homework, etc
        -   Microwave cookers have simplified the task of cooking together with...
        -   ...large amounts of processed food available which does not need preparation All have reduced the number of tasks to be done...
        -   ...the amount of time spent on those tasks which still need to be done
        -   ...the knowledge needed to complete the tasks
        -    The amount of socialising has been reduced eg when doing the shopping.
