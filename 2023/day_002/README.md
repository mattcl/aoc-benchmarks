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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.01 ± 0.26 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.29 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.5 | 1.3 | 1.02 ± 0.27 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.2 | 1.03 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.28 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.03 ± 0.27 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.27 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.28 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.4 | 1.6 | 1.07 ± 0.26 |
| mattcl-ts | input-lanjian | 11.0 ± 0.4 | 10.0 | 12.0 | 12.67 ± 2.62 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 9.8 | 11.9 | 12.67 ± 2.62 |
| mattcl-ts | input-aspidites | 11.0 ± 0.4 | 9.8 | 11.8 | 12.70 ± 2.62 |
| mattcl-ts | input-mattcl | 11.0 ± 0.4 | 9.8 | 13.1 | 12.70 ± 2.63 |
| mattcl-ts | input-kcen | 11.2 ± 3.4 | 9.9 | 58.4 | 12.98 ± 4.72 |
| mikofo | input-kcen | 11.3 ± 0.3 | 10.2 | 12.2 | 13.01 ± 2.68 |
| mikofo | input-chancalan | 11.3 ± 0.3 | 10.0 | 12.6 | 13.02 ± 2.68 |
| mikofo | input-lanjian | 11.3 ± 0.3 | 10.1 | 12.0 | 13.02 ± 2.68 |
| mikofo | input-mattcl | 11.3 ± 0.4 | 10.2 | 12.5 | 13.04 ± 2.69 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.4 | 12.5 | 13.07 ± 2.69 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.7 | 14.4 | 14.67 ± 3.04 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.8 | 14.0 | 14.75 ± 3.05 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.7 | 14.2 | 14.77 ± 3.07 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.8 | 14.9 | 14.78 ± 3.06 |
| aspidites | input-kcen | 12.9 ± 4.3 | 10.9 | 70.3 | 14.87 ± 5.78 |
| pting | input-aspidites | 14.3 ± 0.6 | 13.4 | 17.6 | 16.58 ± 3.44 |
| pting | input-mattcl | 14.3 ± 0.6 | 13.5 | 17.4 | 16.59 ± 3.46 |
| pting | input-chancalan | 14.3 ± 0.7 | 13.2 | 17.6 | 16.59 ± 3.47 |
| pting | input-lanjian | 14.4 ± 0.6 | 13.3 | 17.1 | 16.60 ± 3.46 |
| pting | input-kcen | 14.4 ± 0.7 | 13.2 | 17.5 | 16.62 ± 3.47 |
| mattcl-py | input-lanjian | 14.4 ± 0.7 | 13.3 | 17.8 | 16.66 ± 3.48 |
| mattcl-py | input-kcen | 14.4 ± 0.7 | 13.4 | 17.8 | 16.69 ± 3.49 |
| mattcl-py | input-mattcl | 14.5 ± 0.7 | 13.5 | 17.8 | 16.73 ± 3.49 |
| mattcl-py | input-aspidites | 14.5 ± 0.6 | 13.4 | 17.9 | 16.74 ± 3.49 |
| mattcl-py | input-chancalan | 14.7 ± 3.1 | 13.3 | 54.9 | 17.00 ± 4.97 |
| chancalan | input-chancalan | 14.9 ± 0.5 | 13.9 | 18.2 | 17.27 ± 3.57 |
| chancalan | input-aspidites | 15.0 ± 0.6 | 14.0 | 18.0 | 17.33 ± 3.60 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 13.9 | 18.1 | 17.35 ± 3.60 |
| chancalan | input-kcen | 15.0 ± 0.7 | 13.9 | 18.0 | 17.37 ± 3.62 |
| chancalan | input-mattcl | 15.1 ± 0.7 | 13.9 | 17.8 | 17.44 ± 3.65 |
| kcen | input-lanjian | 15.1 ± 0.6 | 14.1 | 18.5 | 17.52 ± 3.63 |
| kcen | input-mattcl | 15.2 ± 0.6 | 14.3 | 18.1 | 17.55 ± 3.63 |
| kcen | input-kcen | 15.2 ± 0.5 | 14.2 | 18.3 | 17.56 ± 3.63 |
| kcen | input-aspidites | 15.2 ± 0.5 | 14.3 | 17.6 | 17.57 ± 3.63 |
| kcen | input-chancalan | 15.2 ± 0.6 | 14.2 | 18.0 | 17.61 ± 3.65 |


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