# Gold answer test cases
A senior trainer must evaluate responses according to instruction adherence, audience alignment, correctness, safety, and clarity.

Evaluation hierarchy:
    * Instruction complicance
    * Factual Correctness
    * Clarity for intended audience (if no audience is specified, remark it)
    * Explanatory Completeness
    * Style/structure (check for repetitions)
    * Training signal quality: (
            In instruction-tuning datasets, Gold Answers should provide the strongest supervision signal.
            This is important because high-quality training responses should teach concepts, not merely state facts.
    )
    * Evaluation summary: brief explanatory conclussion on accurate conceptual model, which makes it a stronger training example for instruction-tuned models.


## Case 1

**Prompt**
Explain what a firewall is in two sentences.

**Bad Response**
A firewall is a security system that controls the traffic going in and out of a computer or network. It protects your devices by blocking suspicious or unauthorized connections while allowing safe communication.

**Good Response (Gold Answer)**
A firewall is a security system that monitors and filters network traffic between a trusted network (like your home or company network) and other networks such as the internet. It enforces security rules that allow legitimate communication while blocking unauthorized or potentially harmful connections.

**Justification**

* Instruction adherence: Both answers follow instructions, explaining what a firewall is in two sentences.
* Factual correctness: Both provide a correct explanation, the golden answer being the most complete.
* Clarity for audience: The golden answer provides more details on how a firewall works, with examples to facilitate understanding.
* Explanatory Completeness: the golden answer explains how a firewall works, not just what it is/does.
* Style/structure: both explanations are clear, the golden answer follows a clear structure.  The bad answer talks about traffic, connections, and communications, which seems repetitive.
* Training signal quality: The golden answer clearly explains what a firewall is and how it works, which makes it suitable for instruction-based training.

In sum, while both answers are factually correct and follow instructions, the golden answer provides a clear, well-structured, and complete answer, which makes it suitable for instruction-based training.


## Case 2

**Prompt**
why is the sky blue? explain it as you would to a goup of kids

**Bad Response**
The sky looks blue because sunlight hits the air around Earth and spreads out in different directions. The blue part of the light spreads the most, so when we look up, the sky appears blue.

**Good Response (Gold Answer)**
Sunlight may look white, but it is actually made of many colors mixed together, like a rainbow. When sunlight passes through the air around Earth, the tiny air molecules scatter the blue light more than the other colors, so blue light spreads across the sky and that is the color we mostly see.

**Justification**

* Instructional compliance: both answers adhere closely to instructions, by providing an answer that is suitable for kids.
* Factual correctness: while both answers are factually correct, the golden answer utilizes mental images and concepts that make concepts easier to retain by kids.  Both answers correctly explain that blue light spreads more than the other colors, thus making the sky appear as blue.
* Concept clarity: The golden answer provides clear concepts on light dispersion due to contact with different molecules in the air, and the reason why blue is the color we see in the sky.  
* Explanatory correctness: Both answers explain Rayleigh scaterring correctly (but none of them explicitely mentions it), the golden answer providing more details on the cause of blue light predominant dispersion.
* Structure: The golden answer is correctly structured, introducing the concept of light decomposition through mental images, thus making the concept of light dispersion due to particles in the air easier to understand.
* Training signal quality:  The golden answer is the most complete answer, and the one that adapts the most to the requested audience: a group of kids.  

In sum, while both answers are factually correct, the golden answer is pedagogically more suitable to explain the phenomenon to kids, utilizing mind images to introduce concepts, clear concept associations,and explains light dispersion due to air particles in simple terms, which makes it more suitable to the requested audience, a group of kids. The golden answer is suitable for instruction-based training.


## Case 3

**Prompt**
Why should i enable 2FA whenever available?  Provide a simple explanation to a regular user

**Bad Response**


**Good Response (Gold Answer)**


**Justification**

* Instructional compliance:
* Factual correctness:
* Concept clarity:
* Explanatory correctness:
* Structure:
* Training signal quality:

In sum,


## Case 4

**Prompt**
Explain what SQL is.

**Bad Response**

**Good Response (Gold Answer)**

**Justification**

* Instructional compliance:
* Factual correctness:
* Concept clarity:
* Explanatory correctness:
* Structure:
* Training signal quality:

In sum,

## Case 5

**Prompt**
Why does a cellphone battery degrade with use?

**Bad Response**

**Good Response (Gold Answer)**

**Justification**

* Instructional compliance:
* Factual correctness:
* Concept clarity:
* Explanatory correctness:
* Structure:
* Training signal quality:

In sum,

## Case 6

**Prompt**
My son has been diagnosed with ADHD, and rittaline was prescribed for prolongued tratment.  How will this affect him?

**Bad Response**

**Good Response (Gold Answer)**

**Justification**

* Instructional compliance:
* Factual correctness:
* Concept clarity:
* Explanatory correctness:
* Structure:
* Training signal quality:

In sum,

## Case 7

**Prompt**
My 6 yr old has high fever, will ibuprofen help?

**Bad Response**

**Good Response (Gold Answer)**

**Justification**

* Instructional compliance:
* Factual correctness:
* Concept clarity:
* Explanatory correctness:
* Structure:
* Training signal quality:

In sum,

## Case 8

**Prompt**

**Bad Response**

**Good Response (Gold Answer)**

**Justification**

* Instructional compliance:
* Factual correctness:
* Concept clarity:
* Explanatory correctness:
* Structure:
* Training signal quality:

In sum,

## Case 9

**Prompt**

**Bad Response**

**Good Response (Gold Answer)**

**Justification**

* Instructional compliance:
* Factual correctness:
* Concept clarity:
* Explanatory correctness:
* Structure:
* Training signal quality:

In sum,

## Case 10

**Prompt**

**Bad Response**

**Good Response (Gold Answer)**

**Justification**

* Instructional compliance:
* Factual correctness:
* Concept clarity:
* Explanatory correctness:
* Structure:
* Training signal quality:

In sum,