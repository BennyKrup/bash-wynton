# Bash, Wynton and CoreHPC

Presentation by Beniamin Krupkin, September 9, 2026.
Adapted from [Alex J. Lee’s Bash and Wynton lesson](https://github.com/alexj-lee/bash-wynton), preserving the original lesson and Reveal.js assets. Original license retained.

## Present

[Open slides](https://BennyKrup.github.io/bash-wynton/)

- Arrow keys / Space: advance; Esc: overview; F: fullscreen; S: speaker view.
- [Practical HPC tips](https://BennyKrup.github.io/bash-wynton/#/hpc-tips)
- [CoreHPC transition](https://BennyKrup.github.io/bash-wynton/#/corehpc)

## September 2026 updates

- One practical HPC tips slide: small tests, clear failures, stable inputs, thread allocation and output checks.
- CoreHPC transition, SGE-to-Slurm commands, an illustrative array template and migration checks.
- Old course-specific signup instructions removed; author attribution and license preserved.
- Speaker notes hidden from audience view; use S for presenter mode.

Official Wynton retirement is **early March 2027**, per the [March 1, 2026 announcement](https://wynton.ucsf.edu/hpc/about/news.html). February 2027 is a suggested migration target, not the official retirement date. The presenter supplied the Slurm transition information; CoreHPC account/partition/storage details need confirmation through [UCSF onboarding](https://it.ucsf.edu/service/corehpc).

The original Wynton material is historical SGE training, not a current CoreHPC operations manual. The Slurm example is a teaching template; its resources and analysis.py are illustrative. No cluster jobs were submitted or validated by preparing this deck.

## Local preview

Run `python3 -m http.server 8765` in this folder and open http://localhost:8765/. The original lesson uses external Tailwind/font assets, so a network connection is recommended.

## Sources

- https://wynton.ucsf.edu/hpc/about/news.html
- https://it.ucsf.edu/service/corehpc
- https://slurm.schedmd.com/sbatch.html
- https://slurm.schedmd.com/job_array.html

## License

MIT; see LICENSE for original Reveal.js copyright and terms.
