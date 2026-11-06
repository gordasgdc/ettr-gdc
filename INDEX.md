# ETTR GDC - profile index

29 profiles, 28 unique curves, 203 LUTs in profile folders (196 unique tables) + 21 short-name copies for Sony viewfinders = 224 `.cube` files.

| Brand | Profile (folder) | Gamut | Curve | Max interp. error (10-bit codes) | Max error, stops (out >= -6 EV grey / >= -8 EV grey) | Colour oracle |
|---|---|---|---|---|---|---|
| Sony | `S-Log2_S-Gamut` | S-Gamut | slog2 | 0.194 | 0.0288 / 0.0529 | OK |
| Sony | `S-Log3_S-Gamut3.Cine` | S-Gamut3.Cine | slog3 | 1.427 | 0.053 / 0.0531 | OK |
| Sony | `S-Log3_S-Gamut3` | S-Gamut3 | slog3 | 0.667 | 0.0167 / 0.0531 | OK |
| Canon | `Canon-Log_Cinema-Gamut` | Cinema Gamut | clog | 0.159 | 0.0377 / 0.0719 | OK |
| Canon | `Canon-Log2_Cinema-Gamut` | Cinema Gamut | clog2 | 0.298 | 0.0178 / 0.0645 | OK |
| Canon | `Canon-Log3_Cinema-Gamut` | Cinema Gamut | clog3 | 0.394 | 0.0265 / 0.0265 | OK |
| Panasonic | `V-Log_V-Gamut` | V-Gamut | vlog | 0.737 | 0.0258 / 0.0258 | OK |
| ARRI | `LogC3_AWG3_EI0160` | ARRI Wide Gamut 3 | logc3_ei160 | 0.605 | 0.0356 / 0.0357 | OK |
| ARRI | `LogC3_AWG3_EI0200` | ARRI Wide Gamut 3 | logc3_ei200 | 0.587 | 0.0344 / 0.0344 | OK |
| ARRI | `LogC3_AWG3_EI0250` | ARRI Wide Gamut 3 | logc3_ei250 | 0.549 | 0.0314 / 0.0314 | OK |
| ARRI | `LogC3_AWG3_EI0320` | ARRI Wide Gamut 3 | logc3_ei320 | 0.54 | 0.0264 / 0.0264 | OK |
| ARRI | `LogC3_AWG3_EI0400` | ARRI Wide Gamut 3 | logc3_ei400 | 0.644 | 0.0252 / 0.0252 | OK |
| ARRI | `LogC3_AWG3_EI0500` | ARRI Wide Gamut 3 | logc3_ei500 | 0.723 | 0.0251 / 0.0251 | OK |
| ARRI | `LogC3_AWG3_EI0640` | ARRI Wide Gamut 3 | logc3_ei640 | 0.729 | 0.025 / 0.025 | OK |
| ARRI | `LogC3_AWG3_EI0800` | ARRI Wide Gamut 3 | logc3_ei800 | 0.717 | 0.0248 / 0.0248 | OK |
| ARRI | `LogC3_AWG3_EI1000` | ARRI Wide Gamut 3 | logc3_ei1000 | 0.705 | 0.0246 / 0.0246 | OK |
| ARRI | `LogC3_AWG3_EI1280` | ARRI Wide Gamut 3 | logc3_ei1280 | 0.699 | 0.0243 / 0.0243 | OK |
| ARRI | `LogC3_AWG3_EI1600` | ARRI Wide Gamut 3 | logc3_ei1600 | 0.84 | 0.0232 / 0.0233 | OK |
| ARRI | `LogC4_AWG4` | ARRI Wide Gamut 4 | logc4 | 0.333 | 0.0548 / 0.1219 | OK |
| RED | `Log3G10_REDWideGamutRGB` | REDWideGamutRGB | log3g10 | 0.32 | 0.0284 / 0.0869 | OK |
| Blackmagic | `Film-Gen5_BMD-WG-Gen5` | Blackmagic Wide Gamut Gen5 | bmdgen5 | 0.789 | 0.0384 / 0.0384 | no oracle |
| Nikon | `N-Log_N-Gamut` | N-Gamut (Rec.2020 primaries) | nlog | 0.687 | 0.0316 / 0.129 | OK |
| Fujifilm | `F-Log_F-Gamut` | F-Gamut (Rec.2020 primaries) | flog | 0.209 | 0.0124 / 0.0363 | OK |
| Fujifilm | `F-Log2_F-Gamut` | F-Gamut (Rec.2020 primaries) | flog2 | 0.337 | 0.0175 / 0.0723 | OK |
| GoPro | `Protune-Flat_Protune-Native` | Protune Native | protune | 0.148 | 0.004 / 0.0121 | OK |
| Apple | `Apple-Log_Rec2020` | Rec.2020 | applelog | 8.769 | 0.0229 / 0.0229 | OK |
| FilmLight | `T-Log_E-Gamut` | E-Gamut | tlog | 0.338 | 0.0148 / 0.0397 | OK |
| DaVinci | `DaVinci-Intermediate_DWG` | DaVinci Wide Gamut | intermediate | 0.596 | 0.0184 / 0.0417 | no oracle |
| ACES | `ACEScct_AP1` | ACES AP1 | acescct | 1.229 | 0.0259 / 0.026 | OK |

## Profiles with numerically identical LUTs (same log curve; the gain is per channel, no gamut conversion)

- `slog3`: `Sony/S-Log3_S-Gamut3.Cine`, `Sony/S-Log3_S-Gamut3`
