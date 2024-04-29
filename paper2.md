# This readme can not and is not allowed to be redstrubuted for any means without the owners approval or by inserting the license in the content used.

# If this is found to be breached then action will be taken.

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
- **A global variable used where a value needs to be
accessible from various parts of a program (1 – AO1.2), it is
the same value (1 – AO1.2).
Irrespective of the place where it is accessed (1 – AO1.2).
Any sensible example of a value that will reasonably need
to be the same, e.g. today’s date, VAT rate, pi (1 – AO2.1)**

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
