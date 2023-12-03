# Day 2 benchmarks

[link to problem](https://adventofcode.com/2023/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.3 | 1.0 | 1.04 ± 0.30 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.1 | 1.0 | 1.04 ± 0.31 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.2 | 1.1 | 1.05 ± 0.30 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.3 | 1.05 ± 0.31 |
| mattcl | input-aspidites | 0.8 ± 0.1 | 0.0 | 1.0 | 1.07 ± 0.30 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.4 | 1.07 ± 0.36 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.5 | 1.08 ± 0.36 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.09 ± 0.34 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.11 ± 0.33 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.3 | 1.4 | 1.11 ± 0.33 |
| lanjian | input-aspidites | 0.9 ± 0.1 | 0.5 | 1.0 | 1.14 ± 0.30 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 11.7 | 14.9 | 16.96 ± 3.96 |
| aspidites | input-mattcl | 13.0 ± 0.4 | 11.7 | 14.1 | 17.02 ± 3.96 |
| aspidites | input-lanjian | 13.0 ± 0.5 | 12.0 | 14.4 | 17.06 ± 3.98 |
| aspidites | input-aspidites | 13.0 ± 0.5 | 12.0 | 14.3 | 17.06 ± 3.98 |
| aspidites | input-kcen | 13.1 ± 0.4 | 12.1 | 14.6 | 17.16 ± 3.99 |
| aspidites | input-pting | 13.1 ± 0.5 | 12.0 | 14.6 | 17.18 ± 4.01 |
| pting | input-lanjian | 16.3 ± 0.6 | 15.3 | 19.4 | 21.43 ± 4.99 |
| pting | input-aspidites | 16.3 ± 0.6 | 15.2 | 19.1 | 21.44 ± 5.00 |
| pting | input-chancalan | 16.4 ± 0.7 | 15.4 | 19.7 | 21.49 ± 5.04 |
| mattcl-py | input-mattcl | 16.4 ± 0.6 | 15.5 | 19.6 | 21.51 ± 5.02 |
| mattcl-py | input-aspidites | 16.4 ± 0.6 | 15.3 | 19.3 | 21.51 ± 5.02 |
| pting | input-kcen | 16.4 ± 1.2 | 15.2 | 30.2 | 21.54 ± 5.20 |
| mattcl-py | input-chancalan | 16.4 ± 0.7 | 15.5 | 19.7 | 21.59 ± 5.06 |
| pting | input-mattcl | 16.4 ± 0.8 | 15.5 | 19.3 | 21.61 ± 5.09 |
| mattcl-py | input-kcen | 16.5 ± 0.7 | 15.3 | 19.9 | 21.63 ± 5.07 |
| mattcl-py | input-pting | 16.5 ± 0.7 | 15.4 | 20.9 | 21.65 ± 5.07 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.3 | 19.0 | 21.66 ± 5.07 |
| pting | input-pting | 16.5 ± 0.7 | 15.4 | 19.5 | 21.67 ± 5.09 |
| chancalan | input-lanjian | 17.1 ± 0.5 | 16.2 | 20.1 | 22.44 ± 5.22 |
| chancalan | input-chancalan | 17.1 ± 0.7 | 16.1 | 20.5 | 22.47 ± 5.25 |
| chancalan | input-pting | 17.2 ± 0.6 | 16.1 | 19.7 | 22.61 ± 5.27 |
| chancalan | input-aspidites | 17.2 ± 0.6 | 16.2 | 19.7 | 22.63 ± 5.27 |
| chancalan | input-kcen | 17.3 ± 0.7 | 16.1 | 20.7 | 22.67 ± 5.31 |
| chancalan | input-mattcl | 17.5 ± 3.2 | 16.2 | 56.8 | 22.96 ± 6.73 |
| kcen | input-kcen | 17.5 ± 0.6 | 16.7 | 20.6 | 22.99 ± 5.35 |
| kcen | input-aspidites | 17.6 ± 0.6 | 16.8 | 20.5 | 23.07 ± 5.37 |
| kcen | input-lanjian | 17.6 ± 0.7 | 16.6 | 21.0 | 23.08 ± 5.39 |
| kcen | input-chancalan | 17.6 ± 0.7 | 16.8 | 20.4 | 23.14 ± 5.40 |
| kcen | input-pting | 17.6 ± 0.7 | 16.7 | 21.1 | 23.15 ± 5.41 |
| kcen | input-mattcl | 17.6 ± 0.7 | 17.0 | 20.7 | 23.15 ± 5.40 |
| mikofo | input-aspidites | 314.0 ± 1.8 | 311.3 | 316.8 | 412.56 ± 95.08 |
| mikofo | input-kcen | 314.3 ± 1.6 | 311.5 | 317.0 | 413.03 ± 95.18 |
| mikofo | input-lanjian | 314.6 ± 2.3 | 311.0 | 319.7 | 413.39 ± 95.29 |
| mikofo | input-chancalan | 315.1 ± 1.9 | 311.4 | 318.5 | 413.97 ± 95.41 |
| mikofo | input-pting | 315.2 ± 2.0 | 312.7 | 318.4 | 414.14 ± 95.45 |
| mikofo | input-mattcl | 315.6 ± 1.6 | 313.2 | 318.6 | 414.63 ± 95.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|