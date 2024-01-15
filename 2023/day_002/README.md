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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.6 | 1.01 ± 0.35 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.1 | 1.05 ± 0.29 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.05 ± 0.29 |
| mattcl | input-aspidites | 0.9 ± 0.1 | 0.4 | 1.4 | 1.07 ± 0.29 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.09 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.5 | 1.1 | 1.09 ± 0.29 |
| lanjian | input-aspidites | 0.9 ± 0.1 | 0.5 | 1.1 | 1.09 ± 0.28 |
| mikofo | input-kcen | 10.2 ± 0.4 | 9.3 | 11.2 | 12.14 ± 2.76 |
| mattcl-ts | input-chancalan | 10.2 ± 0.4 | 9.3 | 11.2 | 12.15 ± 2.76 |
| mattcl-ts | input-aspidites | 10.2 ± 0.4 | 9.0 | 11.7 | 12.16 ± 2.77 |
| mattcl-ts | input-kcen | 10.2 ± 0.4 | 9.3 | 11.1 | 12.17 ± 2.77 |
| mattcl-ts | input-mattcl | 10.2 ± 0.4 | 9.0 | 11.5 | 12.17 ± 2.76 |
| mikofo | input-aspidites | 10.2 ± 0.4 | 9.3 | 11.7 | 12.18 ± 2.76 |
| mikofo | input-lanjian | 10.2 ± 0.4 | 9.3 | 11.1 | 12.18 ± 2.76 |
| mikofo | input-mattcl | 10.3 ± 0.4 | 9.3 | 11.7 | 12.21 ± 2.77 |
| mattcl-ts | input-lanjian | 10.3 ± 0.4 | 9.2 | 11.2 | 12.24 ± 2.77 |
| mikofo | input-chancalan | 10.3 ± 0.4 | 9.3 | 11.4 | 12.27 ± 2.78 |
| aspidites | input-chancalan | 12.5 ± 0.4 | 11.6 | 13.7 | 14.81 ± 3.34 |
| aspidites | input-mattcl | 12.5 ± 0.4 | 11.3 | 14.1 | 14.88 ± 3.37 |
| aspidites | input-kcen | 12.5 ± 0.4 | 11.3 | 13.8 | 14.88 ± 3.37 |
| aspidites | input-lanjian | 12.6 ± 0.4 | 11.6 | 13.9 | 14.94 ± 3.39 |
| aspidites | input-aspidites | 12.6 ± 0.5 | 11.5 | 15.4 | 14.97 ± 3.40 |
| pting | input-kcen | 14.2 ± 0.4 | 13.4 | 16.5 | 16.85 ± 3.80 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.4 | 16.90 ± 3.85 |
| pting | input-aspidites | 14.2 ± 0.5 | 13.5 | 17.2 | 16.92 ± 3.84 |
| pting | input-chancalan | 14.3 ± 0.7 | 13.3 | 17.2 | 16.96 ± 3.89 |
| mattcl-py | input-mattcl | 14.3 ± 0.6 | 13.4 | 18.1 | 16.97 ± 3.87 |
| mattcl-py | input-aspidites | 14.3 ± 0.5 | 13.4 | 17.1 | 17.01 ± 3.86 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.3 | 17.5 | 17.01 ± 3.87 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.3 | 17.7 | 17.04 ± 3.91 |
| mattcl-py | input-chancalan | 14.4 ± 0.7 | 13.3 | 17.3 | 17.06 ± 3.90 |
| mattcl-py | input-kcen | 14.4 ± 0.7 | 13.2 | 18.1 | 17.07 ± 3.92 |
| chancalan | input-aspidites | 14.9 ± 0.7 | 13.9 | 17.7 | 17.71 ± 4.04 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.1 | 17.72 ± 4.04 |
| chancalan | input-kcen | 14.9 ± 0.6 | 13.9 | 17.5 | 17.74 ± 4.03 |
| chancalan | input-chancalan | 14.9 ± 0.7 | 13.8 | 18.3 | 17.75 ± 4.05 |
| chancalan | input-lanjian | 15.0 ± 0.7 | 14.0 | 18.1 | 17.81 ± 4.06 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.1 | 18.2 | 17.97 ± 4.07 |
| kcen | input-chancalan | 15.1 ± 0.6 | 14.1 | 18.2 | 18.00 ± 4.09 |
| kcen | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.2 | 18.02 ± 4.10 |
| kcen | input-lanjian | 15.2 ± 0.7 | 14.0 | 18.2 | 18.08 ± 4.12 |
| kcen | input-aspidites | 15.2 ± 0.7 | 14.1 | 18.2 | 18.12 ± 4.13 |


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