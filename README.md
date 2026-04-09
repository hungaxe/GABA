# GABA
Geometric Algebra as Big-integer Algebra, and Binary GABA ↔ Simplicial Homology


====================================

# Abstract 

**Mini abstract**

**Why do we need GABA? The question arises.**

1.1 Two core issues in graphics and robotics programming

When you're working on 3D games, designing robots, or creating computer graphics, you constantly need to:

Rotate, move, and project millions of points, lines, and planes in space.
Check for collisions: Do two objects touch? Is a point inside a sphere?

Problem 1: Floating-point error. Computers don't store real numbers like 0.1 perfectly accurately—they only approximate them. After hundreds of consecutive multiplications/divisions, the error accumulates. The consequences: robots get lost, polygons in games become "open." This is a real engineering disaster.

Problem 2: Uneven memory access. Modern CPUs/GPUs are most powerful when processing sequential, regularly structured data. Traditional geometric algebra libraries store objects as scattered arrays of real numbers—not taking advantage of parallelized SIMD/ASICs.

The core idea of ​​GABA :

Instead of using real numbers, use integers. Instead of storing each geometric object as a separate array, **wrap the whole thing in a single large integer.** Instead of looking up complex multiplication tables, **use XOR (one of the fastest CPU operations).**


1.2 Processing-as-Comparison (PCP) Principle

Paper put forward a philosophy called the Processing-as-Comparison Principle:

"The ultimate goal of any processing pipeline is to transform input into a suitable form for comparison. **Two expressions, 1+1+1 and 1+2, are considered equal if and only if they are equal to the same integer 3.**"

Applying this to geometry: two geometric scenes A and B are geometrically equivalent ⟺ **their standard SInts are equal.** This reduces the geometric comparison problem to **a single integer comparison—a single machine instruction!**



====================================


# Access


**Disclaimer** : At the time of 06/04/2026 (DD/MM/YYYY), this work is an early-stage theoretical exploration developed independently by a student researcher. Due to practical constraints, the current version focuses on conceptual formulation and preliminary validation. The author welcomes feedback, critique, and collaboration from the community.



**Small warning :** I recommend that you only read what I have written here (README.md), the links here, you can click on them to read the details. You can view the files in the folders in my repository, but I do not recommend it.



**Major languages:** English, Vietnamese;

**Recommended reading (Paper):** 


Core Idea A : https://github.com/nahhididwin/GABA/blob/main/files/content/id07.txt ;

Core Idea B : https://github.com/nahhididwin/GABA/blob/main/files/content/trypostid/pid0.7.txt ;



Beta 2.0 :

(Main paper) https://github.com/nahhididwin/GABA/blob/main/files/papers/paper2.docx ;

(Supplement) https://github.com/nahhididwin/GABA/blob/main/files/papers/suppleforpaper2.docx ;

Alpha 1b : 

https://github.com/nahhididwin/GABA/blob/main/files/papers/paper1b.docx ;



====================================



# Author 

Full name : Hung Dinh Phu Dang (Đặng Đình Phú Hưng)

First Name: Hung

Middle Name: Dinh Phu

Last Name (Surname): Dang

Nation : Vietnam

City : Ho Chi Minh City

Date of birth: 20/06/2011 (DD/MM/YYYY)

Github : https://github.com/nahhididwin

====================================


# License and Warning 

License : https://github.com/nahhididwin/GABA/tree/main?tab=License-1-ov-file

Repositories Public Date https://github.com/nahhididwin/GABA/ : 04/04/2026 (DD/MM/YYYY)

WARNING : At the time of 06/04/2026 (DD/MM/YYYY), this work is an early-stage theoretical exploration developed independently by a student researcher. Due to practical constraints, the current version focuses on conceptual formulation and preliminary validation. The author welcomes feedback, critique, and collaboration from the community.


