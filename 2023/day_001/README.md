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
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.5 | 1.3 | 1.03 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.5 | 1.5 | 1.05 ± 0.26 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.4 | 1.5 | 1.07 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.1 | 0.6 | 1.2 | 1.07 ± 0.25 |
| lanjian | input-chancalan | 1.9 ± 0.2 | 1.3 | 2.8 | 1.90 ± 0.43 |
| lanjian | input-aspidites | 1.9 ± 0.2 | 1.1 | 2.7 | 1.91 ± 0.42 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.5 | 2.7 | 1.95 ± 0.46 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.7 | 2.8 | 1.95 ± 0.46 |
| lanjian | input-pting | 2.0 ± 0.3 | 1.5 | 3.4 | 1.96 ± 0.48 |
| lanjian | input-kcen | 2.0 ± 0.2 | 1.5 | 3.1 | 1.97 ± 0.46 |
| aspidites | input-chancalan | 13.0 ± 0.5 | 11.7 | 14.5 | 13.07 ± 2.70 |
| aspidites | input-pting | 13.0 ± 0.4 | 12.2 | 14.8 | 13.09 ± 2.69 |
| aspidites | input-lanjian | 13.0 ± 0.5 | 12.0 | 15.2 | 13.11 ± 2.70 |
| aspidites | input-kcen | 13.1 ± 0.4 | 12.1 | 14.8 | 13.18 ± 2.71 |
| aspidites | input-aspidites | 13.1 ± 0.4 | 12.2 | 14.7 | 13.20 ± 2.71 |
| aspidites | input-mattcl | 13.2 ± 0.5 | 11.8 | 14.6 | 13.24 ± 2.72 |
| pting | input-chancalan | 17.8 ± 0.5 | 16.8 | 20.8 | 17.95 ± 3.67 |
| pting | input-lanjian | 17.9 ± 0.7 | 16.9 | 21.3 | 18.04 ± 3.72 |
| pting | input-mattcl | 18.0 ± 0.8 | 16.9 | 21.1 | 18.08 ± 3.75 |
| pting | input-kcen | 18.0 ± 0.7 | 17.0 | 21.0 | 18.09 ± 3.73 |
| pting | input-aspidites | 18.0 ± 2.1 | 17.0 | 43.5 | 18.13 ± 4.24 |
| pting | input-pting | 18.1 ± 0.8 | 17.2 | 21.1 | 18.16 ± 3.76 |
| mattcl-py | input-aspidites | 18.4 ± 0.5 | 17.5 | 21.1 | 18.51 ± 3.78 |
| chancalan | input-chancalan | 18.4 ± 0.7 | 17.3 | 21.3 | 18.53 ± 3.82 |
| chancalan | input-lanjian | 18.5 ± 0.7 | 17.5 | 22.2 | 18.60 ± 3.83 |
| mattcl-py | input-pting | 18.5 ± 0.7 | 17.4 | 22.3 | 18.64 ± 3.84 |
| mattcl-py | input-chancalan | 18.5 ± 0.6 | 17.6 | 21.8 | 18.65 ± 3.83 |
| mattcl-py | input-lanjian | 18.6 ± 0.7 | 17.7 | 21.5 | 18.66 ± 3.85 |
| chancalan | input-aspidites | 18.6 ± 0.7 | 17.8 | 21.5 | 18.67 ± 3.85 |
| chancalan | input-mattcl | 18.6 ± 0.7 | 17.5 | 21.4 | 18.71 ± 3.86 |
| chancalan | input-kcen | 18.6 ± 0.8 | 17.2 | 21.6 | 18.72 ± 3.87 |
| chancalan | input-pting | 18.7 ± 0.8 | 17.6 | 21.5 | 18.78 ± 3.89 |
| mattcl-py | input-kcen | 18.8 ± 1.4 | 17.6 | 33.6 | 18.87 ± 4.06 |
| kcen | input-aspidites | 18.8 ± 0.6 | 17.9 | 21.6 | 18.87 ± 3.87 |
| mattcl-py | input-mattcl | 18.8 ± 1.8 | 17.6 | 39.9 | 18.88 ± 4.24 |
| kcen | input-chancalan | 18.8 ± 0.8 | 17.8 | 22.0 | 18.94 ± 3.92 |
| kcen | input-lanjian | 18.8 ± 0.7 | 17.7 | 21.5 | 18.94 ± 3.91 |
| kcen | input-kcen | 18.8 ± 0.6 | 18.1 | 21.4 | 18.94 ± 3.89 |
| kcen | input-mattcl | 18.9 ± 0.7 | 18.1 | 22.0 | 18.97 ± 3.90 |
| kcen | input-pting | 18.9 ± 0.8 | 18.0 | 22.0 | 19.04 ± 3.94 |
| mikofo | input-aspidites | 310.8 ± 1.4 | 308.2 | 312.1 | 312.54 ± 63.35 |
| mikofo | input-lanjian | 312.2 ± 2.2 | 309.0 | 315.4 | 313.86 ± 63.64 |
| mikofo | input-chancalan | 312.7 ± 1.9 | 310.0 | 315.2 | 314.45 ± 63.75 |
| mikofo | input-kcen | 313.2 ± 1.8 | 310.7 | 315.7 | 314.88 ± 63.84 |
| mikofo | input-mattcl | 314.4 ± 1.5 | 312.5 | 316.7 | 316.16 ± 64.09 |
| mikofo | input-pting | 314.5 ± 1.2 | 312.5 | 315.9 | 316.26 ± 64.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|