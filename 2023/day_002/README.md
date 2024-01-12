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
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.33 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.5 | 1.05 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.6 | 1.06 ± 0.33 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.33 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.07 ± 0.33 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.09 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.5 | 1.10 ± 0.33 |
| mattcl-ts | input-mattcl | 10.4 ± 0.4 | 9.1 | 11.4 | 12.86 ± 3.09 |
| mattcl-ts | input-chancalan | 10.4 ± 0.4 | 9.3 | 11.6 | 12.87 ± 3.09 |
| mattcl-ts | input-kcen | 10.4 ± 0.4 | 9.4 | 11.4 | 12.87 ± 3.10 |
| mattcl-ts | input-aspidites | 10.4 ± 0.4 | 9.2 | 11.6 | 12.88 ± 3.09 |
| mattcl-ts | input-lanjian | 10.5 ± 0.4 | 9.3 | 11.2 | 12.91 ± 3.09 |
| mikofo | input-mattcl | 10.5 ± 0.4 | 9.4 | 11.5 | 12.93 ± 3.12 |
| mikofo | input-lanjian | 10.5 ± 0.4 | 9.6 | 11.5 | 13.00 ± 3.12 |
| mikofo | input-chancalan | 10.6 ± 0.4 | 9.6 | 11.4 | 13.04 ± 3.13 |
| mikofo | input-kcen | 10.6 ± 0.4 | 9.7 | 11.6 | 13.04 ± 3.13 |
| mikofo | input-aspidites | 10.6 ± 0.4 | 9.6 | 11.6 | 13.04 ± 3.13 |
| aspidites | input-aspidites | 12.5 ± 0.4 | 11.5 | 13.8 | 15.42 ± 3.69 |
| aspidites | input-lanjian | 12.5 ± 0.4 | 11.8 | 13.9 | 15.44 ± 3.69 |
| aspidites | input-kcen | 12.6 ± 0.5 | 11.6 | 14.9 | 15.52 ± 3.73 |
| aspidites | input-chancalan | 12.6 ± 0.4 | 11.8 | 14.2 | 15.56 ± 3.73 |
| aspidites | input-mattcl | 12.8 ± 3.4 | 10.8 | 51.4 | 15.78 ± 5.64 |
| pting | input-chancalan | 14.2 ± 0.5 | 13.4 | 17.0 | 17.59 ± 4.22 |
| pting | input-mattcl | 14.3 ± 0.5 | 13.3 | 17.6 | 17.60 ± 4.22 |
| pting | input-aspidites | 14.3 ± 0.5 | 13.6 | 17.4 | 17.61 ± 4.23 |
| mattcl-py | input-lanjian | 14.3 ± 0.5 | 13.4 | 17.3 | 17.62 ± 4.22 |
| pting | input-kcen | 14.3 ± 0.6 | 13.2 | 17.7 | 17.63 ± 4.25 |
| mattcl-py | input-kcen | 14.3 ± 0.6 | 13.5 | 18.1 | 17.65 ± 4.25 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.3 | 18.1 | 17.68 ± 4.28 |
| mattcl-py | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.8 | 17.71 ± 4.28 |
| mattcl-py | input-aspidites | 14.4 ± 0.6 | 13.4 | 17.3 | 17.74 ± 4.27 |
| mattcl-py | input-mattcl | 14.4 ± 0.7 | 13.3 | 17.5 | 17.80 ± 4.31 |
| chancalan | input-lanjian | 14.9 ± 0.6 | 14.0 | 17.7 | 18.39 ± 4.42 |
| chancalan | input-chancalan | 14.9 ± 0.6 | 13.8 | 17.5 | 18.39 ± 4.42 |
| chancalan | input-kcen | 14.9 ± 0.4 | 13.8 | 17.3 | 18.40 ± 4.39 |
| chancalan | input-aspidites | 14.9 ± 0.6 | 13.9 | 17.7 | 18.46 ± 4.44 |
| kcen | input-chancalan | 15.1 ± 0.5 | 14.2 | 18.3 | 18.61 ± 4.45 |
| chancalan | input-mattcl | 15.1 ± 3.5 | 13.8 | 62.8 | 18.67 ± 6.15 |
| kcen | input-mattcl | 15.1 ± 0.5 | 14.0 | 17.9 | 18.69 ± 4.48 |
| kcen | input-aspidites | 15.2 ± 0.6 | 14.3 | 17.9 | 18.74 ± 4.50 |
| kcen | input-lanjian | 15.2 ± 0.6 | 14.0 | 18.2 | 18.76 ± 4.52 |
| kcen | input-kcen | 15.2 ± 0.7 | 14.0 | 18.5 | 18.81 ± 4.55 |


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