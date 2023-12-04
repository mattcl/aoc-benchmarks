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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.29 |
| mattcl | input-aspidites | 1.0 ± 0.1 | 0.5 | 1.2 | 1.06 ± 0.26 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.6 | 1.10 ± 0.28 |
| lanjian | input-chancalan | 1.9 ± 0.2 | 1.3 | 2.7 | 1.99 ± 0.48 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.4 | 2.7 | 2.01 ± 0.51 |
| lanjian | input-mattcl | 2.0 ± 0.3 | 1.2 | 3.2 | 2.02 ± 0.53 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.2 | 3.0 | 2.02 ± 0.51 |
| lanjian | input-pting | 2.0 ± 0.3 | 1.4 | 3.0 | 2.04 ± 0.51 |
| lanjian | input-aspidites | 2.0 ± 0.3 | 1.4 | 3.5 | 2.05 ± 0.54 |
| aspidites | input-chancalan | 13.0 ± 0.5 | 12.1 | 14.4 | 13.46 ± 2.88 |
| aspidites | input-lanjian | 13.1 ± 0.4 | 12.1 | 14.2 | 13.50 ± 2.88 |
| aspidites | input-mattcl | 13.1 ± 0.4 | 11.9 | 14.5 | 13.53 ± 2.88 |
| aspidites | input-kcen | 13.1 ± 0.5 | 12.0 | 14.6 | 13.58 ± 2.90 |
| aspidites | input-pting | 13.2 ± 0.5 | 12.2 | 14.8 | 13.61 ± 2.90 |
| aspidites | input-aspidites | 13.2 ± 0.4 | 12.3 | 14.6 | 13.63 ± 2.91 |
| pting | input-pting | 18.0 ± 0.5 | 17.1 | 20.9 | 18.57 ± 3.95 |
| pting | input-aspidites | 18.0 ± 0.8 | 16.9 | 21.3 | 18.63 ± 4.01 |
| pting | input-chancalan | 18.1 ± 0.7 | 17.0 | 20.8 | 18.67 ± 3.99 |
| pting | input-lanjian | 18.1 ± 0.8 | 17.0 | 21.3 | 18.67 ± 4.01 |
| pting | input-kcen | 18.1 ± 0.8 | 17.3 | 21.3 | 18.74 ± 4.04 |
| pting | input-mattcl | 18.2 ± 0.8 | 17.1 | 21.3 | 18.76 ± 4.03 |
| chancalan | input-chancalan | 18.4 ± 0.5 | 17.4 | 20.8 | 19.06 ± 4.04 |
| chancalan | input-lanjian | 18.5 ± 0.7 | 17.6 | 21.4 | 19.16 ± 4.10 |
| mattcl-py | input-aspidites | 18.5 ± 0.8 | 17.4 | 21.6 | 19.17 ± 4.11 |
| chancalan | input-kcen | 18.5 ± 0.6 | 17.3 | 22.1 | 19.17 ± 4.09 |
| chancalan | input-mattcl | 18.6 ± 0.7 | 17.6 | 21.9 | 19.20 ± 4.10 |
| mattcl-py | input-mattcl | 18.6 ± 0.6 | 17.7 | 21.3 | 19.23 ± 4.09 |
| mattcl-py | input-pting | 18.6 ± 0.5 | 17.5 | 21.2 | 19.23 ± 4.09 |
| mattcl-py | input-lanjian | 18.6 ± 0.8 | 17.3 | 21.9 | 19.24 ± 4.13 |
| mattcl-py | input-kcen | 18.6 ± 0.6 | 17.9 | 21.4 | 19.24 ± 4.11 |
| chancalan | input-pting | 18.6 ± 0.7 | 17.7 | 21.5 | 19.26 ± 4.13 |
| chancalan | input-aspidites | 18.7 ± 0.9 | 17.6 | 22.1 | 19.29 ± 4.16 |
| mattcl-py | input-chancalan | 18.7 ± 0.8 | 17.6 | 21.9 | 19.36 ± 4.17 |
| kcen | input-aspidites | 18.7 ± 0.6 | 17.8 | 21.7 | 19.37 ± 4.13 |
| kcen | input-chancalan | 18.8 ± 0.5 | 17.7 | 21.4 | 19.38 ± 4.12 |
| kcen | input-lanjian | 18.8 ± 0.5 | 17.9 | 21.3 | 19.41 ± 4.12 |
| kcen | input-pting | 18.8 ± 0.5 | 17.7 | 21.3 | 19.42 ± 4.13 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.9 | 22.0 | 19.47 ± 4.16 |
| kcen | input-mattcl | 18.9 ± 0.8 | 17.7 | 21.9 | 19.52 ± 4.19 |
| mikofo | input-aspidites | 313.4 ± 1.6 | 311.3 | 315.9 | 323.91 ± 68.24 |
| mikofo | input-chancalan | 314.1 ± 1.6 | 310.5 | 316.6 | 324.65 ± 68.40 |
| mikofo | input-lanjian | 314.7 ± 1.6 | 312.5 | 316.8 | 325.26 ± 68.53 |
| mikofo | input-mattcl | 314.7 ± 1.8 | 310.9 | 316.8 | 325.30 ± 68.54 |
| mikofo | input-pting | 315.6 ± 1.5 | 313.4 | 318.4 | 326.24 ± 68.73 |
| mikofo | input-kcen | 320.5 ± 14.2 | 314.3 | 358.1 | 331.31 ± 71.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|