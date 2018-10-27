Script
======

Defense script, with slide transitions and action call outs included.


Begin Defense
-------------

Title Slide

    Good afternoon. Today I will be discussing the uses of recoil
    separators to study reactions in nuclear astrophysics, what must be
    done to prepare the recoil separator for experiments, and the first
    experimental results in support of commissioning the St. George
    recoil separator.

Introduction

    First, I'll discuss the motivation behind using a recoil separator
    in the first place

Prominent Reaction Processes

    The reactions that contribute to stellar energy production are
    determined by the conditions in the stellar interior. These
    conditions include the isotopic enrichment, temperature, pressure,
    and so on. In stars similar to our sun, the primary sources of
    energy generation are through the pp-chain and CNO cycles.

    Both of these reaction sequences have the same final effect: fusing
    four Hydrogen nuclei into a single Helium nuclei. The individual
    reactions that take place, however, are different. Within these
    sequences, radiative proton capture reactions play a dominant role.
    Within the CNO and other cycles, there are also cases where
    radiative alpha capture reactions can provide a "breakout" to
    different reaction sequences.

    These reactions can be grouped under Hydrogen burning processes.

Hydrogen Burning

    In higher mass stars, we commonly see burning cycles like these,
    where the net effect of any one cycle is to convert four Hydrogen
    into one Helium. The CNO cycles on the left are common in stars
    similar to and slightly larger than our Sun, while the more exotic
    cycles on the right take place in heavier and hotter stars.

    These cycles contain the proton capture reactions as well as the
    "breakout" radiative alpha capture reactions that can transition the
    burning between two burning cycles. There are many other burning
    chains and cycles that are possible within stars, so this is just
    one prominent example.

Radiative Capture

    These radiative capture reactions are extremely important for
    understanding the interiors of stars, and have historically been
    measured with gamma detectors. Due to the low efficiency and the
    background count rate, both from nature and any contaminant material
    in the target used, there detections may be difficult or impossible
    to observe, depending on the underlying cross section and the energy
    of the produced gamma. The focus then has been on the resonances
    within the cross section, those points that dominate the reaction
    rate for stellar interiors. Those off-resonance contributions,
    however, can play a large role, especially in cases where no
    resonance plays a dominant role.

Inverse Kinematics

    We would like to get around the limitations of gamma detection and
    gain the ability to measure off-resonance parts of the cross
    section. One way we can do that is through performing the reaction
    in inverse kinematics, where instead of a light particle impinging
    on a heavy target, we direct a beam of the heavy particle onto the
    light target, in our case a hydrogen or helium gas target. The
    produced heavy recoil leave the target and can be detected by a
    high-efficiency particle detector, such as a Silicon strip detector.

    The complication here is that, especially with the off-resonance
    measurements, the count rate of the produced recoils is very low
    when compared against the potential count rate of the incident beam,
    where a difference of 10^15 particles per second could be possible.
    We need a way to stop the incident beam from reaching the detector,
    and for that...

Recoil Separation

    ...we can use a recoil separation technique to filter out those
    incident beam particles and leave us with only the produced recoils
    that we care about.

St. George

    St. George, or the Strong Gradient Electromagnetic Online Recoil
    Separator for Capture Gamma-ray Experiments, is a recoil separator
    in the Nuclear Science Lab at the University of Notre Dame. It is
    designed to study radiative capture reactions performed in inverse
    kinematics in the low mass range, with the original design looking
    at a set of potential reactions with incident beam mass up to
    `A = 40`. Consisting of eleven quadrupoles, six dipoles, and a Wien
    filter, St. George can provide beam suppression up to 10^15 and
    direct those few produced recoils to the detector plane with an
    angular acceptance of 40 mrad and an energy acceptance of 7.5%.

    St. George accomplishes this recoil separation by making use of...

Magnetic and Electric Rigidities

    ...the magnetic and electric rigidities of the particles in
    question. These rigidities are defined by the circular path a given
    particle would take within a uniform field of a given type, and are
    related to the particle's mass, charge, and energy. The rigidity of
    a particle and the designed bending radius of an element will
    determine what field strength is required for that particle.

    It makes more sense, however, to talk in terms of...

