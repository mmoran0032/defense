# Script

Last updated: 2018-11-05

Script for my defense to make sure that I know what I'm saying and can
practice it. I don't want to miss anything during the presentation.

*Note:* the below reflects the status before the dry run with Manoel and
Michael. There are some new slides and others removed, so the below does
not represent the current presentation but can be used as a guide.

## Title Slide

Good afternoon.

My name is Michael Moran.

I want to thank you for coming to my doctoral defense.

Today I will be giving a brief presentation about my work with the St.
George recoil mass separator.

There will be time at the end of the presentation for any questions you
may have.

## Introduction

First, I'd like to discuss in what situations we would want to use the
technique of recoil mass separation to study reactions for nuclear
astrophysics, and what benefits it gives us over other options.

### Capture Reactions

In the primary burning processes that govern the energy production in
stars, different capture reactions are common.

The actual reactions that take place depend on the properties of the
star, such as the temperature and pressure of the stellar interior, the
isotopic enrichment of the burning site, the mass of the star, and the
particular stage of its lifecycle that the star is in.

For stars similar to our sun, the primary energy source is Hydrogen
burning, which has the net effect of converting four protons into one
Helium nucleus.

For our sun, the pp chains dominate this energy production.

For more massive stars, this burning is accomplished through cyclic
burning cycles, such as the CNO, NeNa, and Magnesium-Aluminum cycles,
where the heavy isotopes act as catalytic material for the burning
process.

Once the Hydrogen fuel is exhausted, Helium burning takes over.



Many of these reactions are...

### Radiative Capture

...radiative capture reactions, such as (p,g) and (a,g) reactions.
Historically, these have been studied by detecting the produced gamma
ray, but thhis can be difficult for a number of reasons.

For instance, there may be large background count rates due to natural
background or impurities in the target used, there could be an overall
low count rate due to the cross section, and we are limited by the
detector efficiency.

All of this combined means that the focus has usually been on the
resonances in the cross section, those regions where the probability of
the reaction taking place is greatly increased. The off-resonance
regions can still contribute greatly to our understanding of the
reaction, especially in situations where no resonance contributes to
the reaction in stellar interiors, so we need a method to measure the
cross section in those regions.

### Inverse Kinematics

An alternate to detecting the produced gammas is to detect the heavy
particle instead, which avoids the limitations just described by using a
high efficiency detector with low background counts.

One way we can do that is through performing the reaction in inverse
kinematics, where instead of a light particle impinging on a heavy
target, we direct a beam of the heavy particle onto the light target, in
our case a hydrogen or helium gas target. The produced heavy recoils
leave the target and can be detected by a high-efficiency particle
detector, such as a Silicon strip detector.

Our incident beam will also pass through our target. We need to stop
this beam from reaching out detector, both because the high count rate
would swamp our signal and it could destroy the detector itself.

One technique to do this and not interfere with the produced recoils
is...

## Recoil Separation

...to use recoil separation, where our rarely produced recoils are
separated out from the incident beam such that only those recoils
reach the detector. This is accomplished by using a recoil separator,
such as...

### St. George

...St. George, or the Strong Gradient Electromagnetic Online Recoil
Separator for Capture Gamma-ray Experiments.

St. George is a recoil separator in the Nuclear Science Lab at the
University of Notre Dame, designed primarily to study radiative alpha
capture reactions performed in inverse kinematics in the low mass range.
It consists of eleven quadrupoles, six dipoles, and a Wien filter to
separate out the recoils based on their mass, and its design was
influenced by previously built recoil separators, such as DRAGON or ERNA
or DRS.

St. George achieves the separation of the recoils from the beam by being
set for...

### Magnetic and Electric Rigidities

...the magnetic and electric rigidities of the recoils in question.
These rigidities are defined by the circular path a given particle would
take within a uniform field of a given type, and are related to the
particle's mass, charge, and energy. The rigidity of a particle and the
designed bending radius of an element will determine what field strength
is required for that particle. St. George was designed to transport
particles to its final detector plane within a given range of rigidity
values.

It makes more sense, however, to talk in terms of...

### Particle Selection

...particle selection, where we want to select out a unique particle
that has particular properties. We have three different field types
possible, namely isolated magnetic fields that select for a single
momentum, isolated electric fields that select for a single energy, or
crossed magnetic and electric fields, called a Wien filter, that selects
for a single velocity.

Since we know the properties of our recoil, we can figure out its
rigidity and use these fields to select for the given properties.

### Particle Selection (2)

Note: *Think about converting the plot into Bp-Ep space*

