# Anti-MABL
### Axial Neutrality Training Instrument for Microgravity Associated Bone Loss

Anti-MABL is an ML-powered adaptive resistance control system designed for space-based upper-body training machinery. It mitigates bone degradation and musculoskeletal atrophy in microgravity environments using real-time fatigue prediction.

---

## Awards & Competition Recognition

This project was entered into the Big Bang Competition and the TeenTech Awards, receiving appraisal from judging panels, veteran aerospace engineers, and industry experts.
(Complete feedback for future reference)

> **Big Bang Competition Panel**
> Congratulations on an absolutely outstanding project! We were hugely impressed by Anti-MABL and the ambition, imagination and technical skill you showed throughout your work.
>
> Your project has clearly identified a genuine and under addressed problem - musculoskeletal and bone density loss in astronauts’ upper bodies during spaceflight—and the creative, evidence-based solution devised to tackle it. The project’s strengths lie in its rigorous approach, including thorough research, advanced computational analysis and material selection. The use of 3D CAD modelling and simulation is notable, demonstrating strong technical competence and a willingness to learn and apply advanced skills. The dedication to problem-solving, technical mastery, and future-focused thinking makes this project particularly impressive.
>
> The most exciting, and ambitious, next step is to develop of a functional prototype and obtaining user feedback from astronauts or medical professionals. This would provide valuable insights for further refinement and product evolution. Exploring advanced manufacturing methods, enhancing the machine learning component, and considering applications for Earth-based rehabilitation could further expand the project’s impact and effectiveness, which is really exciting!
>
> Your project stands out for its innovative approach, technical depth, and clear dedication to solving a real-world problem. Your willingness to explore complex concepts and embrace creative solutions is truly impressive—keep nurturing that curiosity and drive, particularly your interest in space and your desire to improve the wellbeing of astronauts. You never know, some day you be be one. Your project has made me more aware of the issue, particularly as we look at longer periods of space travel.
>
> I look forward to seeing where your future research and development take you. 



> Firstly, may I say that I've worked in the Aerospace Industry for 40 years and you have taught me a number of new things!  Thank you for that.  You've learned a lot and taught yourself new skills in order to put this project together.  You've done some challenging research too.  Your passion shines through and this shows you have the drive to become a great Scientist or Engineer going forwards.  Keep working at these skills; they will serve you well in the future.
>
> As a next step, I think you should consider sending your ideas to NASA! I've heard of students in the past who have received encouraging replies, and even if you don't hear back, you will know that you may have given someone there some thoughts and ideas.
>
> You have done a lot of work here on a topic that is quite specialist, and it is good well thought out work.  Very well done!  Like you, I'll be following the progress of Artemis, and hopefully seeing the success of Artemis II in April.  Well done to you - very good work! 



> This is a really impressive project, so congratulations, you’ve clearly put a lot of work into it!
>
> You set yourself up for success by carrying out excellent background research, meaning you had a thorough understanding of what products currently exist in this area, and could identify a gap in the market.
>
> Your design and analysis work is particularly impressive - you have achieved a high level of technical detail in all aspects of the project, and have clearly understood how such a device would work in practice, especially in the complex environment of space. Your use of FEA is also very impressive and a good way of testing that your design could withstand the kinds of forces it would expect to experience, so really well done! Testing a real prototype could be a challenge given the need to replicate the space environment - have you thought about how other existing products achieve this, and what facilities you might need access to?
>
> I really like your idea of incorporating machine learning, that sounds like a very valuable future development!
>
> Overall, well done for a very thorough and well thought out project, in a very interesting area. Your passion and attention to detail are commendable and I wish you all the best for the future, hopefully a successful career in engineering!
> Really brilliant and inspiring work, well done! 


> **TeenTech Award Panel**
> What an incredible journey you have been on with this project. The longevity of your project and the
extensive, detailed and complicated research you have carried out is extremely impressive and
displays tenacity, analytical thinking and attention to detail.
>
> I admire your proactiveness, bravely reaching out to numerous
researchers, university professors and industry experts to develop your knowledge of the complex
technology and science within your design. I am commend the extensive research from multiple
sources and how have applied this to your design. Your project submission is very detailed and your
communication is both excellent and knowledgeable, enabling clarity and clear design progression. I
would love to see you realise your design as it has real promise, due to all your hard work. You have
superbly executed your innovation design within this submission, with a lot of thought and effort.
This project has real potential and I am excited to see where you take this next. It is clear from your
reflections that you have learned a lot through this process and this is the building blocks for your
future career, keep going exactly as you are. Well done on creating something that has the potential
to genuinely help protect the bones of our future astronauts!



