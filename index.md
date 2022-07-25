
In this appendix, we introduce chord proximity, regional proximity, and
chord/regional proximity based on the Tonal Pitch Space (TPS)[@tps]. TPS
is a complementary theory to A Generative Theory of Tonal Music (GTTM)
[@gttm], which is a cognitive tonal music theory that focuses on
structure. TPS considers the mathematical structure of music, such as
the circle of fifths and chord compositions.

# Chord Proximity

## Pitch Class

A pitch class is a pitch-value pair assigned from 0 to 11 according to
the pitch name
(Tab. [\[table:pitch_classes\]](#table:pitch_classes){reference-type="ref"
reference="table:pitch_classes"}, hereafter pc as its abbreviation). It
is because TPS calculation does not depend on the octave of the pitch.
In a pc, for example, C3 and C4 belong to the same class C and have 0 as
a value. And, the same pc applies to homophonic names, so
C$\sharp$`<!-- -->`{=html}3 and D$\flat$`<!-- -->`{=html}4 belong to the
same class, C$\sharp$/D$\flat$, and have 1 as a value.

## Basic Space

The basic space is a two-dimensional space with the pc and the influence
as four levels and indicates how influential a note is in a chord.
Tab. [3](#table:level_of_bs){reference-type="ref"
reference="table:level_of_bs"} shows the meaning of influence levels and
Fig. [\[figure:basic_space_C\]](#figure:basic_space_C){reference-type="ref"
reference="figure:basic_space_C"} shows the basic space of
$\rm{I}/\mathbf{C}$. The closer a note is to Level a, the more
influential it is in the chord (e.g., C(0) is the most influential note
in $\rm{I}/\mathbf{C}$).

## Chord Proximity within A Region

Chord proximity is calculated based on two factors: the diatonic circle
of fifths
(Fig. [\[figure:circle_of_fifths\]](#figure:circle_of_fifths){reference-type="ref"
reference="figure:circle_of_fifths"}) and the common notes. The diatonic
circle of fifths is the diatonic scale arranged in a circle by the
*chord-circle rule* on the basic space, with Roman numerals representing
degrees and arithmetic numbers representing the pc values of the root
note of the chord. The *chord-circle rule* can be stated as \"move the
pcs at level a-c four diatonic steps to the right or left.\" A diatonic
step means the movement of a pc on level d. As
Fig. [\[figure:circle_of_fifths\]](#figure:circle_of_fifths){reference-type="ref"
reference="figure:circle_of_fifths"}, applying the *chord-circle rule*
once to the right on $\rm{I}/\mathbf{C}$
(Fig. [\[figure:basic_space_C\]](#figure:basic_space_C){reference-type="ref"
reference="figure:basic_space_C"}) produces
$\rm{V}/\mathbf{C}$(Fig. [\[figure:basic_space_G\]](#figure:basic_space_G){reference-type="ref"
reference="figure:basic_space_G"}) and to the left produces
$\rm{IV}/\mathbf{C}$. Also note that the pc values overlap, so the right
of 11 is 0, and the left of 0 is 11.

And the common note, another factor of the chord proximity, is the
number of *distinctive* pcs in basic spaces between two chords. For
instance, in
Fig. [\[figure:bs_comparison\]](#figure:bs_comparison){reference-type="ref"
reference="figure:bs_comparison"}, underscored numbers mean distinctive
pcs between $\rm{I}/\mathbf{C}$ and $\rm{V}/\mathbf{C}$. This figure is
like $\rm{V}/\mathbf{C}$ overlain on $\rm{I}/\mathbf{C}$, so the level
of pc2 in $\rm{I}/\mathbf{C}$ is 1 and one in $\rm{V}/\mathbf{C}$ is 3,
thus the distinctive pc2 is $3-1=2$. From now, we formulate the chord
proximity $c$ between a chord $x$ and a chord $y$ as

$$c(x\rightarrow y) = j+k$$ where $j$ is the shortest number of steps in
the circle of fifths and $k$ is the number of distinctive pcs (e.g.,
Fig. [\[figure:bs_comparison\]](#figure:bs_comparison){reference-type="ref"
reference="figure:bs_comparison"}).

## Chord Proximity across Regions

To get chord proximity for chords in different regions, we need an
additional measurement, a regional shift. With the same chord proximity
and the diatonic circle of fifths, a regional shift is calculated on the
chromatic circle of fifths by the *regional-circle rule* on the basic
space
(Fig. [\[figure:chromatic_cof\]](#figure:chromatic_cof){reference-type="ref"
reference="figure:chromatic_cof"}) and the *regional-circle rule* can be
stated as \"move the pcs at level d seven chromatic steps to the right
or left.\" A chromatic step means the movement of a pc on level e. And
of course, a regional shift between the same region will be 0. Now we
can enlarge the formula $c$ with a regional shift as
$$c(x\rightarrow y) = i+j+k$$ where $i$ is the steps on the region
circle, $j$ and $k$ are the same as before.
Fig. [11](#figure:bs_comparison_diff){reference-type="ref"
reference="figure:bs_comparison_diff"} shows the derivation of chord
proximity across regions, **C** to **G**. Here, although
$\rm{V}/\mathbf{C}$ and $\rm{I}/\mathbf{G}$ both refer to G-major,
$c(\rm{I}/\mathbf{C}\rightarrow\rm{V}/\mathbf{C})=5$ and
$c(\rm{I}/\mathbf{C}\rightarrow\rm{I}/\mathbf{G})=7$ mean that the chord
proximity will be different depending on their regions. In general, the
chord proximity is smaller when interpreted without musical modulation
[@tpsapp].

