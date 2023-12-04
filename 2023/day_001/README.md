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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 ± 0.29 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.27 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.4 | 1.5 | 1.01 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.28 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.5 | 3.0 | 1.93 ± 0.46 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.3 | 3.6 | 1.95 ± 0.49 |
| lanjian | input-chancalan | 1.9 ± 0.3 | 1.3 | 3.2 | 1.98 ± 0.49 |
| lanjian | input-mattcl | 1.9 ± 0.3 | 1.3 | 3.2 | 2.03 ± 0.52 |
| lanjian | input-pting | 2.0 ± 0.3 | 1.6 | 3.0 | 2.04 ± 0.52 |
| lanjian | input-aspidites | 2.0 ± 0.3 | 1.2 | 3.0 | 2.04 ± 0.52 |
| aspidites | input-lanjian | 13.0 ± 0.4 | 11.8 | 14.2 | 13.55 ± 2.84 |
| aspidites | input-kcen | 13.0 ± 0.5 | 11.6 | 14.3 | 13.62 ± 2.86 |
| aspidites | input-chancalan | 13.1 ± 0.5 | 11.9 | 14.5 | 13.63 ± 2.86 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.1 | 14.5 | 13.65 ± 2.87 |
| aspidites | input-pting | 13.1 ± 0.4 | 12.2 | 14.6 | 13.67 ± 2.86 |
| aspidites | input-mattcl | 13.2 ± 2.1 | 11.1 | 41.5 | 13.75 ± 3.58 |
| pting | input-mattcl | 17.9 ± 0.6 | 17.0 | 21.0 | 18.67 ± 3.91 |
| pting | input-pting | 17.9 ± 0.6 | 17.0 | 21.5 | 18.70 ± 3.93 |
| pting | input-aspidites | 18.0 ± 0.7 | 17.0 | 20.9 | 18.77 ± 3.96 |
| pting | input-lanjian | 18.0 ± 0.7 | 17.1 | 20.8 | 18.77 ± 3.96 |
| pting | input-chancalan | 18.0 ± 0.7 | 16.8 | 21.1 | 18.79 ± 3.96 |
| pting | input-kcen | 18.0 ± 0.6 | 16.7 | 20.9 | 18.80 ± 3.95 |
| mattcl-py | input-lanjian | 18.5 ± 0.6 | 17.4 | 21.3 | 19.32 ± 4.06 |
| chancalan | input-chancalan | 18.5 ± 0.6 | 17.6 | 21.9 | 19.34 ± 4.05 |
| mattcl-py | input-chancalan | 18.5 ± 0.5 | 17.5 | 21.1 | 19.35 ± 4.05 |
| mattcl-py | input-mattcl | 18.5 ± 0.6 | 17.5 | 21.3 | 19.35 ± 4.06 |
| chancalan | input-aspidites | 18.5 ± 0.6 | 17.7 | 21.8 | 19.35 ± 4.06 |
| chancalan | input-kcen | 18.5 ± 0.6 | 17.3 | 21.6 | 19.36 ± 4.06 |
| chancalan | input-lanjian | 18.5 ± 0.6 | 17.4 | 21.6 | 19.36 ± 4.07 |
| mattcl-py | input-kcen | 18.6 ± 0.6 | 17.6 | 21.5 | 19.40 ± 4.06 |
| mattcl-py | input-aspidites | 18.6 ± 0.7 | 17.5 | 21.9 | 19.40 ± 4.08 |
| chancalan | input-mattcl | 18.6 ± 0.8 | 17.3 | 21.7 | 19.46 ± 4.11 |
| chancalan | input-pting | 18.7 ± 0.7 | 17.4 | 21.5 | 19.49 ± 4.10 |
| mattcl-py | input-pting | 18.7 ± 0.8 | 17.7 | 21.7 | 19.53 ± 4.13 |
| kcen | input-chancalan | 18.7 ± 0.5 | 17.9 | 21.2 | 19.55 ± 4.08 |
| kcen | input-aspidites | 18.7 ± 0.6 | 17.7 | 21.2 | 19.58 ± 4.10 |
| kcen | input-mattcl | 18.8 ± 0.7 | 17.9 | 21.8 | 19.65 ± 4.14 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.8 | 21.7 | 19.67 ± 4.13 |
| kcen | input-pting | 18.9 ± 0.7 | 17.7 | 22.1 | 19.73 ± 4.16 |
| kcen | input-lanjian | 19.2 ± 4.6 | 18.0 | 75.7 | 20.06 ± 6.38 |
| mikofo | input-kcen | 315.0 ± 1.5 | 312.1 | 316.9 | 329.00 ± 68.17 |
| mikofo | input-chancalan | 315.6 ± 1.3 | 313.9 | 317.1 | 329.57 ± 68.29 |
| mikofo | input-lanjian | 315.6 ± 0.8 | 314.8 | 317.2 | 329.58 ± 68.28 |
| mikofo | input-aspidites | 315.8 ± 1.2 | 313.2 | 317.3 | 329.79 ± 68.33 |
| mikofo | input-pting | 316.2 ± 2.1 | 312.6 | 319.5 | 330.26 ± 68.45 |
| mikofo | input-mattcl | 316.7 ± 1.5 | 314.4 | 318.7 | 330.78 ± 68.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|