> This is a really impressive project that demonstrates a strong level of maturity in both your thinking
and execution. You’ve identified a clear problem and developed a unique solution. It’s great to see
how you’ve built on existing ideas and found a genuine gap.
Your research is a real strength. Speaking to experts and clearly showing what you learned from
them, and your timeline and process are very well organised. I particularly enjoyed following your
journey from discovery through to development and iteration - it shows thoughtful and reflective
design process.
>
> Overall, this is an excellent project that seems to address a genuine gap and challenge. I particularly
enjoyed your reflection on how your view of engineering has evolved with this project from making
things to solving meaningful problems. For me, this suggests a strong foundation for a future career
in design and engineering. 

---

## The Problem

* **The Rate of Atrophy:** In microgravity, astronauts lose **1–2% of their bone mass per month**. This rate drastically exceeds terrestrial osteoporosis, leaving astronauts highly susceptible to debilitating fractures and demanding an intensive post-flight recovery period.
* **The Biological Cause:** Microgravity disrupts internal bone homeostasis. The altered environment suppresses Mesenchymal Stem Cells (MSCs), inhibiting osteoblast formation while triggering an overproduction of osteolytic cytokines (**IL-1, IL-6, and TNFα**). This communication failure causes the body to aggressively break down bone tissue without rebuilding it.
* **The Current Hardware Gap:** Existing ISS countermeasures like NASA's ARED, alongside concept designs like DLR's ATHLETIC and NEX4EX, focus almost exclusively on lower-body, pushing motions. They neglect upper-body pulling muscle groups (e.g., *latissimus dorsi*, *rhomboids*) and grip strength.

---

## Design Brief

Anti-MABL is engineered not to replace current equipment, but to serve as a specialized, compact complementary system.
* **Target:** Upper-body pulling biomechanics and grip strength retention.
* **Objective:** Deliver maximal muscle loading across a full range of motion.
* **Goal:** Protect musculoskeletal health to minimize post-flight recovery times.

---

## Manufacturing, Architecture & Components

### Eddy Current Brake
* Utilizes electromagnetic forces induced via electrical currents in a conductive material to generate resistance.
* Operates completely frictionless, eliminating mechanical wear and extending operational lifespans.
* Impervious to extreme space-bound environmental conditions.

### Electromagnet Control
* Allows fully variable resistance profiles tailored dynamically to individual user baselines.
* Resistance scales predictably with the current fed through the electromagnet array.

### 7075-T7351 Aluminium Alloy
* High strength-to-weight ratio with superior fatigue and stress-corrosion-cracking resistance.
* Selected as the primary substrate for the main structural body.

### Tension Load Cell
* Converts raw pulling force into a measurable electrical signal.
* Integrated into the handgrip assembly to capture real-time force and power metrics, closing the feedback loop with the Eddy Current Brake.

### Aerospace-Grade Titanium Alloy Bolts
* Non-magnetic fasteners that do not interfere with the electromagnetic fields of the braking system.
* Paired with nylon-insert locknuts to prevent vibrational loosening.
* Replaces welding to completely preserve the critical T7351 heat-treatment properties of the aluminium frame.

---

## Risk Management & Safety Engineering

* **Joule Heating Mitigation:** High-current flow through the Eddy Current Brake induces conversion of electrical energy to thermal energy. Future iterations require active cooling blocks paired with a hardware-level emergency current cut-off to shield users from excess heat.
* **Control Loop Redundancy:** Closed-loop systems carry the risk of algorithm overshooting. Rigorous physical testing profiles must be paired with mechanical safety relief overrides to prevent dangerous structural overloading if the machine learning calculations error out.

---

## Expert Feedback & Acknowledgements

This project would not have progressed nearly as much without the help of various individuals, labs and companies who offered their feedback and advice.

I would like to thank the following:

* **Dr Maria Parkes** | *Principal Teaching Fellow & BME Programme Lead, Department of Bioengineering, Imperial College London*
  
* **Dr Davide Piaggio** | *Assistant Professor in Biomedical Engineering, School of Engineering, University of Warwick*

* **May Orogi** | *Arxfit*

---

### Project Status Note
*The physical hardware development of this project was paused due to the high financial costs associated with aerospace-grade manufacturing processes and specialist components. The machine learning control script and architectural research are preserved openly in this repository as an active portfolio piece.*
