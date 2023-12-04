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
| mattcl | input-pting | 0.8 ± 0.4 | 0.2 | 3.3 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.7 | 1.27 ± 0.61 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.3 | 1.28 ± 0.61 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.2 | 1.8 | 1.31 ± 0.62 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.5 | 1.32 ± 0.63 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.8 | 1.35 ± 0.68 |
| lanjian | input-pting | 1.9 ± 0.3 | 1.1 | 3.4 | 2.36 ± 1.11 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.3 | 2.9 | 2.47 ± 1.16 |
| lanjian | input-aspidites | 2.0 ± 0.3 | 1.4 | 3.1 | 2.52 ± 1.18 |
| lanjian | input-mattcl | 2.0 ± 0.3 | 1.4 | 3.2 | 2.52 ± 1.19 |
| lanjian | input-chancalan | 2.1 ± 0.4 | 1.4 | 3.3 | 2.56 ± 1.23 |
| lanjian | input-kcen | 2.1 ± 0.3 | 1.2 | 3.5 | 2.57 ± 1.23 |
| aspidites | input-mattcl | 13.0 ± 0.4 | 12.1 | 14.5 | 16.19 ± 7.30 |
| aspidites | input-kcen | 13.1 ± 0.5 | 12.0 | 14.6 | 16.25 ± 7.33 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 11.8 | 14.6 | 16.26 ± 7.33 |
| aspidites | input-pting | 13.1 ± 0.5 | 11.5 | 14.5 | 16.32 ± 7.36 |
| aspidites | input-chancalan | 13.2 ± 0.5 | 12.0 | 14.7 | 16.41 ± 7.40 |
| aspidites | input-lanjian | 13.2 ± 0.5 | 11.7 | 14.5 | 16.42 ± 7.40 |
| pting | input-mattcl | 18.2 ± 0.6 | 17.4 | 21.7 | 22.58 ± 10.18 |
| pting | input-kcen | 18.2 ± 0.7 | 17.2 | 21.3 | 22.64 ± 10.21 |
| pting | input-aspidites | 18.3 ± 0.8 | 17.0 | 21.8 | 22.75 ± 10.27 |
| pting | input-chancalan | 18.3 ± 0.9 | 17.2 | 21.7 | 22.77 ± 10.29 |
| pting | input-pting | 18.5 ± 0.9 | 17.3 | 21.9 | 22.93 ± 10.36 |
| pting | input-lanjian | 18.5 ± 1.0 | 17.5 | 21.5 | 22.95 ± 10.38 |
| mattcl-py | input-aspidites | 18.7 ± 0.6 | 17.7 | 21.8 | 23.24 ± 10.47 |
| chancalan | input-mattcl | 18.7 ± 0.6 | 17.4 | 21.3 | 23.26 ± 10.48 |
| mattcl-py | input-pting | 18.7 ± 0.5 | 17.9 | 21.4 | 23.27 ± 10.48 |
| mattcl-py | input-lanjian | 18.7 ± 0.7 | 17.5 | 22.0 | 23.28 ± 10.50 |
| mattcl-py | input-chancalan | 18.8 ± 0.7 | 17.7 | 21.4 | 23.29 ± 10.50 |
| chancalan | input-kcen | 18.8 ± 0.7 | 17.5 | 21.8 | 23.30 ± 10.51 |
| chancalan | input-aspidites | 18.8 ± 0.8 | 17.4 | 22.1 | 23.31 ± 10.52 |
| chancalan | input-chancalan | 18.8 ± 0.8 | 17.4 | 22.2 | 23.31 ± 10.52 |
| chancalan | input-lanjian | 18.8 ± 0.8 | 17.6 | 22.0 | 23.31 ± 10.52 |
| mattcl-py | input-mattcl | 18.8 ± 0.7 | 18.0 | 21.9 | 23.34 ± 10.53 |
| mattcl-py | input-kcen | 18.9 ± 2.7 | 17.5 | 51.9 | 23.45 ± 11.05 |
| chancalan | input-pting | 18.9 ± 0.8 | 17.3 | 21.7 | 23.46 ± 10.59 |
| kcen | input-lanjian | 19.0 ± 0.6 | 17.6 | 21.6 | 23.55 ± 10.61 |
| kcen | input-mattcl | 19.0 ± 0.7 | 17.8 | 21.7 | 23.62 ± 10.65 |
| kcen | input-chancalan | 19.1 ± 0.9 | 17.7 | 22.6 | 23.72 ± 10.72 |
| kcen | input-aspidites | 19.2 ± 0.8 | 18.1 | 22.1 | 23.80 ± 10.74 |
| kcen | input-pting | 19.2 ± 0.8 | 17.9 | 22.9 | 23.83 ± 10.76 |
| kcen | input-kcen | 19.2 ± 1.0 | 17.7 | 25.6 | 23.86 ± 10.80 |
| mikofo | input-aspidites | 316.9 ± 2.2 | 312.3 | 319.9 | 393.52 ± 176.86 |
| mikofo | input-chancalan | 317.3 ± 2.6 | 313.1 | 320.3 | 394.04 ± 177.10 |
| mikofo | input-kcen | 320.3 ± 3.2 | 313.7 | 323.6 | 397.74 ± 178.78 |
| mikofo | input-pting | 320.3 ± 1.9 | 317.5 | 322.6 | 397.77 ± 178.77 |
| mikofo | input-mattcl | 320.5 ± 3.2 | 315.4 | 324.5 | 397.95 ± 178.87 |
| mikofo | input-lanjian | 320.5 ± 1.5 | 318.5 | 322.5 | 398.07 ± 178.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|