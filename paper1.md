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
  - Is needed to store the address of the next
instruction (to be processed)
  - Value is then sent to the MAR
  - After sending the value the PC is
incremented / changed to address held in
CIR if the operation is a Jump


- **Memory Address Register (MAR)**
  - Contains the address of the instruction
(to be accessed in memory)…
  - …address of instruction sent from PC
– Contains the address of the data (to be
accessed in memory)…
  - …address of data sent from CIR
  - Stores the memory location of the
data to be fetched/ stores the memory
location 50 [1]

- **Memory Data Register (MDR)**
  - Contains the instruction which has been
accessed from memory
  - Contains the data which has been
accessed from memory
  - That is referenced by the MAR /
Instruction sent to CIR
  - acts as a buffer
  - Stores the data from memory
location specified by MAR / Stores the
data from memory location 50 [1]

- **Address Bus:**
  - Transfers the memory location to
access the data (to be fetched)/
transfers the memory location 50 [1]

- **Data Bus:**
   - Transfers the data from the memory
location specified by MAR / Transfers
the data from the memory location 50       

- **fast clock speed:**
    - Gives more cycles per second
    - More instructions can be executed per second
    - So the program takes less time to run 

- **large cache memory:**
    - More space for data / instructions in
cache memory
    - RAM needs to be accessed less
frequently
     - Accessing cache is quicker than
accessing the RAM (1 per -, Max 2)
 

- **Describe two ways in which the accumulator is used.**
  - Temporary storage
for data being processed / during
calculations
  - I/O in processor…
  - … used as a buffer / gateway

- **Describe the use of special registers and their functions during the fetch-decode-execute cycle, including jump
instructions, reading from and writing to memory.**
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
    - Programs run faster…
…due to simpler instructions
    - RISC requires more RAM
    - RISC takes one machine cycle
    - RISC fixed number of bytes

- **Von Neumann:**
    - instructions are executed in a linear sequence
    - Single control unit
    - One instruction at a time
    - Uses fetch execute cycle
    - Program & data stored together /
program & data in same format 

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
    - Allows programs to be stored in memory noncontiguously

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

### Software Development