Particle Selection

    ...particle selection, where we want to select out a unique particle
    that has particular properties, namely the mass-to-charge ratio and
    the energy-to-charge ratio. We have three different field types
    possible, namely isolated magnetic or electric field, or crossed
    fields where the magnetic and electric fields are trying to bend
    the particle in opposite difrections, also known as a Wien filter.

    Alone, none of these can uniquely identify a particle, but...

Particle Selection

    We can use any two of the three in combination to select for a
    single particle. This is one of the driving forces behind the design
    of recoil separators like St. George. In our case, St. George uses
    magnetic dipoles for momentum selection and a Wien filter for
    velocity selection, which has the combined effect of selecting for
    a single mass. As our recoils leave the target with a single mass,
    we can accomplish our goal of selecting for our produced recoils.

Angular and Energy Acceptance

    Our problem is that, while the particles leave the target with a
    single mass, the do not leave at a single energy and not necessarily
    along the central axis for our electromagnetic elements. A recoil
    separator must also transport those produced recoils within a given
    angular and energy spread to the final detector while still
    rejecting the incident beam. The range of possible values are the
    acceptances for the separator.

Importance of Acceptances

    In an ideal case, every single recoil particle that is produced by
    the reaction within these bounds would make it to the detector plane
    which would eliminate the separator as a potential source of
    uncertainty for the final measurement. Since there may be very few
    recoild produced, depending on what part of the cross section is
    being measured, this ideal case becomes more important, so a lot of
    care and effort must be made to ensure that the designed acceptances
    for the separator hold for all possible recoil particles that could
    be produced.

Commissioning

    This process is called commissioning, where the characteristics of
    the separator are explored and determined through a variety of
    methods to ensure that the separator will work as it was designed to
    do under experimental conditions.

Types of Commissioning

    We can break the commissioning steps up into three possible cases:
    the energy commissioning, where we test out different enegies for a
    single tune of the separator to see which make it to our final
    detector; the angular commissioning, where the particles that enter
    St. George are angled from the central axis to determine what the
    angular acceptance is; and a joint commissioning, where we've
    changed both. This last case is what will happen in real
    experiments and what we are aiming for, but the goal is the same
    for all three case.

    We want to get 100% of our produced recoils to the final detector
    plane during an experiment, so 100% of the particles we use for the
    commissioning work should also make it to that final detector plane.

Energy Acceptance

    We first looked at the energy acceptance, as the measurements
    requried were less complex. For given test beams, selected to cover
    the rigidity phase space for St. George near where the produced
    recoils for astrophysically-important reactions would be, we checked
    if a single tune, or a single setting of all of the electromagnetic
    elements of St. George, could transport our test beam to our final
    detector, and we showed for eight such beams an energy acceptance of
    8%, which is past the design limits.

    This is good, but we still need the angular acceptance, and after
    a short campaign to attempt to measure the full angular acceptance,
    we transitioned to measuring...

Joint Acceptance

    ...the joint acceptance.

    Initially, we used a degrader foil to provide a small joint angular
    and energy spread which we would tune St. George to transport that
    beam to our desired focal plane. This technique has its own set of
    complications, especially that our spread beam becomes harder to
    detect in the tails of the distribution, complicating the procedure.

    Instead of running a test beam for these cases, we can get closer to
    the final situation by...

Reaction Measurements

    ...actually performing a well-known reaction to determine the
    acceptances. This choice shouldn't be done before the other two,
    since the tuning procedure relies on understanding the separator
    enough to actual be able to tune it properly.

Justification for Reaction Measurements

    All of our possibilities to get to a joint acceptance are costly in
    terms of time and effort, but our direct reaction measurements can
    help in that regard. With an understood angular and energy spread
    and a known cross section, we know what, in terms of particle counts
    at the detector, we need to see. The idea is to tune the separator,
    run the reaction, and calculate the acceptances based on what is
    known about the reaction itself. Performed enough times and over
    a range of rigidities, we can more quickly get to a situation where
    we trust that St. George can be tuned for its full acceptance for
    any reaction.

The ALPA Reaction

    Our first reaction measurement is the ALPA reaction, performed
