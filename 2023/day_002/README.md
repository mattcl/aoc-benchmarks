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
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.5 | 1.05 ± 0.30 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.2 | 1.05 ± 0.29 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.4 | 1.3 | 1.06 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.2 | 1.06 ± 0.28 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.2 | 1.07 ± 0.28 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.29 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.3 | 1.3 | 1.07 ± 0.28 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.2 | 1.08 ± 0.27 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.08 ± 0.29 |
| mattcl-ts | input-lanjian | 11.3 ± 0.4 | 10.2 | 12.1 | 11.45 ± 2.54 |
| mattcl-ts | input-kcen | 11.3 ± 0.4 | 10.1 | 12.2 | 11.47 ± 2.55 |
| mattcl-ts | input-aspidites | 11.3 ± 0.4 | 10.0 | 12.2 | 11.50 ± 2.55 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.1 | 12.2 | 11.51 ± 2.55 |
| mattcl-ts | input-chancalan | 11.4 ± 0.4 | 10.2 | 12.6 | 11.60 ± 2.57 |
| mikofo | input-mattcl | 11.5 ± 0.3 | 10.6 | 12.5 | 11.68 ± 2.58 |
| mikofo | input-kcen | 11.5 ± 0.3 | 10.6 | 12.5 | 11.69 ± 2.58 |
| mikofo | input-lanjian | 11.5 ± 0.3 | 10.3 | 12.9 | 11.70 ± 2.59 |
| mikofo | input-aspidites | 11.5 ± 0.3 | 10.7 | 12.7 | 11.74 ± 2.60 |
| mikofo | input-chancalan | 11.5 ± 0.3 | 10.6 | 12.9 | 11.75 ± 2.60 |
| aspidites | input-lanjian | 12.3 ± 2.5 | 10.9 | 46.7 | 12.50 ± 3.77 |
| aspidites | input-aspidites | 12.7 ± 0.6 | 11.2 | 14.4 | 12.93 ± 2.90 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.7 | 14.2 | 13.08 ± 2.92 |
| aspidites | input-mattcl | 12.9 ± 0.5 | 11.8 | 14.4 | 13.13 ± 2.93 |
| aspidites | input-chancalan | 13.0 ± 0.5 | 11.8 | 15.0 | 13.18 ± 2.94 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.7 | 18.9 | 14.96 ± 3.34 |
| pting | input-chancalan | 14.8 ± 0.7 | 13.9 | 17.9 | 15.01 ± 3.37 |
| pting | input-mattcl | 14.8 ± 0.7 | 13.7 | 18.2 | 15.01 ± 3.37 |
| pting | input-aspidites | 14.8 ± 0.6 | 13.7 | 17.4 | 15.02 ± 3.35 |
| mattcl-py | input-kcen | 14.8 ± 0.7 | 13.6 | 18.3 | 15.04 ± 3.37 |
| pting | input-lanjian | 14.8 ± 0.7 | 13.6 | 18.4 | 15.05 ± 3.39 |
| mattcl-py | input-aspidites | 14.8 ± 0.6 | 13.6 | 18.5 | 15.07 ± 3.37 |
| pting | input-kcen | 14.8 ± 0.7 | 13.5 | 18.0 | 15.09 ± 3.39 |
| mattcl-py | input-chancalan | 14.9 ± 0.6 | 13.8 | 17.5 | 15.11 ± 3.37 |
| mattcl-py | input-mattcl | 14.9 ± 0.7 | 13.6 | 18.0 | 15.13 ± 3.39 |
| chancalan | input-mattcl | 15.3 ± 0.6 | 14.2 | 17.9 | 15.53 ± 3.46 |
| chancalan | input-kcen | 15.3 ± 0.7 | 14.2 | 18.9 | 15.56 ± 3.50 |
| chancalan | input-aspidites | 15.3 ± 0.6 | 14.2 | 18.1 | 15.57 ± 3.48 |
| chancalan | input-chancalan | 15.3 ± 0.6 | 14.2 | 18.2 | 15.59 ± 3.48 |
| kcen | input-lanjian | 15.5 ± 0.7 | 14.3 | 18.5 | 15.80 ± 3.53 |
| kcen | input-chancalan | 15.6 ± 0.7 | 14.5 | 18.6 | 15.86 ± 3.55 |
| kcen | input-kcen | 15.6 ± 0.7 | 14.3 | 18.5 | 15.91 ± 3.56 |
| kcen | input-mattcl | 15.6 ± 0.6 | 14.8 | 18.6 | 15.91 ± 3.55 |
| kcen | input-aspidites | 15.7 ± 0.7 | 14.3 | 19.1 | 15.96 ± 3.57 |
| chancalan | input-lanjian | 15.8 ± 4.7 | 14.1 | 57.0 | 16.11 ± 5.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-mikofo|<pre>2162</pre>|<pre>72513</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|