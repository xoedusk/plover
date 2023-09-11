# Plover Greek Dictionary
These JSON dictionaries for [Plover](https://www.openstenoproject.org/plover/) help you stroke Greek letters that are commonly used in mathematics.

Regarding spaces, the Greek letters sent by Plover will behave just like usual fingerspelling with Latin letters. Output is in Unicode.

There are separate **single-stroke** and **two-stroke** dictionaries; you may use one or both depending on your mood.
Download the JSON dictionaries and add them to your list of Plover dictionaries.
 * [Greek-Single-Stroke.json](./Greek-Single-Stroke.json)
 * [Greek-Two-Stroke.json](./Greek-Two-Stroke.json)

> [!NOTE]
> Only Greek letters typically used in mathematics are supported; unsupported are letters that look similar to the corresponding Latin letters, e.g., capital Latin A (A) and capital Greek Alpha (Α).

## Single stroke dictionary: Brief overview 
Most Greek letters have a one-to-one correspondance to Latin letters. For these, simply include the additional `#` key in the corresponding Latin finger-spelling stroke.
  * `#TK*` → δ (delta)
  * `#TK*P` → Δ (Delta)
  * Etc.

Letters that don't have one-to-one correspondants can usually be guessed. 
 * `#TH*P` → Θ (Theta)
 * `#SP*` → ψ   (psi)
 * `#AOE*` → η (eta)

> [!WARNING] 
> The stroke `#TH*P` for capital Θ may conflict with the Plover default `#24*7` for '24/7'. Two possible fixes you can enact: define a new stroke for '24/7', or change the stroke for Θ from `#TH*P` to `#H*P`.

## Two-stroke dictionary: Brief overview
Most Greek letters have a one-to-one correspondance to Latin letters. For these, stroke the prefix `#TKPWR` (sounds like `#GR`) before the corresponding Latin finger-spelling stroke.

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
