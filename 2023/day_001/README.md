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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.5 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-chancalan | 1.1 ± 0.1 | 0.2 | 1.3 | 1.05 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.4 | 1.6 | 1.07 ± 0.23 |
| lanjian | input-chancalan | 1.9 ± 0.2 | 1.4 | 2.8 | 1.80 ± 0.36 |
| lanjian | input-aspidites | 2.0 ± 0.2 | 1.5 | 2.7 | 1.88 ± 0.39 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.4 | 2.8 | 1.88 ± 0.42 |
| lanjian | input-mattcl | 2.0 ± 0.3 | 1.4 | 2.9 | 1.90 ± 0.41 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.2 | 2.8 | 1.92 ± 0.41 |
| lanjian | input-kcen | 2.1 ± 0.3 | 1.4 | 3.4 | 1.93 ± 0.42 |
| aspidites | input-mattcl | 13.1 ± 0.4 | 11.7 | 14.3 | 12.34 ± 2.22 |
| aspidites | input-chancalan | 13.1 ± 0.4 | 12.3 | 14.2 | 12.36 ± 2.22 |
| aspidites | input-pting | 13.2 ± 0.5 | 11.6 | 14.9 | 12.41 ± 2.25 |
| aspidites | input-kcen | 13.2 ± 0.5 | 12.3 | 14.7 | 12.42 ± 2.24 |
| aspidites | input-aspidites | 13.2 ± 2.0 | 11.4 | 40.8 | 12.44 ± 2.92 |
| aspidites | input-lanjian | 13.2 ± 0.4 | 12.2 | 14.6 | 12.47 ± 2.25 |
| pting | input-pting | 18.0 ± 0.6 | 17.1 | 21.3 | 16.98 ± 3.06 |
| pting | input-mattcl | 18.0 ± 0.6 | 17.1 | 20.7 | 16.99 ± 3.06 |
| pting | input-aspidites | 18.0 ± 0.8 | 16.9 | 21.5 | 16.99 ± 3.10 |
| pting | input-kcen | 18.1 ± 0.6 | 17.2 | 20.8 | 17.02 ± 3.07 |
| pting | input-chancalan | 18.1 ± 0.8 | 16.9 | 21.1 | 17.05 ± 3.11 |
| pting | input-lanjian | 18.1 ± 0.7 | 17.0 | 21.0 | 17.08 ± 3.10 |
| chancalan | input-aspidites | 18.5 ± 0.6 | 17.7 | 22.0 | 17.45 ± 3.15 |
| mattcl-py | input-aspidites | 18.5 ± 0.6 | 17.5 | 21.7 | 17.46 ± 3.14 |
| chancalan | input-kcen | 18.6 ± 0.6 | 17.5 | 22.1 | 17.49 ± 3.15 |
| mattcl-py | input-lanjian | 18.6 ± 0.6 | 17.5 | 21.8 | 17.52 ± 3.16 |
| chancalan | input-lanjian | 18.7 ± 0.7 | 17.7 | 21.2 | 17.58 ± 3.18 |
| chancalan | input-chancalan | 18.7 ± 0.8 | 17.4 | 22.3 | 17.58 ± 3.20 |
| mattcl-py | input-mattcl | 18.7 ± 0.7 | 17.7 | 21.8 | 17.59 ± 3.18 |
| chancalan | input-mattcl | 18.7 ± 0.6 | 17.6 | 21.5 | 17.59 ± 3.17 |
| mattcl-py | input-kcen | 18.7 ± 0.7 | 17.6 | 21.9 | 17.59 ± 3.18 |
| mattcl-py | input-pting | 18.7 ± 0.7 | 17.7 | 22.2 | 17.63 ± 3.20 |
| mattcl-py | input-chancalan | 18.7 ± 0.7 | 17.7 | 21.8 | 17.66 ± 3.20 |
| chancalan | input-pting | 18.8 ± 0.8 | 17.7 | 21.9 | 17.70 ± 3.23 |
| kcen | input-kcen | 18.9 ± 0.5 | 18.2 | 21.5 | 17.76 ± 3.19 |
| kcen | input-aspidites | 18.9 ± 0.8 | 17.9 | 22.2 | 17.79 ± 3.24 |
| kcen | input-chancalan | 18.9 ± 0.7 | 17.8 | 21.8 | 17.79 ± 3.21 |
| kcen | input-mattcl | 18.9 ± 0.7 | 17.7 | 22.0 | 17.81 ± 3.22 |
| kcen | input-pting | 18.9 ± 0.6 | 18.0 | 21.7 | 17.82 ± 3.21 |
| kcen | input-lanjian | 18.9 ± 0.8 | 17.7 | 22.2 | 17.83 ± 3.25 |
| mikofo | input-aspidites | 313.9 ± 1.4 | 312.4 | 315.9 | 295.69 ± 52.39 |
| mikofo | input-pting | 314.6 ± 2.1 | 311.2 | 317.0 | 296.36 ± 52.54 |
| mikofo | input-chancalan | 314.8 ± 1.0 | 312.8 | 316.3 | 296.48 ± 52.53 |
| mikofo | input-mattcl | 315.3 ± 2.2 | 311.5 | 317.4 | 296.95 ± 52.64 |
| mikofo | input-lanjian | 316.1 ± 2.7 | 312.4 | 321.0 | 297.78 ± 52.81 |
| mikofo | input-kcen | 316.8 ± 1.3 | 315.2 | 319.8 | 298.43 ± 52.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|