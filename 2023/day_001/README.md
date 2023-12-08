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
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.28 |
| mattcl | input-aspidites | 1.0 ± 0.1 | 0.4 | 1.1 | 1.02 ± 0.25 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.3 | 1.02 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.26 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.4 | 1.04 ± 0.28 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.2 | 1.2 | 1.04 ± 0.25 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.4 | 1.3 | 1.05 ± 0.25 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.27 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.6 | 1.06 ± 0.28 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.5 | 1.2 | 1.06 ± 0.26 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.27 |
| lanjian | input-mikofo | 1.0 ± 0.1 | 0.5 | 1.3 | 1.07 ± 0.26 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.5 | 1.08 ± 0.27 |
| mattcl-ts | input-lanjian | 12.2 ± 0.4 | 11.2 | 13.0 | 12.57 ± 2.48 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.2 | 13.0 | 12.62 ± 2.49 |
| mattcl-ts | input-mikofo | 12.2 ± 0.4 | 11.2 | 13.3 | 12.64 ± 2.50 |
| mattcl-ts | input-aspidites | 12.2 ± 0.4 | 11.2 | 13.3 | 12.66 ± 2.50 |
| mattcl-ts | input-kcen | 12.3 ± 0.4 | 11.3 | 13.4 | 12.67 ± 2.50 |
| mattcl-ts | input-pting | 12.3 ± 0.4 | 11.2 | 13.1 | 12.75 ± 2.51 |
| mattcl-ts | input-chancalan | 12.4 ± 2.9 | 11.2 | 52.6 | 12.82 ± 3.89 |
| mikofo | input-mikofo | 12.7 ± 0.3 | 11.6 | 13.5 | 13.09 ± 2.57 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.8 | 13.13 ± 2.58 |
| mikofo | input-kcen | 12.7 ± 0.3 | 11.7 | 13.9 | 13.13 ± 2.58 |
| mikofo | input-mattcl | 12.7 ± 0.4 | 11.8 | 15.0 | 13.13 ± 2.59 |
| mikofo | input-lanjian | 12.7 ± 0.3 | 11.9 | 13.5 | 13.15 ± 2.58 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.8 | 14.4 | 13.16 ± 2.62 |
| aspidites | input-kcen | 12.7 ± 0.4 | 11.8 | 13.9 | 13.17 ± 2.61 |
| mikofo | input-pting | 12.8 ± 0.3 | 12.0 | 13.9 | 13.19 ± 2.59 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.9 | 14.2 | 13.24 ± 2.62 |
| aspidites | input-mikofo | 12.8 ± 0.4 | 11.8 | 14.7 | 13.24 ± 2.62 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.9 | 14.0 | 13.25 ± 2.62 |
| aspidites | input-pting | 12.8 ± 0.5 | 11.9 | 14.1 | 13.28 ± 2.63 |
| aspidites | input-lanjian | 12.9 ± 0.5 | 11.7 | 14.4 | 13.31 ± 2.65 |
| mikofo | input-aspidites | 13.1 ± 4.6 | 11.8 | 77.0 | 13.50 ± 5.39 |
| pting | input-lanjian | 15.5 ± 0.6 | 14.7 | 18.8 | 16.00 ± 3.18 |
| pting | input-kcen | 15.5 ± 0.7 | 14.4 | 19.1 | 16.01 ± 3.20 |
| pting | input-aspidites | 15.5 ± 0.6 | 14.5 | 18.2 | 16.01 ± 3.18 |
| pting | input-mattcl | 15.5 ± 0.6 | 14.5 | 18.7 | 16.02 ± 3.18 |
| pting | input-pting | 15.6 ± 0.7 | 14.6 | 19.2 | 16.10 ± 3.21 |
| pting | input-mikofo | 15.6 ± 0.6 | 14.5 | 18.6 | 16.11 ± 3.21 |
| pting | input-chancalan | 15.6 ± 0.7 | 14.4 | 19.0 | 16.16 ± 3.24 |
| mattcl-py | input-lanjian | 15.8 ± 0.7 | 14.7 | 18.7 | 16.31 ± 3.25 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 15.0 | 19.0 | 16.36 ± 3.27 |
| mattcl-py | input-mattcl | 15.8 ± 0.7 | 15.0 | 19.4 | 16.36 ± 3.27 |
| chancalan | input-mattcl | 15.8 ± 0.5 | 14.9 | 18.5 | 16.37 ± 3.23 |
| mattcl-py | input-aspidites | 15.9 ± 0.7 | 14.8 | 18.7 | 16.42 ± 3.29 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 14.7 | 19.2 | 16.49 ± 3.30 |
| mattcl-py | input-chancalan | 16.0 ± 0.8 | 14.9 | 19.3 | 16.51 ± 3.32 |
| chancalan | input-mikofo | 16.0 ± 0.7 | 14.9 | 18.6 | 16.53 ± 3.30 |
| chancalan | input-lanjian | 16.0 ± 0.7 | 14.9 | 19.0 | 16.55 ± 3.31 |
| chancalan | input-chancalan | 16.0 ± 0.7 | 15.0 | 18.6 | 16.56 ± 3.30 |
| chancalan | input-pting | 16.0 ± 0.8 | 14.8 | 19.4 | 16.58 ± 3.34 |
| chancalan | input-aspidites | 16.0 ± 0.7 | 15.0 | 18.9 | 16.58 ± 3.31 |
| chancalan | input-kcen | 16.1 ± 0.8 | 14.9 | 18.8 | 16.62 ± 3.33 |
| mattcl-py | input-mikofo | 16.1 ± 4.3 | 14.6 | 72.2 | 16.68 ± 5.47 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.7 | 16.90 ± 3.36 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.1 | 19.6 | 16.93 ± 3.37 |
| kcen | input-pting | 16.4 ± 0.6 | 15.4 | 19.4 | 16.99 ± 3.37 |
| kcen | input-aspidites | 16.5 ± 0.7 | 15.4 | 19.8 | 17.04 ± 3.39 |
| kcen | input-mikofo | 16.6 ± 2.0 | 15.4 | 40.9 | 17.16 ± 3.91 |
| kcen | input-chancalan | 16.6 ± 1.4 | 15.3 | 32.8 | 17.17 ± 3.65 |
| kcen | input-mattcl | 16.7 ± 3.2 | 15.4 | 57.5 | 17.24 ± 4.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-mikofo|<pre>55538</pre>|<pre>54875</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|