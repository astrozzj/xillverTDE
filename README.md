# xillverTDE

`xillverTDE.fits` is an additive XSPEC table model in the `xillver`/`relxill` family for modeling X-ray reflection in tidal disruption event (TDE) and other soft, super-Eddington systems. It uses a single-temperature blackbody illuminating spectrum. For more details about the model, please refer to Masterson, M., Kara, E., Ricci, C., et al. 2022, ApJ 934, 35. 

Use it in XSPEC with:

```xspec
model atable{xillverTDE.fits}
```

## Attribution

If you use `xillverTDE` provided in this repository in a publication, please kindly cite the paper that introduced and first applied the model:

Masterson, M., Kara, E., Ricci, C., et al. 2022, [*The Astrophysical Journal*, 934, 35.](https://doi.org/10.3847/1538-4357/ac76c0) | [arXiv:2206.05140](https://arxiv.org/abs/2206.05140)

It is also used in [Jin et al., *An Intermediate-mass Black Hole Lurking in A Galactic Halo Caught Alive during Outburst*](https://arxiv.org/abs/2501.09580) (arXiv:2501.09580).

For the official `relxill` model, documentation, and releases, see the [relxill website](https://www.sternwarte.uni-erlangen.de/~dauser/research/relxill/).

## File integrity

SHA-256 for `xillverTDE.fits`:

```text
c18d6f9fd7aad0edd55c4260e46e9bcb32d110c3d6d98a15e0ec50c5c4b18377
```
