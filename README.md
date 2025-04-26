# Secondary Mushroom

## Project Overview
The **EDA Secondary Mushroom** project is a project to help understand data structure, identify patterns, relationships between variables, and potential anomalies from various features in a secondary mushroom dataset, before further modeling is performed. 

Data visualization helps simplify the interpretation of numerical and categorical features, and can reveal hidden insights that are not immediately apparent from the raw data table.

---

## Source
**Dataset Link:** [Secondary Mushroom Dataset - UCI Repository](https://archive.ics.uci.edu/dataset/848/secondary+mushroom+dataset)

---

## Data Description
The mushroom dataset provides a comprehensive collection of features that can be used to classify mushrooms into edible or poisonous categories. It includes **21 attributes**, each detailing a specific characteristic of the mushrooms.

- **Target class**:  
  - `e` = edible  
  - `p` = poisonous (may include mushrooms of unknown edibility)

- **Features**:  
  - 1 binary class  
  - 20 features: nominal (n) or metrical (m)

### Attribute Descriptions:

1. **cap-diameter** (m): float number in cm  
2. **cap-shape** (n): `b`=bell, `c`=conical, `x`=convex, `f`=flat, `s`=sunken, `p`=spherical, `o`=others  
3. **cap-surface** (n): `i`=fibrous, `g`=grooves, `y`=scaly, `s`=smooth, `h`=shiny, `l`=leathery, `k`=silky, `t`=sticky, `w`=wrinkled, `e`=fleshy  
4. **cap-color** (n): `n`=brown, `b`=buff, `g`=gray, `r`=green, `p`=pink, `u`=purple, `e`=red, `w`=white, `y`=yellow, `l`=blue, `o`=orange, `k`=black  
5. **does-bruise-bleed** (n): `t`=bruises or bleeding, `f`=no  
6. **gill-attachment** (n): `a`=adnate, `x`=adnexed, `d`=decurrent, `e`=free, `s`=sinuate, `p`=pores, `f`=none, `?`=unknown  
7. **gill-spacing** (n): `c`=close, `d`=distant, `f`=none  
8. **gill-color** (n): see cap-color + `f`=none  
9. **stem-height** (m): float number in cm  
10. **stem-width** (m): float number in mm  
11. **stem-root** (n): `b`=bulbous, `s`=swollen, `c`=club, `u`=cup, `e`=equal, `z`=rhizomorphs, `r`=rooted  
12. **stem-surface** (n): see cap-surface + `f`=none  
13. **stem-color** (n): see cap-color + `f`=none  
14. **veil-type** (n): `p`=partial, `u`=universal  
15. **veil-color** (n): see cap-color + `f`=none  
16. **has-ring** (n): `t`=ring, `f`=none  
17. **ring-type** (n): `c`=cobwebby, `e`=evanescent, `r`=flaring, `g`=grooved, `l`=large, `p`=pendant, `s`=sheathing, `z`=zone, `y`=scaly, `m`=movable, `f`=none, `?`=unknown  
18. **spore-print-color** (n): see cap-color  
19. **habitat** (n): `g`=grasses, `l`=leaves, `m`=meadows, `p`=paths, `h`=heaths, `u`=urban, `w`=waste, `d`=woods  
20. **season** (n): `s`=spring, `u`=summer, `a`=autumn, `w`=winter  
