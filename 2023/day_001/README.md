# Day 1 benchmarks

[link to problem](https://adventofcode.com/2023/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [aspidites](https://github.com/aspidites/aoc2023) (haskell)
- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-aspidites | 1.0 ± 0.1 | 0.3 | 1.3 | 1.02 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.4 | 1.6 | 1.05 ± 0.29 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.2 | 1.06 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.2 | 1.06 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.2 | 1.08 ± 0.27 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 1.2 | 2.7 | 1.98 ± 0.50 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.3 | 3.1 | 1.99 ± 0.50 |
| lanjian | input-pting | 1.9 ± 0.2 | 1.3 | 2.7 | 2.01 ± 0.51 |
| lanjian | input-aspidites | 1.9 ± 0.2 | 1.4 | 3.0 | 2.01 ± 0.51 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.3 | 2.7 | 2.02 ± 0.52 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.3 | 3.9 | 2.05 ± 0.54 |
| aspidites | input-lanjian | 12.9 ± 0.4 | 11.9 | 14.1 | 13.93 ± 3.11 |
| aspidites | input-pting | 13.0 ± 0.4 | 11.9 | 14.1 | 14.01 ± 3.13 |
| aspidites | input-chancalan | 13.0 ± 0.4 | 12.0 | 14.1 | 14.02 ± 3.13 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.1 | 14.6 | 14.05 ± 3.15 |
| aspidites | input-kcen | 13.1 ± 0.4 | 11.8 | 14.5 | 14.06 ± 3.15 |
| aspidites | input-mattcl | 13.1 ± 0.5 | 11.6 | 14.2 | 14.08 ± 3.16 |
| pting | input-chancalan | 17.8 ± 0.6 | 16.8 | 20.7 | 19.19 ± 4.30 |
| pting | input-pting | 17.9 ± 0.6 | 17.1 | 21.1 | 19.21 ± 4.30 |
| pting | input-aspidites | 17.9 ± 0.8 | 17.1 | 20.9 | 19.26 ± 4.35 |
| pting | input-mattcl | 17.9 ± 0.6 | 16.7 | 20.8 | 19.28 ± 4.33 |
| pting | input-kcen | 18.0 ± 0.7 | 17.0 | 21.4 | 19.34 ± 4.35 |
| pting | input-lanjian | 18.0 ± 0.8 | 16.9 | 21.1 | 19.41 ± 4.39 |
| mattcl-py | input-aspidites | 18.3 ± 0.6 | 17.2 | 20.8 | 19.73 ± 4.41 |
| chancalan | input-lanjian | 18.4 ± 0.6 | 17.4 | 21.5 | 19.78 ± 4.42 |
| chancalan | input-aspidites | 18.4 ± 0.8 | 17.2 | 21.6 | 19.82 ± 4.47 |
| chancalan | input-mattcl | 18.4 ± 0.6 | 17.4 | 21.4 | 19.83 ± 4.45 |
| mattcl-py | input-mattcl | 18.5 ± 0.6 | 17.4 | 21.4 | 19.88 ± 4.45 |
| mattcl-py | input-pting | 18.5 ± 0.5 | 17.6 | 21.3 | 19.89 ± 4.44 |
| mattcl-py | input-kcen | 18.5 ± 0.7 | 17.6 | 21.8 | 19.91 ± 4.46 |
| mattcl-py | input-lanjian | 18.5 ± 0.8 | 17.4 | 22.0 | 19.91 ± 4.48 |
| chancalan | input-kcen | 18.5 ± 0.7 | 17.6 | 22.2 | 19.93 ± 4.48 |
| mattcl-py | input-chancalan | 18.5 ± 0.8 | 17.2 | 21.7 | 19.94 ± 4.49 |
| chancalan | input-pting | 18.6 ± 1.3 | 17.2 | 32.0 | 20.01 ± 4.63 |
| kcen | input-lanjian | 18.7 ± 0.7 | 17.6 | 21.9 | 20.13 ± 4.52 |
| kcen | input-mattcl | 18.7 ± 0.6 | 17.8 | 21.7 | 20.16 ± 4.51 |
| chancalan | input-chancalan | 18.7 ± 4.1 | 17.2 | 65.8 | 20.17 ± 6.27 |
| kcen | input-aspidites | 18.8 ± 0.8 | 17.7 | 21.8 | 20.19 ± 4.55 |
| kcen | input-chancalan | 18.8 ± 0.8 | 17.9 | 22.3 | 20.25 ± 4.57 |
| kcen | input-kcen | 18.8 ± 0.8 | 17.7 | 21.6 | 20.27 ± 4.56 |
| kcen | input-pting | 19.1 ± 4.0 | 18.1 | 67.4 | 20.55 ± 6.23 |
| mikofo | input-kcen | 313.5 ± 1.6 | 309.7 | 314.9 | 337.40 ± 74.72 |
| mikofo | input-mattcl | 314.0 ± 2.0 | 310.1 | 316.4 | 337.92 ± 74.84 |
| mikofo | input-pting | 314.4 ± 1.8 | 310.4 | 316.2 | 338.29 ± 74.92 |
| mikofo | input-chancalan | 314.6 ± 1.3 | 312.7 | 316.1 | 338.52 ± 74.95 |
| mikofo | input-lanjian | 314.6 ± 2.0 | 309.8 | 316.2 | 338.55 ± 74.98 |
| mikofo | input-aspidites | 314.8 ± 1.5 | 311.4 | 316.8 | 338.77 ± 75.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|