We can use any two of the three in combination to select for a single
particle. This is one of the driving forces behind the design of recoil
separators like St. George. In our case, St. George uses magnetic
dipoles for momentum selection and a Wien filter for velocity selection,
which has the combined effect of selecting for a single mass. As our
recoils leave the target with a single mass, we can accomplish our goal
of selecting for our produced recoils.

### Angular and Energy Acceptance

Our problem is that, while the particles leave the target with a single
mass, the do not leave at a single energy and not necessarily along the
central axis for our electromagnetic elements. A recoil separator must
also transport those produced recoils within a given angular and energy
spread to the final detector while still rejecting the incident beam.
The ranges of values arise from the kinematics of the reaction itself
and the interaction of the produced recoils with the target.

The range of possible values are the acceptances for the separator and
must be verified experimentally across a range of rigidity values.

### Importance of Acceptances

Having these acceptances hold for a variety of value sis important,
because we want to eliminate St. George as a potential source of error.
We are trying to show that any produced recoil will make it to the final
detector system, and ideally none of the incident beam particles. Since
those recoils may be emitted from the target with a wide range of values
based on the kinematics of the reaction, that's also why we have our
acceptances.

Showing the acceptances hold is extremely important once we start
performing reactions, where those extremely rare recoil particles can be
vastly outnumbered by the incident beam. When measuring off-resonance
regions of the cross section, this becomes even more important due to
the lower count rates.

Since every single combination of rigidities can't conceivably be
verified independently, we'd like to verify the acceptances at enough
different values so that we can scale St. George between those values.
If we've done this properly, St. George will retain its acceptance
properties at the new values.

The process of actual probing the parameter space is called...

## Commissioning

...commissioning the separator, where we verify that the separator will
work as it was designed to do under experimental conditions.

### Types of Commissioning

Our goal for commissioning is to transport 100% of the particles to the
final detector plane. For an experiment, these particles will be the
produced recoils, but for commissioning work they may be a direct beam.

We can break the commissioning steps up into three possible cases, where
for each case we are varying some property of the particles while
keeping the field strengths in our recoil separator the same. They
are...

...the energy commissioning, where we test out different enegies for a
single tune of the separator to see which make it to our final
detector...

...the angular commissioning, where the particles that enter St. George
are angled from the central axis to determine what the angular
acceptance is, and...

...a joint commissioning, where we've changed both.

This last case is what will happen in real experiments and what we are
aiming for, but the goal is the same for all three case.

### Energy Acceptance

Our group first attempted to measure the energy acceptance through the
entirety of St. George. To determine this acceptance, St. George was
tuned for the rigidity of a test beam produced by the 5U accelerator.
The beam current was measured at the entrance and final focal plane of
St. George to determine if 100% of the beam was transmitted, and if so,
the beam energy was varied within the expected energy acceptance to see
if the tune also transmitted 100% of the beam at the slightly deviated
energy.

This was an iterative process, as if the tune did not transmit the
entire beam, the tune for St. George would need to be adjusted.

### Energy Acceptance (2)

For eight different test beams with eight different rigidities, we
showed that St. George would accept an energy deviation up to 8%, which
is above the design limit of 7.5%.

The given test beams were selected to cover the rigidity phase space for
St. George near where the produced recoils for astrophysically-important
reactions would be. Again, this does not cover the entire parameter
space, but we can scale the separator between these points and be
confident that our acceptance value hasn't changed dramatically. In
fact, this scaling was the first step when moving from one point to the
next which forced our baseline tune to be similar across a range of
values.

### Angular acceptance



## Joint Acceptance

...the joint acceptance.

The joint acceptance is closer to what we will see experimentally, where
the produced recoild have both an angular and energy spread as they
enter St. George. We first attempted to use a degrader foil and tune the
beam in the same way as the energy acceptance measurements, but we ran
into some complications in our experimental procedure.

Instead of running a test beam for these cases, we can get closer to the
final situation by...

## Reaction Measurements

...actually performing a well-known reaction to determine the
acceptances. This choice builds on the previously accomplished work, but
due to the nature of the commissioning work we were confident that we
could attempt this solution.

## Justification for Reaction Measurements

All of our possibilities to get to a joint acceptance are costly in
terms of time and effort, but our direct reaction measurements can help
in that regard. With an understood angular and energy spread and a known
cross section, we know what, in terms of particle counts at the
detector, we need to see. The idea is to tune the separator, run the
reaction, and calculate the acceptances based on what is known about the
reaction itself. Performed enough times and over a range of rigidities,
we can more quickly get to a situation where we trust that St. George
can be tuned for its full acceptance for any reaction.

## The ALPA Reaction

