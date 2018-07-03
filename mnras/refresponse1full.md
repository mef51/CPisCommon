We are grateful to the referee for the helpful recommendations and comments. Below are the referee's comments (in quotes) followed after each point by our response.

Assistant Editor's Comments:
Editor
Comments to the Author:
"Please ensure that all textual labels in figures are at least as large as the caption text; any smaller and they become too difficult to read."

Response: Most figure and axes labels are now larger

Reviewer's Comments:
Reviewer: 1
Comments to the Author
Report on MN-18-1764-MJ
-----------------------
"The paper is well argued, and shows a plausible explanation for non-Zeeman
circular polarization found in molecular spectra. I set out below some
recommendations that I believe would improve the paper.

Introduction, p1, end of 1st column: It would probably be useful to just
add a few lines of explanation about the GK effect. It appears to be
transfer of polarized radiation through a Zeeman-split medium in the
case where the Zeeman splitting frequency is larger than the rate of
all processes except the Doppler width of the spectral line.
A statement similar to the above would make the paper more self-contained,
and only the more interested reader would need to look up the original
GK paper."

Response: Added the following explanation of GK in the introduction:
The GK effect can occur when a molecule
with even weak Zeeman splitting is in a medium with
some anisotropy and the splitting frequency is greater
than the collisional rate and other misaligning processes.
These conditions can cause a population imbalance in
the levels of the split lines that results in a net LP aligned
either perpendicular or parallel to the plane-of-the-sky
component of the magnetic field.

Section 2
---------
"Obviously, at the frequencies considered in the manuscript, one's choice
of telescope is very limited, and it is rather unfortunate for this work
that both the SMA and ALMA are equiped with linear feeds. If the authors
are aware of any similar observations, probably at lower frequencies, where
additional non-Zeeman circular polarization profiles and/or images have been
obtained with telescopes equiped with circular feeds, I feel that a
reference to that work would add considerable weight to the argument, since
the calibration process is much less replete with sources of error."

Response: While there seem to be several VLA and VLBA observations of CP I believe the most relevant work is that by Cotton etal. 2011 using the VLBA. The VLBA is equipped with off-axis circular feeds and they used a very similar squint correction as the one we detail. I added a paragraph to the ends of Section 2 and Section 5.1 to highlight this. Other relevant observations (like Hezareh etal. 2013) used linear feeds.

Definition of Stokes-V
----------------------
"On line 4 of Section 2.1, Stokes V is written as 'left'-'right'. However,
in the next paragraph, and in eq.(3), it is 'right'-'left'. I recommend that
Stokes definitions should conform to the IAU standard of 'right'-'left' in
all cases. The IAU definition also appears to agree with the definition
of Stokes V as -2Im{E_x E_y^*} in the first paragraph of 2.1."

Response: Changed Section 2.1 to conform to the IAU standard (right - left)

Additional Calibration Information
----------------------------------
"It is surprising that, for linear feed instruments, no mention is made of
the correction for the parallactic angle. Obviously, this does not matter for
true circular feeds, but it is not clear to me whether the 1/4 and 1/2-wave
plate equipment used in the SMA linear feeds is insensitive to the parallactic
angle."

Respone: The SMA observes point sources over a large range of parallactic angles to correct for it and to obtain the polarization leakages, however Stokes I and V are independent of the leakages to first-order. Added a paragraph at the end of section 2.1 to explain this. As an aside the SMA only uses QWPs and has no half-wave plates.

"Secondly, the intensity function in eq.(2) is the 'dirty' map, that is it
is the true source intensity convolved with the instrumental beam. In a
polarization observation there are slightly different (in general) beams
for each hand of circular polarization, or each Stokes parameter. In AIPS,
they have the file extensions, LBEAM, RBEAM, QBEAM, VBEAM etc. Were the
Stokes-I and Stokes-V maps deconvolved with a model based on their own beam, or just Stokes-I? Which algorithm was used for cleaning by Miriad: Clean or maximum entropy?"

Response: Added a clarification after eq. 2 to highlight that I(l,m) is convolved with the instrumenal beam. In regards to the deconvolution Miriad produces only a single beam for all polarizations. I checked that the instrumental beams for the LL and RR polarizations were not very different from each other by 'forcing' Miriad to invert each set of data seperately. The beams had very slight differences in their RMS but the shape of both beams were essentially identical. The penultimate paragraph before section 4 now explains this.

Observations
-------------
"1st para., l3: SMA data is described as having been measured using
circular feeds. However, in the previous section, the SMA has been described
as an instrument with linear feeds. It would be better to say that the
data was obtained with the linear to circular wave-plate equipment
installed."

Response: replaced the offending line at the beginning of Section 4 concerning the SMA feeds with your suggestion.

"Caption to Fig. 2: In the spectra, the Stokes-V lines are purple, not blue.
[Blue is correct for the maps]."

Response: Purple lines are now blue, thank you. I have mild color blindess. :)

Section 5.2
-----------
"As for the GK mechanism, I feel that this Section is missing a good basic
physical description of ARS. The reader of a more mathematical bent should
not be denied equations 5-10, but these formulae are just results that, in
my opinion, convey almost nothing about the process itself. Of course, the
reader may just wish to launch into the 2013 paper, but I think a short
physical description would be very helpful. My attempt follows:

ARS is a matter-radiation interaction mechanism mediated by the
second-order diagonal elements of the molecular density matrix (rather
than the much weaker first-order off-diagonal elements). In the presence
of a magnetic field, a small phase-change may be propagated at each
scattering between the n-photon states of incident radiation that are
linearly polarized parallel to, and perpendicular to, the magnetic field.
This phase change leads to the appearance of circular polarization in
the scattered radiation."

Response: Added the following paragraph to 5.2 to explain the physical basis for ARS:
ARS is a second-order interaction between
radiation and matter in the presence of a magnetic field.
Incident radiation with photon states that are polarized
k and ⊥ to the magnetic field can scatter off a molecule
and incur a small phase shift between the photon
states. The phase shift incurred after propagating and
scattering off many molecules results in the appearance
of CP in the scattered radiation.

In addition to the above changes an acknowledgements section has been added, as well as urls to to the scripts used for the reduction and squint correction.
