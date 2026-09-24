# hnabielek2003rep1doc

```toml
[kovan]
id = "hnabielek2003rep1doc"
kind = "paper"
created = "2026-09-24T02:41:10Z"
modified = "2026-09-24T03:20:30Z"
```

## Summary
# Annotation (p1) — PANAMA for TRISO particles (Germany)

```toml
connections = ["cc6edec73a6c"]

[kovan]
id = "annotation-p1-panama-for-triso-particles-germany"
kind = "annotation"
created = "2026-09-24T02:41:37Z"
modified = "2026-09-24T02:47:58Z"

[source]
page = 1
region = [
    0.10899519920349121,
    0.1926383227109909,
    0.8901438117027283,
    0.24804478883743286,
]
```

PANAMA for TRISO particles (Germany)

# Annotation (p5) — Total failure fraction phi_total = 1 - (1-

```toml
[kovan]
id = "annotation-p5-total-failure-fraction-phi-total-1-1"
kind = "annotation"
created = "2026-09-24T04:34:35Z"
modified = "2026-09-24T04:34:35Z"

[source]
page = 5
region = [
    0.2535969913005829,
    0.5788781046867371,
    0.7505333423614502,
    0.634835958480835,
]
```

Total failure fraction 

phi_total = 1 - (1-  phi_0) * (1 - phi_1) * (1- phi_2)

# Annotation (p5) — phi_0 represents manufacturing defects failure fraction. For PANAMA

```toml
[kovan]
id = "annotation-p5-phi-0-represents-manufacturing-defects-failure-fraction-for-panama"
kind = "annotation"
created = "2026-09-24T04:34:35Z"
modified = "2026-09-24T04:34:35Z"

[source]
page = 5
region = [
    0.13389210402965546,
    0.6485690474510193,
    0.8591635227203369,
    0.7813013195991516,
]
```

phi_0 represents manufacturing defects failure fraction. 

For PANAMA manual, this is assumed 0, perfect TRISO

# Annotation (p5) — phi_0 ballpark figure is 6.0e-5

```toml
[kovan]
id = "annotation-p5-phi-0-ballpark-figure-is-6-0e-5"
kind = "annotation"
created = "2026-09-24T04:34:35Z"
modified = "2026-09-24T04:34:35Z"

[source]
page = 5
region = [
    0.1311049610376358,
    0.8002920746803284,
    0.8709623217582703,
    0.8448677659034729,
]
```

phi_0 ballpark figure is 6.0e-5

# Annotation (p8) — this is the pressure vessel model phi_1 (t,T)

```toml
[kovan]
id = "annotation-p8-this-is-the-pressure-vessel-model-phi-1-t-t"
kind = "annotation"
created = "2026-09-24T04:37:47Z"
modified = "2026-09-24T04:37:47Z"

[source]
page = 8
region = [
    0.10959598422050476,
    0.3498976230621338,
    0.9524939656257629,
    0.7877698540687561,
]
```

this is the pressure vessel model 

phi_1 (t,T) = 1 - exp( -ln 2 * (sigma_t/sigma_o)^m)

sigma_t = stress in SiC layer due to internal gas pressure 
sigma_o = SiC tensile strength at end of irradiation

# Annotation (p9) — tensile stress formula sigma_t = A * B

```toml
[kovan]
id = "annotation-p9-tensile-stress-formula-sigma-t-a-b"
kind = "annotation"
created = "2026-09-24T04:38:53Z"
modified = "2026-09-24T04:38:53Z"

[source]
page = 9
region = [
    0.09490926563739777,
    0.06649124622344971,
    0.9729666709899902,
    0.5515994429588318,
]
```

tensile stress formula 
sigma_t = A * B

A = (r * p)/(2 * d_0)
B = (1 + v * t / d_0)

# Annotation (p9) — fission gas internal pressure p p = numerator/denominator

```toml
[kovan]
id = "annotation-p9-fission-gas-internal-pressure-p-p-numerator-denominator"
kind = "annotation"
created = "2026-09-24T04:39:48Z"
modified = "2026-09-24T04:45:30Z"

[source]
page = 9
region = [
    0.24226990342140198,
    0.6866704225540161,
    0.9216597080230713,
    0.7887784242630005,
]
```

fission gas internal pressure p 

p = numerator/denominator

numerator =  (F_d * F_f + OPF) * F_b
denominator = (V_f/V_k * R * T / V_m)

F_d = relative fraction of fission gas release 
OPF = number of oxygen atoms per fission
V_m = molar volume in particle kernel m3/mole
F_f = fission product yield from stable fission gases (0.31)
F_b = heavy metal burnup (FIMA)
V_k = kernel volume (m3)
V_f = void fraction (m3), corresponding to 50% of buffer vol 
R = Molar gas constant