Our first reaction measurement is the ALPA reaction, performed in
inverse kinematics. As an initial test, we focused on two low-lying
resonances, both of which are 2+ states with an isotropic angular
distribution. I'm not showing all of the states here, just the two that
we are interested in. The angular distribution is really important,
since we are only measuring the reaction at zero degrees. If we look at
the differential cross section around these points...

## The ALPA Reaction

...at zero degrees, we can see additional structure within the cross
section that we will be able to probe. Our two resonances are relatively
isolated, so with the energy resolution of our accelerator, we'll be
able to measure this underlying structure. Having a known cross section
is important, since we will need to use it to determine the expected
number of particles.

While this cross section is for zero degrees, due to our angular
acceptance of 40 mrad, we can assume that the structure is the same for
that small angular window.

## Alternate Tune

At the time we ran this experiment, the entirety of St. George had not
been commissioned yet. From our previous work, we had a really good
understanding of the energy acceptance properties of the separator, but
our angular acceptance had only been shown to be 40 mrad up to the focal
plane following the Wien filter. At this location, the canonical tune of
St. George is a tall, narrow spot for the transported recoils, which
means that some of the produces alpha particles would fall off of the
detector.

Instead, we developed an alternate tune...

## Alternate Tune

...that would transport the particles within a smaller energy acceptance
window of 4% and the full 40 mrad angular acceptance to this new
detector plane, where the beam spot would fall on the active surface of
the Si detector in both the horizontal...

## Alternate Tune

...and vertical plane.

## Angular Acceptance Measurement

As already mentioned, the alpha particles are emitted in all directions,
so we rely on the physical target chamber to restrict what particles
enter St. George. The Faraday cup at the entrance to the separator will
restrict our angular acceptance. While this measurement will result in
an angular acceptance for a different tune than the canonical St. George
recoil transport tune, the techniques and procedures are 100% applicable
to the full case.

## Acceptance Measurements

Our actual experiment explored ten total energy points within the cross
section, focusing on those two resonance areas. Our on-resonance
energies here and here show, understandably, the smallest uncertainty
and are consistent with the tuned 40 mrad acceptance, which is great.
From our analysis, we also have the benefit of attributing these
uncertainty bands, here the 67% and 95% bands, to each of the inputs
that are under our "control" to direct the actions that should be taken
at different points in the cross section during future directions. For
instance, these two points just below the resonance energy show the
largest uncertainty, and almost all of that uncertainty can be
attributed to the energy uncertainty of our incident beam. Our
on-resonance points are dominated by the current uncertainty, which is
partially limited by our experimental setup.

The last thing to note is that there is a systematic shift at lower
energies to higher acceptances. During previous studies, it was common
to have a much easier time to reduce the vertical acceptance to 40 mrad
or above, but much more difficult to do the same in the horizontal
direction. Since we are assuming a uniform angular acceptance, we can't
adequately separate out the two directions which may lead to this shift.
The fact that our on resonance points agree with a symetric 40 mrad
acceptance in comforting, since the transport tune was checked
beforehand with a direct alpha beam near these points.

## Future Directions

This experiment is not the end of the line for the commissioning of St.
George, which I expect to continue in various capacities and
periodically rechecked over the coming years.

## Experimental Outcome

We have shown that St. George can accept recoils produced within an
energy window of at least 7.5%, and within a combined angular spread of
40 mrad with an energy spread of 3%. With the note that this last
acceptance measurement was for a different tune, St. George has been
shown to be capable of measuring 6 of the 8 test reactions outlined
within the 2008 design paper by Couder et al. Additionally, even though
St. George was not directly designed to study (p,a) reactions, we've
demonstrated that the acceptance properties and the beam rejection
properties are sufficient to study this additional class of reactions.
There is already interest within the NSL and collaborations for this
capability, and using St. George for these reactions will work both for
novel studies as well as supporting experimental work for other
experimental areas within the NSL.

## The Future of St. George

We've shown that St. George can be used for the (p,a) experiments in
this configuration, and there is already growing interest to use St.
George in this capacity to augment the work at other experiments. Our
ability to fine tune the separator is also essential for future work,
and the built-up knowledge of how the separator performs will continue
to build on itself to improve future work.

Some of the procedures and diagnostic equipment that were developed
during this commissioning work have already had an influence on the next
generation of recoil separators, namely SECAR at Michigan State
University. Since the design of SECAR was influenced by the design of
St. George, it makes sense that the separator can also be helpful in
this regard.

Finally, the last parts of the full St. George system, namely the HIPPO
supersonic gas target which provides the He target for (a,g) reactions
and the full detector system, of which we only used a part of, are
coming online. As those last systems are commissioned themselves, we
will have unlocked the full potential of St. George for making ground
breaking strides in nuclear astrophysics.

With that, thank you for your time, and I look forward to your
questions.
