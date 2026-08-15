# Anti-MABL

**Axial Neutrality Training Instrument for Microgravity Associated Bone Loss**

Anti-MABL: ML-powered adaptive resistance control system for space-based upper body training machines. Prevents bone degradation in microgravity using real-time fatigue prediction.

**Only the software for this product has been developed, and is in this repo.**
## **Problem**

My project aims to address the health effects of long duration
spaceflight. Even with rigorous exercise, astronauts lose 1-2% of
their bone mass per month in space, Source, a rate that exceeds
osteoporosis on Earth, a bone disease that makes bones more
likely to fracture, even from gentle impacts such as walking.
Source This weakening of the astronaut’s musculoskeletal
system leads to a higher probability of debilitating fractures and a
longer, more intensive post-flight recovery. My project’s purpose
is to mitigate this health risk, improving the safety of space
missions for astronauts.

The biological cause of astronaut
bone loss is a disruption of bone homeostasis – the body’s natural
balance of building new and breaking old bone tissue. In
microgravity, the activity of Mesenchymal Stem Cells (MSCs), cells
that create new bone tissue, is altered. This causes them to inhibit
osteoblasts and produce excess osteolytic cytokines, proteins like
IL-1, IL-6 and TNFα that allow cells to communicate and break
down bone tissue. This means that too much bone is broken down,
and this reduces the astronaut’s bone mass.

## **Design Brief**

This product, designed to complement the ARED, should mitigate
the health risks faced by astronauts from long duration
spaceflight or exposure to microgravity. It will target the weaking
of the musculoskeletal system, particularly in the upper body,
pulling motions and grip strength, helping astronauts maintain
bone mass in these areas, reducing the post-flight recovery time
and the risk of debilitating fractures.

## **Product Research**

ATHLETIC and NEX4EX are both concept
ideas created by the company DLR whereas
iRED and ARED were created by NASA for
use in the ISS. iRED is the precursor of ARED,
the current product used for this major
problem. Built by NASA, this device uses
pistons which move inside vacuum
cyclinders to create resistance, similar to
free-weight on Earth. Both ATHLETIC and
NEX4EX are designed to be exactly the same
as ARED, but compress the size of the
machinery greatly, for use in future missions
with smaller spacecraft.

Whilst analysing these machines, I realised
that they are all the same in terms of the fact
they all focus on lower-body, pushing
motions, neglecting other aspects of the
body, including grip strength and upper body
pulling muscles like the latissimus dorsi and
the rhomboids.

My product is not built to replace these
machines, but to be a specialist tool that can
complement them, allowing astronauts to
not suffer as dramatic a health risk from
space exploration which will continue to
increase extensively in the future

## **Manufacturing Plans, Components, Techniques and Technology**

**Eddy Current Brake**

Eddy current brakes are a type of brake
that use the electromagnetic forces
generated when you induce electrical
currents in a conductive material
slowing it down. These will be used to
provide resistance to the handles in
my product. They are useful as they
have no friction or wear like traditional
cables or other possible alternatives,
allowing them to be smoother and
have a longer lifespan. Additionally,
they are unaffected by extreme
conditions, such as space, which
allows them to function as required.

**Electromagnet**

An electromagnet will allow the
resistance of Anti-MABL to be varied,
so it can suit the needs of different
astronauts. The strength of the magnet
can be increased by increasing the
current through the electromagnet.

**7075-T7351 Aluminium Alloy**

This material is extremely common in
aerospace due to its high strength-to-
weight ratio, its fatigue resistance and
its stress-corrosion-cracking resistance.
The main body of the final product will
be made out of this material.

**Tension Load Cell**

A tension load cell is a type of transducer that
converts the force of tension created by the
pulling motion into a measurable electrical
signal. This will be connected to the handgrip
assembly, so that astronauts can track their
real-time force and power output, which can
allow the product to possibly become auto
adjusting by telling the eddy current brake
how much current to draw, and therefore
how much resistance should be applied.

**Aerospace-Grade Titanium Alloy Bolts**

In order to join the individual parts created by CNC
milling, I must use titanium alloy bolts. These bolts are
non-magnetic and will not interfere with the eddy
current brake system. Additionally, they are extremely
durable and have a high-strength-to-weight ratio.
These bolts will incorporate a nylon insert locknut in
order to secure the bolt and prevent loosening. I
cannot use welding as welding changes the properties
of the material and would ruin the T7351 heat
treatment that gives the aluminium alloy its properties.

## **Risks**

One challenge is the risk of excessive Joule-
heating in the Eddy Current Brake. Joule Heating
occurs when electrical current flows through a
conductor, producing heat as the electrons
collide with atoms in the material, converting
electrical energy into thermal energy. To avoid
this, I should research the use of cooling
mechanisms and potentially an emergency
current cut-off, to prevent excessive heat build
up inside the product, which could harm the
astronauts.

Another challenge is the reliability of the closed
loop control system. To avoid system failure, I
should rigorously test all parts.

## Note

This idea has been scrapped due to cost of parts and processes.
