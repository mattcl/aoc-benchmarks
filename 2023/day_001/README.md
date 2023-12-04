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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.4 | 1.03 ± 0.25 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.3 | 1.2 | 1.03 ± 0.23 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.25 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 1.6 | 2.7 | 1.92 ± 0.38 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.0 | 2.6 | 1.94 ± 0.42 |
| lanjian | input-kcen | 1.9 ± 0.2 | 1.3 | 2.7 | 1.97 ± 0.42 |
| lanjian | input-aspidites | 1.9 ± 0.3 | 1.2 | 3.1 | 1.98 ± 0.45 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.3 | 2.6 | 2.00 ± 0.43 |
| lanjian | input-pting | 1.9 ± 0.3 | 1.2 | 3.0 | 2.04 ± 0.47 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.3 | 14.8 | 13.60 ± 2.52 |
| aspidites | input-aspidites | 13.0 ± 0.4 | 12.0 | 14.8 | 13.78 ± 2.53 |
| aspidites | input-mattcl | 13.0 ± 0.4 | 12.1 | 14.1 | 13.83 ± 2.53 |
| aspidites | input-chancalan | 13.1 ± 0.5 | 11.9 | 14.6 | 13.84 ± 2.55 |
| aspidites | input-lanjian | 13.1 ± 0.4 | 12.1 | 14.7 | 13.85 ± 2.54 |
| aspidites | input-pting | 13.1 ± 0.4 | 12.1 | 14.3 | 13.85 ± 2.54 |
| pting | input-kcen | 17.9 ± 0.6 | 17.1 | 21.6 | 18.94 ± 3.49 |
| pting | input-chancalan | 17.9 ± 0.7 | 16.9 | 21.2 | 18.95 ± 3.51 |
| pting | input-aspidites | 17.9 ± 0.7 | 17.1 | 21.5 | 18.97 ± 3.50 |
| pting | input-mattcl | 17.9 ± 0.7 | 17.0 | 21.3 | 19.00 ± 3.52 |
| pting | input-pting | 18.0 ± 0.7 | 16.7 | 20.6 | 19.05 ± 3.53 |
| pting | input-lanjian | 18.2 ± 2.6 | 16.9 | 50.5 | 19.33 ± 4.48 |
| chancalan | input-kcen | 18.4 ± 0.6 | 17.2 | 21.6 | 19.52 ± 3.58 |
| chancalan | input-lanjian | 18.5 ± 0.7 | 17.2 | 21.9 | 19.57 ± 3.62 |
| chancalan | input-aspidites | 18.5 ± 0.6 | 17.4 | 21.8 | 19.58 ± 3.60 |
| mattcl-py | input-kcen | 18.5 ± 0.6 | 17.6 | 21.8 | 19.58 ± 3.60 |
| mattcl-py | input-aspidites | 18.5 ± 0.6 | 17.5 | 21.1 | 19.65 ± 3.62 |
| chancalan | input-mattcl | 18.6 ± 0.8 | 17.3 | 22.0 | 19.68 ± 3.65 |
| mattcl-py | input-lanjian | 18.6 ± 0.7 | 17.3 | 21.3 | 19.68 ± 3.65 |
| chancalan | input-chancalan | 18.6 ± 0.9 | 17.4 | 21.5 | 19.73 ± 3.69 |
| mattcl-py | input-pting | 18.6 ± 0.7 | 17.5 | 21.4 | 19.73 ± 3.65 |
| mattcl-py | input-mattcl | 18.6 ± 0.9 | 17.7 | 22.4 | 19.74 ± 3.69 |
| kcen | input-kcen | 18.7 ± 0.7 | 17.7 | 22.1 | 19.83 ± 3.65 |
| chancalan | input-pting | 18.7 ± 1.6 | 17.6 | 35.4 | 19.84 ± 3.95 |
| kcen | input-aspidites | 18.7 ± 0.7 | 17.5 | 22.2 | 19.84 ± 3.67 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.9 | 21.6 | 19.84 ± 3.64 |
| kcen | input-chancalan | 18.7 ± 0.6 | 17.8 | 21.4 | 19.86 ± 3.65 |
| kcen | input-mattcl | 18.9 ± 0.8 | 17.8 | 21.8 | 20.00 ± 3.70 |
| kcen | input-pting | 18.9 ± 0.8 | 17.6 | 22.1 | 20.00 ± 3.71 |
| mattcl-py | input-chancalan | 18.9 ± 4.6 | 17.4 | 75.4 | 20.02 ± 6.04 |
| mikofo | input-aspidites | 311.9 ± 2.2 | 308.4 | 316.1 | 330.73 ± 59.85 |
| mikofo | input-chancalan | 313.1 ± 1.7 | 311.2 | 315.7 | 332.09 ± 60.07 |
| mikofo | input-kcen | 313.2 ± 2.4 | 309.6 | 315.6 | 332.17 ± 60.11 |
| mikofo | input-pting | 314.1 ± 1.4 | 312.2 | 316.3 | 333.09 ± 60.25 |
| mikofo | input-lanjian | 314.2 ± 2.1 | 311.2 | 318.9 | 333.24 ± 60.30 |
| mikofo | input-mattcl | 314.2 ± 2.0 | 310.5 | 318.1 | 333.26 ± 60.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|