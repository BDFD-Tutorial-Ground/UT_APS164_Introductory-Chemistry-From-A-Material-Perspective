# Crystal Structure Comparison: FCC, BCC, HCP, Simple Cubic, and Rock Salt

## Quick Comparison Table

| Structure | Full name | Conventional unit cell contents | Coordination number | Atomic packing factor | Close-packed plane | Close-packed direction | Stacking / key geometry | Common examples |
|---|---|---:|---:|---:|---|---|---|---|
| SC | Simple cubic | 1 atom/cell | 6 | 0.52 | None truly close-packed; densest plane is {100} | <100> directions are nearest-neighbor directions | Simple cubic layers stacked directly above each other | Polonium, idealized model |
| BCC | Body-centered cubic | 2 atoms/cell | 8 nearest neighbors | 0.68 | None truly close-packed; densest planes are {110} | <111> are closest-packed directions | Atoms touch along body diagonal | alpha-Fe, Cr, W, Mo |
| FCC | Face-centered cubic | 4 atoms/cell | 12 | 0.74 | {111} | <110> | ABCABC close-packed stacking | Al, Cu, Ni, Ag, Au, Pb |
| HCP | Hexagonal close-packed | 6 atoms/conventional cell; 2 atoms/primitive cell | 12 | 0.74 ideal | {0001} basal plane | <11-20> | ABAB close-packed stacking | Mg, Ti, Zn, Co |
| Rock Salt | NaCl-type ionic structure | 4 formula units/cell; 4 cations + 4 anions | 6 for each ion, opposite charge only | Depends on ion sizes; not a single metallic APF | Not usually described by metallic close-packed planes; each ion sublattice is FCC with {111} close-packed layers | Nearest unlike-ion directions are <100> | Two interpenetrating FCC sublattices; cations fill all octahedral sites of anion FCC lattice | NaCl, MgO, CaO, FeO |

## Main Takeaways

FCC and HCP are the two classic close-packed metallic structures. They both have:

- coordination number 12
- maximum equal-sphere packing efficiency of 0.74
- triangular/hexagonal close-packed atomic layers

The difference is the stacking sequence:

```text
FCC: ABCABC...
HCP: ABAB...
```

BCC is dense, but it is not close-packed. It has close-packed directions, especially <111>, but no plane has the true triangular close-packed arrangement found in FCC {111} or HCP {0001}.

Simple cubic is much more open. Its atoms touch along cube edges, but it does not contain a true close-packed plane.

Rock salt is an ionic crystal, so it should not be treated exactly like a one-atom metallic lattice. It is best understood as two interpenetrating FCC lattices: one for anions and one for cations.

## FCC: Face-Centered Cubic

In FCC, atoms are located at the 8 corners and the 6 face centers of the cubic unit cell.

Effective atoms per conventional unit cell:

```text
8 corners x 1/8 + 6 face centers x 1/2 = 4 atoms
```

Key facts:

- Coordination number: 12
- Atomic packing factor: 0.74
- Close-packed planes: {111}
- Close-packed directions: <110>
- Stacking sequence: ABCABC...
- Atoms touch along the face diagonal.

Radius-lattice parameter relation:

```text
4r = sqrt(2)a
a = 2sqrt(2)r
```

The FCC {111} plane has a triangular arrangement of atoms. This is why it is a close-packed plane.

Common FCC metals:

- Al
- Cu
- Ni
- Ag
- Au
- Pb

## HCP: Hexagonal Close-Packed

HCP is also a close-packed structure, but it uses a hexagonal unit cell instead of a cubic one.

Key facts:

- Coordination number: 12
- Atomic packing factor: 0.74 for ideal HCP
- Close-packed plane: {0001}, also called the basal plane
- Close-packed directions: <11-20>
- Stacking sequence: ABAB...

Ideal HCP geometry:

```text
a = 2r
c/a = 1.633
```

HCP and FCC have the same packing efficiency and coordination number. The major difference is the layer stacking:

```text
HCP repeats every 2 layers: ABAB...
FCC repeats every 3 layers: ABCABC...
```

Common HCP metals:

- Mg
- Ti
- Zn
- Co

## BCC: Body-Centered Cubic

In BCC, atoms are located at the 8 corners and 1 body center of the cubic unit cell.

Effective atoms per conventional unit cell:

```text
8 corners x 1/8 + 1 body center = 2 atoms
```

Key facts:

- Coordination number: 8 nearest neighbors
- Atomic packing factor: 0.68
- No true close-packed plane
- Densest planes: {110}
- Closest-packed directions: <111>
- Atoms touch along the body diagonal.

