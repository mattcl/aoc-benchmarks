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
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.34 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.32 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.33 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.31 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.33 |
| lanjian | input-aspidites | 1.0 ± 0.1 | 0.4 | 1.3 | 1.08 ± 0.31 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.6 | 1.6 | 1.09 ± 0.30 |
| mattcl | input-aspidites | 1.0 ± 0.1 | 0.5 | 1.2 | 1.09 ± 0.30 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 10.0 | 12.3 | 12.20 ± 3.10 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 10.0 | 12.0 | 12.20 ± 3.10 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.2 | 11.9 | 12.22 ± 3.09 |
| mattcl-ts | input-aspidites | 11.2 ± 0.4 | 10.0 | 12.4 | 12.24 ± 3.10 |
| mikofo | input-lanjian | 11.3 ± 0.3 | 10.3 | 12.3 | 12.38 ± 3.13 |
| mikofo | input-mattcl | 11.3 ± 0.3 | 10.3 | 12.5 | 12.40 ± 3.14 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.3 | 12.3 | 12.42 ± 3.14 |
| mattcl-ts | input-lanjian | 11.4 ± 2.7 | 9.8 | 48.5 | 12.48 ± 4.28 |
| mikofo | input-chancalan | 11.4 ± 0.4 | 10.5 | 12.6 | 12.48 ± 3.16 |
| mikofo | input-kcen | 11.4 ± 0.3 | 10.1 | 13.0 | 12.48 ± 3.16 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.5 | 14.2 | 13.86 ± 3.52 |
| aspidites | input-aspidites | 12.8 ± 3.6 | 11.2 | 62.1 | 14.02 ± 5.27 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 11.7 | 14.4 | 14.08 ± 3.58 |
| aspidites | input-mattcl | 12.9 ± 0.5 | 11.7 | 14.4 | 14.11 ± 3.58 |
| aspidites | input-lanjian | 12.9 ± 0.5 | 11.6 | 14.7 | 14.13 ± 3.59 |
| pting | input-chancalan | 14.5 ± 0.5 | 13.6 | 17.3 | 15.91 ± 4.03 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.8 | 18.4 | 15.96 ± 4.07 |
| pting | input-kcen | 14.6 ± 0.6 | 13.4 | 17.7 | 16.00 ± 4.08 |
| pting | input-aspidites | 14.6 ± 0.6 | 13.6 | 17.5 | 16.01 ± 4.08 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.6 | 17.9 | 16.02 ± 4.07 |
| mattcl-py | input-kcen | 14.6 ± 0.6 | 13.8 | 18.4 | 16.03 ± 4.09 |
| mattcl-py | input-aspidites | 14.7 ± 0.6 | 13.7 | 17.5 | 16.06 ± 4.08 |
| pting | input-mattcl | 14.7 ± 0.6 | 13.6 | 18.3 | 16.07 ± 4.09 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.5 | 18.1 | 16.08 ± 4.08 |
| mattcl-py | input-mattcl | 15.1 ± 4.5 | 13.3 | 67.3 | 16.52 ± 6.40 |
| chancalan | input-lanjian | 15.1 ± 0.5 | 14.3 | 17.8 | 16.56 ± 4.20 |
| chancalan | input-aspidites | 15.1 ± 0.5 | 14.1 | 17.7 | 16.58 ± 4.20 |
| chancalan | input-chancalan | 15.2 ± 0.7 | 13.9 | 18.2 | 16.59 ± 4.23 |
| chancalan | input-mattcl | 15.2 ± 0.7 | 13.9 | 19.5 | 16.63 ± 4.24 |
| chancalan | input-kcen | 15.3 ± 0.8 | 14.3 | 18.2 | 16.73 ± 4.28 |
| kcen | input-chancalan | 15.3 ± 0.5 | 14.1 | 18.2 | 16.80 ± 4.26 |
| kcen | input-lanjian | 15.4 ± 0.7 | 14.1 | 18.6 | 16.88 ± 4.30 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.5 | 18.6 | 16.90 ± 4.29 |
| kcen | input-mattcl | 15.6 ± 0.7 | 14.4 | 18.4 | 17.05 ± 4.34 |
| kcen | input-aspidites | 15.7 ± 3.0 | 14.3 | 55.3 | 17.22 ± 5.41 |


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