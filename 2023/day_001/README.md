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
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.34 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.34 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.07 ± 0.33 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.4 | 1.7 | 1.10 ± 0.36 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.2 | 1.3 | 1.10 ± 0.33 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.1 | 3.2 | 1.98 ± 0.57 |
| lanjian | input-aspidites | 1.8 ± 0.2 | 1.0 | 2.7 | 1.99 ± 0.56 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 1.3 | 2.8 | 2.00 ± 0.57 |
| lanjian | input-kcen | 1.8 ± 0.2 | 1.3 | 3.2 | 2.01 ± 0.58 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.7 | 2.08 ± 0.61 |
| lanjian | input-pting | 1.9 ± 0.3 | 1.3 | 3.3 | 2.09 ± 0.63 |
| aspidites | input-mattcl | 13.0 ± 0.4 | 12.0 | 14.0 | 14.19 ± 3.79 |
| aspidites | input-chancalan | 13.0 ± 0.4 | 12.2 | 14.5 | 14.21 ± 3.80 |
| aspidites | input-pting | 13.0 ± 0.5 | 11.4 | 14.1 | 14.23 ± 3.82 |
| aspidites | input-lanjian | 13.1 ± 0.4 | 12.1 | 14.1 | 14.26 ± 3.82 |
| aspidites | input-aspidites | 13.1 ± 0.4 | 12.2 | 14.3 | 14.28 ± 3.82 |
| aspidites | input-kcen | 13.1 ± 0.4 | 12.2 | 14.6 | 14.30 ± 3.83 |
| pting | input-lanjian | 17.9 ± 0.7 | 17.0 | 21.4 | 19.57 ± 5.25 |
| pting | input-aspidites | 18.0 ± 0.8 | 17.1 | 21.2 | 19.60 ± 5.27 |
| pting | input-mattcl | 18.0 ± 0.8 | 17.2 | 21.2 | 19.62 ± 5.28 |
| pting | input-pting | 18.0 ± 0.7 | 17.1 | 20.9 | 19.65 ± 5.28 |
| pting | input-chancalan | 18.0 ± 0.7 | 17.2 | 21.4 | 19.69 ± 5.29 |
| chancalan | input-chancalan | 18.4 ± 0.5 | 17.3 | 21.4 | 20.07 ± 5.36 |
| mattcl-py | input-lanjian | 18.4 ± 0.5 | 17.5 | 21.1 | 20.11 ± 5.38 |
| pting | input-kcen | 18.4 ± 4.9 | 17.0 | 71.2 | 20.11 ± 7.58 |
| chancalan | input-kcen | 18.5 ± 0.6 | 17.7 | 20.9 | 20.15 ± 5.39 |
| mattcl-py | input-mattcl | 18.5 ± 0.6 | 17.4 | 21.3 | 20.17 ± 5.40 |
| chancalan | input-aspidites | 18.5 ± 0.8 | 17.4 | 21.3 | 20.18 ± 5.44 |
| chancalan | input-lanjian | 18.5 ± 0.7 | 17.6 | 21.8 | 20.21 ± 5.42 |
| mattcl-py | input-chancalan | 18.5 ± 0.6 | 17.5 | 21.5 | 20.23 ± 5.41 |
| mattcl-py | input-kcen | 18.5 ± 0.6 | 17.6 | 21.7 | 20.23 ± 5.42 |
| chancalan | input-pting | 18.5 ± 0.7 | 17.4 | 22.0 | 20.24 ± 5.42 |
| mattcl-py | input-aspidites | 18.5 ± 0.8 | 17.7 | 21.8 | 20.24 ± 5.45 |
| chancalan | input-mattcl | 18.5 ± 0.8 | 17.6 | 21.8 | 20.24 ± 5.45 |
| mattcl-py | input-pting | 18.6 ± 0.6 | 17.3 | 21.3 | 20.31 ± 5.44 |
| kcen | input-kcen | 18.7 ± 0.6 | 17.7 | 21.6 | 20.39 ± 5.46 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.8 | 22.2 | 20.42 ± 5.46 |
| kcen | input-chancalan | 18.8 ± 0.7 | 17.9 | 22.0 | 20.48 ± 5.49 |
| kcen | input-pting | 18.8 ± 0.6 | 18.0 | 21.7 | 20.48 ± 5.48 |
| kcen | input-mattcl | 18.8 ± 0.7 | 17.6 | 22.1 | 20.52 ± 5.50 |
| kcen | input-aspidites | 18.8 ± 0.7 | 17.9 | 21.8 | 20.55 ± 5.51 |
| mikofo | input-aspidites | 313.4 ± 1.3 | 311.7 | 315.9 | 342.05 ± 90.89 |
| mikofo | input-chancalan | 313.4 ± 2.2 | 310.9 | 317.0 | 342.07 ± 90.92 |
| mikofo | input-kcen | 314.1 ± 1.9 | 311.9 | 316.8 | 342.79 ± 91.10 |
| mikofo | input-pting | 314.1 ± 2.3 | 311.2 | 317.3 | 342.80 ± 91.11 |
| mikofo | input-lanjian | 314.8 ± 1.3 | 312.6 | 317.3 | 343.51 ± 91.28 |
| mikofo | input-mattcl | 314.9 ± 1.9 | 312.2 | 317.7 | 343.65 ± 91.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|