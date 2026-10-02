# Launch calculation appendix

Reference integrator: [`../calc/lightsail.py`](../calc/lightsail.py). Tagged engineering claims: [`probes.md`](probes.md).

**CANON.** These numbers are an adopted fictional design family. They are not demonstrated hardware.

**CANON.** The external links below do not validate the fictional membrane, the 10 GW/m² loading, picotechnology, or destination capture.

- NASA sail deployment (class of photon sails, not this hop): https://www.nasa.gov/centers-and-facilities/marshall/nasa-solar-sail-technology-passes-crucial-deployment-test/
- Breakthrough Starshot (laser-sail concept class): https://breakthroughinitiatives.org/initiative/3
- Hoang et al. on interstellar gas and dust damage: https://arxiv.org/abs/1608.05284
- Einstein Online on time dilation and simultaneity: https://www.einstein-online.info/en/spotlight/time_dilation_road/

## Variables (SI)

| Symbol | Meaning | Reference value |
| --- | --- | --- |
| \(c\) | Speed of light | 299 792 458 m s⁻¹ |
| \(m\) | Rest mass of the launch stack (probe body + sail system) | 0.002 kg for the 1 g + 1 g row |
| \(P\) | Nominal beam power crossing a stationary plane over the sail's projected area, assuming containment | 1.00 × 10¹¹ W for the 1 g row |
| \(\beta\) | \(v/c\) in the launch frame | 0 → 0.2 |
| \(\gamma\) | \(1/\sqrt{1-\beta^2}\) | 1.02062 at 0.2c |
| \(F(\beta)\) | Radiation force on an ideal receding reflector | \((2P/c)\,(1-\beta)/(1+\beta)\) |
| \(g_0\) | Standard gravity | 9.80665 m s⁻² |
| AU | Astronomical unit | 149 597 870 700 m |

**CANON.** \(P\) is not automatically useful intercepted power under every optical convention. It is not transmitter output after losses, aperture spill, or pointing error.

## Equations

Ideal receding reflector in the launch frame:

\[
F(\beta)=\frac{2P}{c}\frac{1-\beta}{1+\beta}
\]

Relativistic momentum and position:

\[
\frac{d}{dt}(\gamma m v)=F(\beta),\qquad \frac{dx}{dt}=v
\]

Closed form for onboard proper time from \(\beta=0\) to \(\beta_f\):

\[
\tau=\frac{m c}{2P/c}\frac{\beta_f}{1-\beta_f}
\]

Launch-frame time and distance are integrated from

\[
\frac{dt}{d\beta}=\frac{m c}{2P/c}(1+\beta)^{-1/2}(1-\beta)^{-5/2},\qquad \frac{dx}{d\beta}=\beta c\frac{dt}{d\beta}
\]

Transmitter emission duration for a source at the launch origin:

\[
t_\mathrm{em}=t-x/c
\]

**INFERENCE.** Parent model: a source at the launch origin and light-speed delay along the boost trajectory. A photon that arrives at \((t,x)\) was emitted at \(t-x/c\).

## Verified boost to 0.2c

**INFERENCE.** Parent model: the force convention and integrals in this file, applied to the adopted sail family in [`probes.md`](probes.md) (equal \(P/m\), ideal near-perfect reflector, nominal initial intensity 10 GW/m²). Independent Simpson integration and the proper-time closed form agree with [`../calc/lightsail.py`](../calc/lightsail.py). Rounded work figures:

| Quantity | Do not confuse with | Result |
| --- | --- | --- |
| Launch-frame acceleration duration \(t\) | Proper time; transmitter-on time | 226 s |
| Onboard proper time \(\tau\) | Historical date; experienced mind-time | 225 s |
| Transmitter emission duration \(t_\mathrm{em}\) | \(t\) | 202 s |
| Acceleration distance | Coast distance | 7.31 million km ≈ 0.049 AU |
| Initial acceleration \(F(0)/m\) | Mean acceleration | ≈ 34 000 \(g_0\) |
| Kinetic energy \((\gamma-1)mc^2\) of the 2 g stack | Nominal beam energy | 3.71 × 10¹² J |
| Nominal beam energy \(P\,t_\mathrm{em}\) | Kinetic energy; transmitter wall-plug energy | 2.02 × 10¹³ J |
| Nominal \(P\,t\) | Energy that actually left the aperture | 2.26 × 10¹³ J |

**INFERENCE.** Parent model: the same adopted family. Lower intensity, different loading, or a shorter acceleration lane change every row. The table is one family, not a required unique sail.

**INFERENCE.** Diffraction check only, parent model: an idealised 1 μm source with a 5 km aperture. Airy first-dark-ring diameter \(2.44\,\lambda L/D \approx 3.57\) m at \(L=7.31\times10^9\) m. Order-of-magnitude against the circular-equivalent 1 g row. It does not guarantee full power on the 3.57 m sail. Launch stills use a diamond planform; this check is not re-fit to that outline.

## Obsolete model

**CANON.** Constant 0.001 \(g_0\) bang-coast-bang with ~198 yr burns and a ~5 106 yr Kepler transit is an obsolete default. Keep it only as a labelled historical note. That model gave a 7191–7201 A.D. arrival band by adding two long burns. Do not reuse that band as the current arrival window.
