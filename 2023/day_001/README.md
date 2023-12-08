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
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.5 | 1.02 ± 0.29 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.31 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.28 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.4 | 1.05 ± 0.30 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.7 | 1.06 ± 0.31 |
| lanjian | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.9 | 1.06 ± 0.32 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.30 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.3 | 1.2 | 1.08 ± 0.28 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.7 | 1.09 ± 0.30 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 10.9 | 13.4 | 12.98 ± 2.89 |
| mattcl-ts | input-aspidites | 12.1 ± 0.4 | 11.0 | 13.1 | 12.98 ± 2.89 |
| mattcl-ts | input-pting | 12.2 ± 0.4 | 11.1 | 13.0 | 13.02 ± 2.89 |
| mattcl-ts | input-kcen | 12.2 ± 0.4 | 11.3 | 13.1 | 13.04 ± 2.89 |
| mattcl-ts | input-lanjian | 12.2 ± 0.4 | 11.3 | 13.1 | 13.05 ± 2.90 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.3 | 13.2 | 13.05 ± 2.90 |
| mattcl-ts | input-chancalan | 12.6 ± 4.8 | 11.1 | 65.7 | 13.47 ± 5.89 |
| aspidites | input-chancalan | 12.6 ± 0.5 | 11.5 | 14.4 | 13.51 ± 3.02 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.6 | 13.9 | 13.58 ± 3.03 |
| aspidites | input-pting | 12.7 ± 0.9 | 11.1 | 23.7 | 13.62 ± 3.16 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.7 | 14.0 | 13.64 ± 3.04 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.6 | 13.8 | 13.67 ± 3.05 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.9 | 14.0 | 13.69 ± 3.05 |
| aspidites | input-mikofo | 12.8 ± 0.4 | 11.8 | 14.2 | 13.71 ± 3.05 |
| pting | input-chancalan | 15.4 ± 0.6 | 14.3 | 18.3 | 16.49 ± 3.68 |
| pting | input-lanjian | 15.4 ± 0.6 | 14.5 | 18.9 | 16.54 ± 3.70 |
| pting | input-kcen | 15.4 ± 0.6 | 14.5 | 18.5 | 16.55 ± 3.70 |
| pting | input-pting | 15.5 ± 0.7 | 14.5 | 18.5 | 16.56 ± 3.72 |
| pting | input-mattcl | 15.5 ± 0.6 | 14.5 | 18.0 | 16.58 ± 3.70 |
| pting | input-mikofo | 15.5 ± 0.7 | 14.7 | 18.9 | 16.61 ± 3.73 |
| pting | input-aspidites | 15.6 ± 1.8 | 14.3 | 38.2 | 16.71 ± 4.16 |
| mattcl-py | input-mikofo | 15.6 ± 0.6 | 14.7 | 18.9 | 16.72 ± 3.73 |
| mattcl-py | input-mattcl | 15.7 ± 0.6 | 14.8 | 18.6 | 16.77 ± 3.75 |
| mattcl-py | input-lanjian | 15.7 ± 0.7 | 14.6 | 18.7 | 16.83 ± 3.78 |
| mattcl-py | input-pting | 15.7 ± 0.6 | 14.8 | 18.4 | 16.85 ± 3.76 |
| mattcl-py | input-chancalan | 15.7 ± 0.7 | 14.7 | 18.7 | 16.85 ± 3.77 |
| mattcl-py | input-aspidites | 15.7 ± 0.6 | 15.0 | 19.3 | 16.86 ± 3.77 |
| mattcl-py | input-kcen | 15.7 ± 0.6 | 14.9 | 18.9 | 16.87 ± 3.76 |
| chancalan | input-aspidites | 15.8 ± 0.6 | 14.7 | 18.6 | 16.96 ± 3.79 |
| chancalan | input-lanjian | 15.8 ± 0.8 | 14.8 | 19.0 | 16.96 ± 3.82 |
| chancalan | input-kcen | 15.9 ± 0.7 | 14.7 | 19.8 | 16.98 ± 3.81 |
| chancalan | input-mattcl | 15.9 ± 0.7 | 14.7 | 18.9 | 17.02 ± 3.81 |
| chancalan | input-chancalan | 16.0 ± 0.8 | 14.7 | 19.6 | 17.13 ± 3.86 |
| chancalan | input-mikofo | 16.1 ± 2.3 | 14.9 | 45.7 | 17.22 ± 4.52 |
| kcen | input-mattcl | 16.2 ± 0.5 | 15.0 | 19.0 | 17.36 ± 3.86 |
| kcen | input-aspidites | 16.3 ± 0.5 | 15.3 | 18.7 | 17.47 ± 3.89 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.6 | 17.49 ± 3.91 |
| chancalan | input-pting | 16.3 ± 3.5 | 14.7 | 48.8 | 17.50 ± 5.37 |
| kcen | input-pting | 16.4 ± 0.6 | 15.4 | 19.0 | 17.53 ± 3.92 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.3 | 19.0 | 17.54 ± 3.94 |
| kcen | input-mikofo | 16.4 ± 0.6 | 15.4 | 19.4 | 17.54 ± 3.91 |
| kcen | input-chancalan | 16.5 ± 2.1 | 15.3 | 41.0 | 17.69 ± 4.47 |
| mikofo | input-pting | 31.4 ± 0.5 | 30.5 | 33.1 | 33.65 ± 7.42 |
| mikofo | input-lanjian | 31.4 ± 0.4 | 30.3 | 33.2 | 33.66 ± 7.42 |
| mikofo | input-chancalan | 31.5 ± 0.4 | 30.6 | 32.5 | 33.71 ± 7.43 |
| mikofo | input-mikofo | 31.5 ± 0.4 | 30.4 | 33.1 | 33.75 ± 7.44 |
| mikofo | input-aspidites | 31.5 ± 0.6 | 30.6 | 35.6 | 33.76 ± 7.46 |
| mikofo | input-mattcl | 31.5 ± 0.4 | 30.4 | 32.7 | 33.78 ± 7.45 |
| mikofo | input-kcen | 32.4 ± 7.4 | 30.4 | 97.1 | 34.69 ± 11.00 |


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