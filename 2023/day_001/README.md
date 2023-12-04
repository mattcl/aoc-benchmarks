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
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.1 | 1.5 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.26 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.2 | 1.07 ± 0.24 |
| lanjian | input-pting | 1.9 ± 0.2 | 1.4 | 2.7 | 1.99 ± 0.45 |
| lanjian | input-mattcl | 1.9 ± 0.3 | 1.3 | 3.4 | 2.03 ± 0.47 |
| lanjian | input-aspidites | 1.9 ± 0.3 | 1.2 | 3.0 | 2.03 ± 0.49 |
| lanjian | input-chancalan | 1.9 ± 0.3 | 1.4 | 3.2 | 2.04 ± 0.48 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.4 | 3.0 | 2.05 ± 0.49 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.3 | 3.1 | 2.08 ± 0.48 |
| aspidites | input-aspidites | 13.0 ± 0.4 | 12.2 | 14.2 | 13.94 ± 2.66 |
| aspidites | input-chancalan | 13.0 ± 0.5 | 11.9 | 14.3 | 13.95 ± 2.67 |
| aspidites | input-mattcl | 13.0 ± 0.5 | 12.0 | 14.8 | 13.98 ± 2.67 |
| aspidites | input-pting | 13.0 ± 0.5 | 12.1 | 14.2 | 13.98 ± 2.68 |
| aspidites | input-lanjian | 13.1 ± 0.5 | 11.4 | 14.4 | 14.04 ± 2.69 |
| aspidites | input-kcen | 13.1 ± 0.4 | 12.0 | 14.3 | 14.08 ± 2.69 |
| pting | input-kcen | 17.9 ± 0.7 | 16.9 | 21.5 | 19.18 ± 3.68 |
| pting | input-lanjian | 18.0 ± 0.8 | 17.1 | 20.8 | 19.26 ± 3.71 |
| pting | input-aspidites | 18.0 ± 0.8 | 16.9 | 21.4 | 19.30 ± 3.73 |
| pting | input-chancalan | 18.0 ± 0.6 | 17.2 | 20.5 | 19.31 ± 3.69 |
| pting | input-pting | 18.0 ± 0.7 | 17.1 | 21.5 | 19.33 ± 3.72 |
| pting | input-mattcl | 18.1 ± 0.9 | 16.9 | 21.5 | 19.43 ± 3.77 |
| chancalan | input-aspidites | 18.5 ± 0.6 | 17.4 | 21.5 | 19.79 ± 3.78 |
| chancalan | input-kcen | 18.5 ± 0.6 | 17.5 | 21.8 | 19.82 ± 3.79 |
| chancalan | input-lanjian | 18.5 ± 0.7 | 17.4 | 21.2 | 19.82 ± 3.79 |
| mattcl-py | input-aspidites | 18.5 ± 0.8 | 17.4 | 21.8 | 19.85 ± 3.83 |
| mattcl-py | input-lanjian | 18.5 ± 0.7 | 17.4 | 21.4 | 19.88 ± 3.82 |
| chancalan | input-chancalan | 18.6 ± 0.8 | 17.4 | 21.5 | 19.94 ± 3.84 |
| mattcl-py | input-chancalan | 18.6 ± 0.7 | 17.5 | 21.6 | 19.94 ± 3.82 |
| mattcl-py | input-mattcl | 18.6 ± 0.9 | 17.5 | 21.8 | 19.94 ± 3.86 |
| mattcl-py | input-pting | 18.6 ± 0.6 | 17.5 | 21.4 | 19.94 ± 3.81 |
| chancalan | input-pting | 18.7 ± 0.7 | 17.4 | 21.6 | 20.01 ± 3.84 |
| chancalan | input-mattcl | 18.7 ± 0.8 | 17.8 | 21.2 | 20.01 ± 3.84 |
| kcen | input-pting | 18.8 ± 0.5 | 17.9 | 21.6 | 20.12 ± 3.82 |
| mattcl-py | input-kcen | 18.8 ± 1.7 | 17.4 | 37.4 | 20.14 ± 4.19 |
| kcen | input-lanjian | 18.8 ± 0.6 | 17.7 | 21.8 | 20.16 ± 3.85 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.6 | 21.9 | 20.17 ± 3.87 |
| kcen | input-mattcl | 18.8 ± 0.7 | 17.9 | 21.8 | 20.18 ± 3.87 |
| kcen | input-aspidites | 18.9 ± 0.8 | 18.0 | 22.1 | 20.22 ± 3.89 |
| kcen | input-chancalan | 18.9 ± 0.8 | 17.8 | 21.4 | 20.23 ± 3.89 |
| mikofo | input-aspidites | 314.6 ± 2.7 | 311.2 | 319.8 | 337.28 ± 63.43 |
| mikofo | input-kcen | 314.8 ± 2.3 | 311.3 | 319.1 | 337.45 ± 63.44 |
| mikofo | input-chancalan | 314.8 ± 1.5 | 311.4 | 316.2 | 337.46 ± 63.42 |
| mikofo | input-pting | 315.6 ± 1.7 | 313.6 | 318.7 | 338.30 ± 63.58 |
| mikofo | input-lanjian | 315.7 ± 1.9 | 312.5 | 318.7 | 338.43 ± 63.61 |
| mikofo | input-mattcl | 316.5 ± 1.8 | 313.6 | 318.7 | 339.33 ± 63.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|