## Regional Space

Regional proximity is the proximity of a region in terms of the
*distance of its local tonic*. This step is justified because one
strongly hears chords in relation to their local tonic as well as to one
overall governing tonic [@tps]. In the calculation of regional
proximity, we use the regional space, a torus of regions. First we place
the tonic $\rm{I}/\mathbf{I}$ and the local tonics
$\rm{I}/\mathbf{V}, \rm{I}/\mathbf{IV}, \rm{i}/\mathbf{vi}, \rm{i}/\mathbf{i}$
that have the smallest chord proximity $c=7$ from the tonic on a torus.
The region in the circle of fifths
($\rm{I}/\mathbf{V}, \rm{I}/\mathbf{IV}$) placed on the vertical axis,
and relative and parallel minor
($\rm{i}/\mathbf{vi}, \rm{i}/\mathbf{i}$) placed on the horizontal axis.
Then do this procedure recursively to form a torus, showed in
Fig. [\[figure:regional_space\]](#figure:regional_space){reference-type="ref"
reference="figure:regional_space"} and
Fig. [15](#figure:regional_space_relative){reference-type="ref"
reference="figure:regional_space_relative"}.

::: {.center}
::: {#table:level_of_bs}
    pc             C            C$\sharp$/D$\flat$           D            D$\sharp$/E$\flat$           E            F
  ------- -------------------- -------------------- -------------------- -------------------- -------------------- ----
   value           0                    1                    2                    3                    4            5
    pc     F$\sharp$/G$\flat$           G            G$\sharp$/A$\flat$           A            A$\sharp$/B$\flat$   B
   value           6                    7                    8                    9                    10           11

  : Level and its description in the basic space.
:::
:::

::: {.center}
::: {#table:level_of_bs}
    Level               Description
  --------- ------------------------------------
   Level a          The root of a chord.
   Level b     The root of fifth of a chord.
   Level c       The components of a chord.
   Level d   The diatonic scale of chord's key.
   Level e           All pitch classes.

  : Level and its description in the basic space.
:::
:::

::: {.center}
![Derivation of chord proximity
$c(\rm{I}/\mathbf{C}\rightarrow\rm{I}/\mathbf{G})$.](bs_c.png){#figure:bs_comparison_diff
width="70mm"}
:::

[\[figure:basic_space_C\]]{#figure:basic_space_C
label="figure:basic_space_C"}

::: {.center}
![Derivation of chord proximity
$c(\rm{I}/\mathbf{C}\rightarrow\rm{I}/\mathbf{G})$.](bs_g.png){#figure:bs_comparison_diff
width="70mm"}
:::

[\[figure:basic_space_G\]]{#figure:basic_space_G
label="figure:basic_space_G"}

::: {.center}
![Derivation of chord proximity
$c(\rm{I}/\mathbf{C}\rightarrow\rm{I}/\mathbf{G})$.](bs_c_g_comparison.png "fig:"){#figure:bs_comparison_diff
width="70mm"} $c(\rm{I}/\mathbf{C}\rightarrow\rm{V}/\mathbf{C})=1+4=5$
:::

[\[figure:bs_comparison\]]{#figure:bs_comparison
label="figure:bs_comparison"}

::: {.center}
![Derivation of chord proximity
$c(\rm{I}/\mathbf{C}\rightarrow\rm{I}/\mathbf{G})$.](bs_c_g_comparison_region.png "fig:"){#figure:bs_comparison_diff
width="70mm"} $c(\rm{I}/\mathbf{C}\rightarrow\rm{I}/\mathbf{G})=1+1+5=6$
:::

[\[figure:bs_comparison_diff\]]{#figure:bs_comparison_diff
label="figure:bs_comparison_diff"}

::: {.center}
![The regional space (subregions oriented to
C-major).](circle_of_fifth.png){#figure:regional_space_relative
height="30mm"}
:::

[\[figure:circle_of_fifths\]]{#figure:circle_of_fifths
label="figure:circle_of_fifths"}

::: {.center}
![The regional space (subregions oriented to
C-major).](chromatic_circle_of_fifth.png){#figure:regional_space_relative
height="30mm"}
:::

[\[figure:chromatic_cof\]]{#figure:chromatic_cof
label="figure:chromatic_cof"}

::: {.center}
![The regional space (subregions oriented to
C-major).](regional_space.png){#figure:regional_space_relative
width="50mm"}
:::

[\[figure:regional_space\]]{#figure:regional_space
label="figure:regional_space"}

::: {.center}
![The regional space (subregions oriented to
C-major).](regional_space_relative.png){#figure:regional_space_relative
width="50mm"}
:::

[\[figure:regional_space_relative\]]{#figure:regional_space_relative
label="figure:regional_space_relative"}

::: {.center}
![Pivot regions with their proximity value from $\mathbf{I}$ and
$\mathbf{i}$,
respectively.](pivot_major.png "fig:"){#figure:pivot_regions
height="15mm"} ![Pivot regions with their proximity value from
$\mathbf{I}$ and $\mathbf{i}$,
respectively.](pivot_minor.png "fig:"){#figure:pivot_regions
height="15mm"}
:::

[\[figure:pivot_regions\]]{#figure:pivot_regions
label="figure:pivot_regions"}

::: {.figure*}
::: {.center}
![image](pivoting.png){width="110mm"}
:::

Blue rectangles: pivot regions, red circles: the starting point or
pivots. [\[figure:pivoting\]]{#figure:pivoting label="figure:pivoting"}
:::

## Pivots and Regional Proximity

The regional space suggests a further reason why the above formula for
$c$ works for nearby but not distant regions. Nearby regions share
chords that can function as *pivot chords* from one region to another.
But as chromatic changes infiltrate more distant regions, direct pivot
chords disappear, requiring intermediate pivots that have not yet been
taken into account [@tps]. From these point of view, the regional
proximity from the starting region $\mathbf{S}$ to the destination
region $\mathbf{D}$,
$\delta\left(\mathbf{S}\rightarrow \mathbf{D}\right)$ can be stated as

$$\delta\left(\mathbf{S}\rightarrow \mathbf{D}\right)\vcentcolon=
    c_1+c_2+\ldots+c_n$$ where $c_1$ is the intermediate chord proximity
from the starting region to the tonic of the first pivot region (the
first tonic pivots), $c_2$ is the intermediate chord proximity from the
tonic of the first pivot region to the second one, and so on. In this
calculation, the regional proximity needs the six-regional units called
*pivot regions* (Fig. [17](#figure:pivot_regions){reference-type="ref"
reference="figure:pivot_regions"}) and tonic of pivot regions called
*tonic pivots*. For example,
$\delta\left(\mathbf{F}\rightarrow \mathbf{b}\right)$ can be calculated
with pivots
$\mathbf{F}\rightarrow \mathbf{C}\rightarrow \mathbf{e}\rightarrow \mathbf{b}$
as in Fig. [\[figure:pivoting\]](#figure:pivoting){reference-type="ref"
reference="figure:pivoting"}. And as you can see in this example, there
are multiple routing for $\mathbf{S}\rightarrow \mathbf{D}$ since pivot
regions have at least five candidates (e.g., a routing for
$\mathbf{F}\rightarrow \mathbf{b}$ can be interpreted as
$\mathbf{F}\rightarrow \mathbf{C}\rightarrow \mathbf{e}\rightarrow \mathbf{b}$,
$\mathbf{F}\rightarrow \mathbf{C}\rightarrow \mathbf{G}\rightarrow \mathbf{b}$,
etc.). So we'll use the minimum regional proximity of all regions in
this paper. These values can be computed with some algorithms such as
Dijkstra's algorithm and Bellman-Ford algorithm since this routing can
be taken as the shortest path from a single source vertex to all of the
other vertices in a weighted graph.

## Chord/Regional Proximity

From these definitions, the chord/regional proximity, the chord
proximity enlarged with the regional proximity, $\delta$ can be
determined as:

$$\begin{split}
        & \delta\left(\rm{D_1}/\mathbf{R_1}\rightarrow \rm{D_2}/\mathbf{R_2}\right) \vcentcolon=\\
        &d\left(\rm{D_1}/\mathbf{R_1}\rightarrow \mathbf{P_1}\right)
        +\delta\left(\mathbf{P_1}\rightarrow \mathbf{P_n}\right)
        +d\left(\mathbf{P_n}\rightarrow \rm{D_2}/\mathbf{R_2}\right)\label{ckdistance}
    \end{split}$$ where $\rm{D_{\mathit{i}}}/\mathbf{R_{\mathit{i}}}$ is
the chord of the degree $\rm{D_{\mathit{i}}}$ on region
$\rm{\mathbf{R_{\mathit{i}}}}$ and $\mathbf{P_{\mathit{k}}}$ is a tonic
pivot.

::: {.thebibliography}
F. Lerdahl, *Tonal Pitch Space*. Oxford University Press, 2001.

F. Lerdahl, R. Jackendoff. A Generative Theory of Tonal Music,
Cambridge, Mass: MIT Press, 1983.
