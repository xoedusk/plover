# Plover Greek Dictionary
This Plover dictionary helps you write Greek letters that are commonly used in mathematics. Not all letters are supported since many of them look similar to Latin letters (e.g., capital A and capital Alpha). All Greek letter behave just like usual fingerspelling via the glue `{&}` command.

There are separate **single-stroke** and **two-stroke** dictionaries; you may use one or both depending on your mood.
Download them here and add the files to your list of Plover dictionaries.
 * [Greek-Single-Stroke.json](./Greek-Single-Stroke.json)
 * [Greek-Two-Stroke.json](./Greek-Two-Stroke.json)

## Single stroke dictionary: Brief overview 
Include the additional `#` key in the usual finger-spelling stroke. This works for Greek letters that have a one-to-one Latin correspondant:
  * `#TK*` → δ (delta)
  * `#TK*P` → Δ (Delta)
  * Etc.

Exceptions that don't have one-to-one correspondants can usually be guessed:
 * `#TH*P` → Θ (Theta)
 * `#SP*` → ψ   (psi)
 * `#AOE*` → η (eta)

> [!WARNING] 
> The stroke `#TH*P` for capital Θ may conflict with the Plover default `#24*7` for '24/7'. You may define a new stroke for '24/7' if desired, or perhaps change `#TH*P` to `#H*P` for Θ.

## Two-stroke dictionary: Brief overview
Stroke the prefix `#TKPWR` (think `#GR`) before the usual finger-spelling stroke. This works for Greek letters that have a one-to-one Latin correspondant:

   * `#TKPWR/O*` → ω 
   * `#TKPWR/O*P` → Ω
   * Etc.

Exceptions that don't have one-to-one correspondants can usually be guessed:
 * `#TKPWR/TH*P` → Θ (Theta)
 * `#TKPWR/SP*` → ψ   (psi)
 * `#TKPWR/AOE*` → η (eta)

# Complete list of strokes
## Single-stroke dictionary
Include the `#` key in your usual fingerspelling stroke.
 | Stroke | Letter | Glyph | Note |
 | ------ | ------ | ----- | ----- |
 | `#A*`  | alpha  | α | |
 | `#PW*` | beta |β | |
 | `#TKPW*` or `#TKPW*P` | gamma |γ / Γ  | |
 | `#TK*` | delta |δ / Δ | |
 | `#E*` | epsilon |ε | |
 | `#STKPW*` | zeta |ζ   | |
 | `#AOE*` | eta| η | |
 | `#TH*` or `#TH*P`  | theta |θ / Θ | Conflicts with `#24*7` for 24/7. See note in overview above.
 | `#K*` | kappa |κ |  |
 | `#HR*` or `#HR*P` | lambda |λ / Λ | |
 | `#PH*` | mu |μ | |
 | `#TPH*` | nu |ν | |
 | `#KP*` or `#KP*P` | xi |ξ / Ξ | |
 | `#P*` or `#P*P` | pi |π / Π | |
 | `#R*` | rho |ρ | |
 | `#S*` or `#S*P`  |sigma | σ / Σ  | |
 | `#T*` |tau |τ | |
 | `#TP*` or `#TP*P` |phi | φ / Φ | |
 | `#KH*` | chi |χ | |
 | `#SP*` or `#SP*P` | psi |ψ / Ψ | |
 | `#O*`or `#O*P`| omega | ω / Ω ||
## Two-stroke dictionary
Stroke the prefix `#TKPWR` before the usual fingerspelling stroke.
 | Stroke | Letter | Glyph | Note |
 | ------ | ------ | ----- | ----- |
 | `#TKPWR/A*`  | alpha  | α | |
 | `#TKPWR/PW*` | beta |β | |
 | `#TKPWR/TKPW*` or `#TKPWR/TKPW*P` | gamma |γ / Γ  | |
 | `#TKPWR/TK*` | delta |δ / Δ | |
 | `#TKPWR/E*` | epsilon |ε | |
 | `#TKPWR/STKPW*` | zeta |ζ   | |
 | `#TKPWR/AOE*` | eta| η | |
 | `#TKPWR/TH*` or `#TKPWR/TH*P`  | theta |θ / Θ | |
 | `#TKPWR/K*` | kappa |κ |  |
 | `#TKPWR/HR*` or `#TKPWR/HR*P` | lambda |λ / Λ | |
 | `#TKPWR/PH*` | mu |μ | |
 | `#TKPWR/TPH*` | nu |ν | |
 | `#TKPWR/KP*` or `#TKPWR/KP*P` | xi |ξ / Ξ | |
 | `#TKPWR/P*` or `#TKPWR/P*P` | pi |π / Π | |
 | `#TKPWR/R*` | rho |ρ | |
 | `#TKPWR/S*` or `#TKPWR/S*P` |sigma | σ / Σ  | |
 | `#TKPWR/T*` |tau |τ | |
 | `#TKPWR/TP*` or `#TKPWR/TP*P` |phi | φ / Φ | |
 | `#TKPWR/KH*` | chi |χ | |
 | `#TKPWR/SP*` or `#TKPWR/SP*P` | psi |ψ / Ψ | |
 | `#TKPWR/O*`or `#TKPWR/O*P`| omega | ω / Ω ||
