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

# Paper 2

## Abstraction – Computational thinking:

- **What has happened:**
  - X has been removed
  - People have been removed/simplified with symbols
- **Removes elements from a problem:**
  - Means of hiding irrelevant details
- **Benefits:**
  - Reduced development time (1) as factors that can detract from the program can be ignored (1)
  - Program more likely to solve the problem (1) as unnecessary aspects will not detract from the main purpose of the program (1) 
  - Reduces complexity of programming code (1) therefore can run on lower spec computers(1)

## Record:
- Can store multiple values under one identifier 
- The data can be of different data types

## Array:
- **Benefits of 1d array:**
  - Allows easy access/indexing/manipulation of each data item in turn 
  - 1D Array can hold multiple items of the same data type
  - Maximum number of array elements is known

## Subprograms:
- **Benefits:**
  - Small sub-programs are easier to read/understand/modify 
  - Write once and call repeated times
  - Avoids repeated code 
  - Subroutines can be tested individually then added to the main program
  - Modules already tested
  - Can be reused in other programs
  - Can give procedures to different programmers to build

## Global/Local variable:

- **Scope of global and local variables:**
  - Global variable is declared outside of the subroutine.
  - Local variable is only visible in the subroutine
- **Duplication of variable names in separate functions**
- **Variable identifiers must conform to a standard convention:**
  - By convention UPPERCASE is reserved for constants rather than variables.
- **Global variables make it difficult to integrate modules, they increase the complexity of a program:**
  - They may cause conflicts with names written by others/in other modules, and they may be changed inadvertently when the program is complex.
- **Local variables help to make each function reusable.**

## ByVal and ByRef:

- **By value:**
  - A local copy of the data is used
  - Data is discarded when the subprogram exits
  - Does not override/change the original data 
- **By reference:**
  - Memory location of data is sent
  - Changes are made to the original data
  - Changes remain after the subprogram exits

## Function:

