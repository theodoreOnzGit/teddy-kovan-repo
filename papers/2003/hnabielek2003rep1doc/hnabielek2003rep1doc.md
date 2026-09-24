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

# Annotation (p10) — f(tau) formula used in eq(4)

```toml
[kovan]
id = "annotation-p10-f-tau-formula-used-in-eq-4"
kind = "annotation"
created = "2026-09-24T04:47:23Z"
modified = "2026-09-24T04:49:26Z"

[source]
page = 10
region = [
    0.15379303693771362,
    0.7245659828186035,
    0.9365618228912354,
    0.9562377333641052,
]
```

f(tau) formula used in eq(4)

f_tau = 1 - 6/tau * summation term

summation term = sum (from 1 to infty) (1 - numerator/denominator)

numerator = exp( - n^2 * pi^2 * tau)
denominator = n^4 * pi^4

numerator is terminated after 1000 terms, or if two consective 
summations differ by no more than 1e-20
# Annotation (p10) — Equation 4 relative fraction of fission gas release

```toml
[kovan]
id = "annotation-p10-equation-4-relative-fraction-of-fission-gas-release"
kind = "annotation"
created = "2026-09-24T04:47:23Z"
modified = "2026-09-24T04:47:23Z"

[source]
page = 10
region = [
    0.14575646817684174,
    0.5237429738044739,
    0.9398344159126282,
    0.6676387786865234,
]
```

Equation 4 

relative fraction of fission gas release (F_d)

F_d = numerator / tau_i

numerator = (tau_i + tau_a) * f (tau_i + tau_a) - tau_a * f (tau_a)

# Annotation (p11) — tau_i = DS (T_B) * t_B tau_a =

```toml
[kovan]
id = "annotation-p11-tau-i-ds-t-b-t-b-tau-a"
kind = "annotation"
created = "2026-09-24T04:57:51Z"
modified = "2026-09-24T04:57:51Z"

[source]
page = 11
region = [
    0.137483611702919,
    0.5881931781768799,
    0.8520141839981079,
    0.8411582112312317,
]
```

tau_i = DS (T_B) * t_B
tau_a = DS (T) * t 

DS is reduced diffusion coeff in 1/s for fission gases in particle kernel

DS = D_eff / r_o^2 
r_o = particle kernel radius
t = accident time 
T_B = irradiation temp [K]
t_B = irradiation time (s)
t = accident time (s)

# Annotation (p11) — F_b is burnup

```toml
[kovan]
id = "annotation-p11-f-b-is-burnup"
kind = "annotation"
created = "2026-09-24T05:01:17Z"
modified = "2026-09-24T05:01:17Z"

[source]
page = 11
region = [
    0.13864898681640625,
    0.8981607556343079,
    0.826383113861084,
    0.9292854070663452,
]
```

F_b is burnup

# Annotation (p12) — relation for thorium dioxide log DS = -

```toml
[kovan]
id = "annotation-p12-relation-for-thorium-dioxide-log-ds"
kind = "annotation"
created = "2026-09-24T04:59:28Z"
modified = "2026-09-24T04:59:28Z"

[source]
page = 12
region = [
    0.22147071361541748,
    0.5122373104095459,
    0.821500837802887,
    0.5966715216636658,
]
```

relation for thorium dioxide 

log DS = - 5.94 + num_1/denom_1 - num_2/denom_2

num_1 = 3.24
denom_1 = 1 + 0.11/F_B
num_2 = 0.5460e4
denom_2 = T

# Annotation (p12) — log DS = -2.30 - 0.8116e4/T

```toml
[kovan]
id = "annotation-p12-log-ds-2-30-0-8116e4-t"
kind = "annotation"
created = "2026-09-24T04:59:28Z"
modified = "2026-09-24T04:59:28Z"

[source]
page = 12
region = [
    0.14314623177051544,
    0.604202151298523,
    0.8729895949363708,
    0.7764316201210022,
]
```

log DS = -2.30 - 0.8116e4/T

# Annotation (p12) — Fig 2 will give a good basis of

```toml
[kovan]
id = "annotation-p12-fig-2-will-give-a-good-basis-of"
kind = "annotation"
created = "2026-09-24T05:00:36Z"
modified = "2026-09-24T05:00:36Z"

[source]
page = 12
region = [
    0.17097918689250946,
    0.4550877511501312,
    0.8712224960327148,
    0.4911489188671112,
]
```

Fig 2 will give a good basis of comparison for testing the formulae, see if coded correct