Radius-lattice parameter relation:

```text
4r = sqrt(3)a
a = 4r / sqrt(3)
```

Important exam note:

Although BCC often slips in <111> directions and has dense {110} planes, the {110} planes are not close-packed in the same strict sense as FCC {111} or HCP {0001}. A true close-packed plane must have atoms arranged in a triangular/hexagonal net.

Common BCC metals:

- alpha-Fe
- Cr
- W
- Mo

## Simple Cubic

In simple cubic, atoms are located only at the 8 corners of the cubic unit cell.

Effective atoms per conventional unit cell:

```text
8 corners x 1/8 = 1 atom
```

Key facts:

- Coordination number: 6
- Atomic packing factor: 0.52
- No true close-packed plane
- Densest plane: {100}
- Nearest-neighbor directions: <100>
- Atoms touch along cube edges.

Radius-lattice parameter relation:

```text
a = 2r
```

Simple cubic is relatively open compared with FCC, HCP, and BCC. It is uncommon among real elemental solids.

## Rock Salt Structure

Rock salt, also called the NaCl structure, is an ionic crystal structure. It is not a simple metallic packing of identical atoms.

The easiest way to describe it:

```text
One ion type forms an FCC lattice.
The other ion type occupies all octahedral sites.
```

For NaCl specifically:

- Cl- ions can be viewed as forming an FCC sublattice.
- Na+ ions occupy all octahedral holes.
- Equivalently, Na+ and Cl- form two interpenetrating FCC sublattices.

Key facts:

- Coordination number: 6 for Na+ and 6 for Cl-
- Geometry around each ion: octahedral
- Formula units per conventional unit cell: 4 NaCl
- Ion positions are commonly described as FCC anions plus cations in octahedral sites.
- Nearest unlike-ion directions: <100>

Nearest-neighbor relation:

```text
r_cation + r_anion = a/2
a = 2(r_cation + r_anion)
```

Radius ratio condition for stable octahedral coordination:

```text
0.414 <= r_cation / r_anion <= 0.732
```

Close-packed plane note:

Rock salt is often related to FCC packing because the larger ions, commonly the anions, form an FCC array. Therefore the anion sublattice has FCC-style close-packed {111} planes. However, for the full NaCl ionic structure, it is usually better to describe the structure by coordination number and octahedral coordination rather than saying it has a metallic close-packed plane.

## Exam-Friendly Distinctions

Do not confuse these ideas:

| Concept | Meaning | Example |
|---|---|---|
| Close-packed plane | A plane where atoms form a triangular/hexagonal touching pattern | FCC {111}, HCP {0001} |
| Densest plane | The plane with highest planar density in that structure | BCC {110}, SC {100} |
| Close-packed direction | A direction along which atoms touch most closely | FCC <110>, BCC <111>, SC <100> |
| Coordination number | Number of nearest neighbors around one atom or ion | FCC = 12, BCC = 8, NaCl = 6 |

This is why BCC can have a closest-packed direction, <111>, without having a true close-packed plane.

## Short Memory Version

```text
FCC:
  CN = 12
  APF = 0.74
  close-packed plane = {111}
  close-packed direction = <110>
  stacking = ABCABC

HCP:
  CN = 12
  APF = 0.74
  close-packed plane = {0001}
  close-packed direction = <11-20>
  stacking = ABAB

BCC:
  CN = 8
  APF = 0.68
  no true close-packed plane
  densest plane = {110}
  closest-packed direction = <111>

Simple Cubic:
  CN = 6
  APF = 0.52
  no true close-packed plane
  densest plane = {100}
  nearest-neighbor direction = <100>

Rock Salt:
  CN = 6 for each ion
  4 formula units per unit cell
  two interpenetrating FCC sublattices
  cations fill octahedral sites
  best described as octahedral ionic coordination, not simple metallic close packing
```

## Common Mistakes

1. Saying BCC has close-packed planes.

   More accurate: BCC has no true close-packed plane. Its densest planes are {110}, and its closest-packed directions are <111>.

2. Saying FCC and HCP are completely different in packing efficiency.

   More accurate: FCC and HCP both have APF = 0.74 and coordination number 12. Their main difference is stacking sequence.

3. Treating rock salt as if it were a one-atom FCC metal.

   More accurate: Rock salt is an ionic structure with two ion types. It has octahedral coordination, 6:6 coordination, and 4 formula units per cubic unit cell.

4. Confusing coordination number with number of atoms per unit cell.

   Example: FCC has 4 atoms per conventional unit cell, but each atom has 12 nearest neighbors.