- *Example for add item:*
- ![image](https://github.com/RealYusufIsmail/Computer-science-MS-answers-aslevel/assets/67903886/6fae4837-ac1d-4893-8b22-208c9e56ff8b)


## Reusable components:

- **AO1: Knowledge and Understanding:**
  - Program is split into small components 
  - Can identify components that are needed in more than one place
  - Write these as independent modules 
  - They can be imported into other areas of the game 
  - They can be imported into future games that are made 
  - They can be edited and tested independently, then the changes auto-update throughout the program(s)

- **AO2:**
  - Sub-procedure character Movement can be used throughout different levels – saves having to rewrite the code for moving the character
  - Can import sub-procedures e.g. graphics, to save writing these. More likely to be error free as tested

- **AO3:**
   - Will save time (not having to rewrite/test code)
   - Can update one module and it will change all programs that use it – don’t have to change every place the code is written, avoids accidentally missing one
   - Can test independently
   - Can use code other people have written, to save time writing and testing
 
## Programming constructs:

- **Sequence:**
  - Code is executed line-by-line, from top to bottom.
- **Branching:**
  - A certain block of code is run if a specific condition is met, using IF statements.
- **Iteration:**
  - A block of code is executed a certain number of times or while a condition is met. Iteration uses FOR, WHILE, or REPEAT UNTIL loops.
  - Iteration can be either:
    - Count-controlled: Iteration is repeated a given number of times.
    - Condition-controlled: Iteration continues until a given condition is met.

## Type of testing:

- **AO1: Knowledge and Understanding:**
  - Blackbox Use to test the functionality without knowledge of the inner workings 
  - Whitebox Test the algorithms to ensure they do what they were designed to. Does not test functionality 
  - Alpha Internal testing by the programmers before showing to end-user
  - Beta Testing by a third party/end users to ensure it meets requirements and is functional. Helps test usability.

- **AO2:**
  - Discussion of how each strategy would be used in the program
  - She should use alpha testing during the creation to check the processes she is creating.
  - She should use black box testing to make sure the program produces the expected outputs i.e. entering the height, width and depth of a room and it producing these exact dimensions
  - She should use white box testing to make sure the algorithms work, e.g. entering the dimensions of a piece of furniture and then an algorithm calculating if it will fit
  - She should use acceptance testing by showing the software to the end user and walking them through the use of the software to prove it meets all the requirements
  
## Bubble sorts:

- **Knowledge and Understanding:**
  - All adjacent items are compared against each other.
  - The biggest number in the adjacent pair is swapped over with the smallest number. A temp variable is used to hold the data while it’s being moved.
  - When a swap is made a flag is set.
  - This is repeated for all adjacent values, known as one pass.
  - At the end of one pass, the largest item should appear at the end of the list.
  - If at the end of the list, the flag has been set, the flag is unset, and the algorithm starts from the beginning of the list again.
  - When the algorithm gets to the end of the list and the flag is unset, the list is sorted.
- **Application:**
  - As there are 250,000 items a bubble sort would perform very slowly as a lot of passes will need to be made in order to sort the items.
  - Bubble sorts are better suited to data sets where the items are almost/partly sorted. However, the smaller numbers are currently towards the end and the larger numbers are towards the start.
  - This will, therefore, increase the amount of comparisons/passes/swaps required which will, therefore, slow the performance of the sort down.
- **Evaluation:**
  - The algorithm is easy to implement as the number of lines of code is less than other standard sorting algorithms.
  - Although a bubble sort will be able to sort the items into order, it will take longer than other sorting algorithms due to the number of items and the current order or items in the unsorted list.

## Stacks (FILO):

- A stack is Last In First Out (LIFO) 
- Therefore the bookings would be executed from the most recent booking

## Queues (FIFO):

- A queue is First In First Out (FIFO) 
- Therefore bookings will be executed in the order they have received

## IDE:

- Provides a text editor / allows the code to be written
- Provides debugging tools / allows the code to be tested 
- Provides a translator/compiler/interpreter / provides a run-time environment / allows the code to be run 

## Algorithms:

### Binary:
- Works on an ordered set of data 
- Find the mid-point 
- If equal to the mid-point, report found 
- If less than the mid-point, make a sub-list from the left 
- If greater than the mid-point, make a sub-list from the right 
- Repeat with the sub-list until found / sub-list is empty 

### Linear:
- Can work on both ordered and unordered data sets 
- Get the first element 
- If equal, report found 
- If not equal, move to the next element 
- Repeat for all elements until found / end of the list is reached 

## Software methodologies:

| Methodology | Merits | Drawbacks | Uses |
|-------------|--------|-----------|------|
| Waterfall   | Straightforward, documented | Lack of flexibility, limited user involvement | Static, low-risk projects |
| Agile       | Produces high-quality code, flexible | Poor documentation, requires consistent interaction | Small to medium projects with unclear initial requirements |
| Extreme Programming (XP) | High usability, constant user involvement | High cost, teamwork essential | Small to medium projects requiring excellent usability |
| Spiral        | Thorough risk analysis, prototypes throughout | Expensive, lack of focus on code efficiency | Large, risk-intensive projects with a high budget               |
| Rapid Application Development (RAD) | Caters to changing requirements, highly usable product | Poor quality documentation, fast pace may reduce code quality | Small to medium, low-budget projects with short time-frames     |

**Waterfall:**
- Series of stages
- Followed in order
- Can go back up the order
- Then needs to follow back down in order
- Formal, documented stages

**Extrme programming:**
  - Software mythadolgy
  - Focous on realy good quality code
  - Agile model - rapid incrment cycles
  - Quite flexiable. Allows development to change accroding to user requirments
  - Itrative process
  - Invloves paired programmign
  
**Rapid application:**
- Use of prototypes
- No formal analysis, design stages
- More feedback used to influence future stages
- Faster development

**AO2.1: Application**
- Discussion of how the methodologies would support the development
- Discussion of the disadvantages of using each methodology

**AO3.3: Evaluation**
- Candidates will need to consider a variety of viewpoints in relation to testing strategies and will make evaluative comments about the issues and solutions they are discussing
  - The benefits of a method
  - The disadvantages of a method
 
  **Waterfall:**
   - Its not flexiable and limtis change in requirments
 
  **Extrme programming:**
   - High costs  


**Inputs:**
- 1 mark per input, 1 for description
  - w/up arrow[1] 
    - ...to allow the character to move up 
  - s/down arrow[1] 
    - ...to allow the character to move down 
  - a/left arrow[1] 
    - ...to allow the character to move left
  - d/right arrow[1] 
    - ...to allow the character to move right

**Modularity:**
- A module is a set/block of instructions which is given a name which can then be called upon by the main body of code to complete a task(s).
- Program divided into separate self-contained / specific modules or tasks
- Which can be written / tested individually
- Modules can be subdivided further into smaller modules
- Advantages:
  - Modules can be shared between programmers
  - Reduced development time
  - Easier to maintain / debug
  - Modules allocated according to programmers expertise
  - Code can be reused in the project/ future projects
  - Each team member just needs to know what values go into their subroutine and the expected functionality
  - Saves time as work takes place in parallel
  - Each team member can work on their area of expertise
  - Breaks problems into smaller areas
  - Easier to test/ debug/ read
  - Each subroutine can be tested before integration
