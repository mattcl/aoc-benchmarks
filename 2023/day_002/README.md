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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.0 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.04 ± 0.37 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.2 | 1.0 | 1.04 ± 0.36 |
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.37 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.36 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.3 | 1.07 ± 0.38 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.37 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.10 ± 0.38 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.6 | 1.12 ± 0.38 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.13 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.6 | 1.14 ± 0.34 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.4 | 1.15 ± 0.35 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.4 | 1.16 ± 0.37 |
| mattcl-ts | input-aspidites | 10.5 ± 0.4 | 9.4 | 11.4 | 13.10 ± 3.53 |
| mattcl-ts | input-mikofo | 10.5 ± 0.4 | 9.5 | 12.0 | 13.10 ± 3.53 |
| mattcl-ts | input-pting | 10.5 ± 0.3 | 9.7 | 11.3 | 13.12 ± 3.53 |
| mattcl-ts | input-chancalan | 10.5 ± 0.3 | 9.4 | 11.2 | 13.12 ± 3.53 |
| mattcl-ts | input-lanjian | 10.5 ± 0.3 | 9.4 | 11.3 | 13.14 ± 3.53 |
| mattcl-ts | input-kcen | 10.5 ± 0.4 | 9.3 | 11.5 | 13.14 ± 3.54 |
| mattcl-ts | input-mattcl | 10.8 ± 4.0 | 9.3 | 67.4 | 13.46 ± 6.20 |
| mikofo | input-lanjian | 11.2 ± 0.4 | 10.1 | 12.3 | 14.00 ± 3.78 |
| mikofo | input-chancalan | 11.2 ± 0.4 | 10.3 | 12.4 | 14.03 ± 3.78 |
| mikofo | input-mattcl | 11.2 ± 0.4 | 10.3 | 13.0 | 14.05 ± 3.79 |
| mikofo | input-mikofo | 11.3 ± 0.4 | 10.2 | 12.5 | 14.09 ± 3.80 |
| mikofo | input-kcen | 11.3 ± 0.3 | 10.4 | 12.4 | 14.13 ± 3.80 |
| mikofo | input-pting | 11.3 ± 0.3 | 10.3 | 12.4 | 14.18 ± 3.81 |
| mikofo | input-aspidites | 11.4 ± 0.3 | 10.2 | 12.2 | 14.20 ± 3.82 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.7 | 13.9 | 15.87 ± 4.29 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.9 | 14.2 | 15.91 ± 4.29 |
| aspidites | input-pting | 12.8 ± 0.5 | 11.8 | 14.0 | 15.97 ± 4.31 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.9 | 14.2 | 16.01 ± 4.32 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.8 | 15.0 | 16.02 ± 4.33 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.8 | 14.1 | 16.02 ± 4.32 |
| aspidites | input-mikofo | 12.9 ± 0.5 | 11.8 | 14.4 | 16.12 ± 4.35 |
| pting | input-chancalan | 14.2 ± 0.5 | 13.5 | 17.4 | 17.80 ± 4.81 |
| pting | input-mikofo | 14.3 ± 0.6 | 13.4 | 18.7 | 17.90 ± 4.85 |
| pting | input-pting | 14.3 ± 0.5 | 13.4 | 17.5 | 17.92 ± 4.84 |
| pting | input-kcen | 14.3 ± 0.5 | 13.5 | 17.0 | 17.93 ± 4.84 |
| pting | input-mattcl | 14.3 ± 0.6 | 13.4 | 17.5 | 17.93 ± 4.84 |
| mattcl-py | input-mikofo | 14.3 ± 0.5 | 13.5 | 17.1 | 17.93 ± 4.83 |
| mattcl-py | input-lanjian | 14.4 ± 0.5 | 13.5 | 16.7 | 17.94 ± 4.83 |
| mattcl-py | input-kcen | 14.4 ± 0.5 | 13.6 | 17.7 | 17.97 ± 4.85 |
| mattcl-py | input-aspidites | 14.4 ± 0.6 | 13.6 | 18.3 | 17.98 ± 4.86 |
| mattcl-py | input-chancalan | 14.4 ± 0.6 | 13.6 | 17.4 | 18.01 ± 4.86 |
| mattcl-py | input-pting | 14.4 ± 0.6 | 13.3 | 17.6 | 18.02 ± 4.88 |
| mattcl-py | input-mattcl | 14.4 ± 0.7 | 13.5 | 18.3 | 18.05 ± 4.89 |
| pting | input-lanjian | 14.5 ± 2.0 | 13.4 | 40.2 | 18.17 ± 5.44 |
| pting | input-aspidites | 14.7 ± 3.0 | 13.4 | 56.6 | 18.31 ± 6.20 |
| chancalan | input-aspidites | 15.0 ± 0.5 | 14.0 | 17.8 | 18.71 ± 5.05 |
| chancalan | input-mikofo | 15.0 ± 0.6 | 14.1 | 18.2 | 18.73 ± 5.06 |
| chancalan | input-pting | 15.0 ± 0.5 | 14.0 | 18.1 | 18.75 ± 5.06 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 14.1 | 18.1 | 18.76 ± 5.06 |
| chancalan | input-kcen | 15.1 ± 0.6 | 14.0 | 17.7 | 18.82 ± 5.08 |
| chancalan | input-mattcl | 15.1 ± 0.7 | 14.0 | 18.3 | 18.86 ± 5.11 |
| chancalan | input-chancalan | 15.2 ± 2.4 | 14.0 | 47.6 | 18.95 ± 5.88 |
| kcen | input-lanjian | 15.2 ± 0.6 | 14.3 | 18.0 | 18.97 ± 5.12 |
| kcen | input-mikofo | 15.2 ± 0.5 | 14.2 | 18.1 | 19.04 ± 5.13 |
| kcen | input-kcen | 15.2 ± 0.5 | 14.3 | 17.8 | 19.05 ± 5.14 |
| kcen | input-aspidites | 15.3 ± 0.6 | 14.5 | 18.3 | 19.08 ± 5.16 |
| kcen | input-chancalan | 15.3 ± 0.5 | 14.2 | 17.9 | 19.08 ± 5.15 |
| kcen | input-pting | 15.3 ± 0.6 | 14.3 | 18.4 | 19.13 ± 5.17 |
| kcen | input-mattcl | 15.5 ± 1.9 | 14.5 | 40.1 | 19.32 ± 5.69 |


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