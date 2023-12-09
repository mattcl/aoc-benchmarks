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
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.37 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.0 | 1.05 ± 0.33 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.36 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.06 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.1 | 0.9 | 1.07 ± 0.33 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.34 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.35 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.4 | 1.0 | 1.08 ± 0.32 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.09 ± 0.36 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.09 ± 0.36 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.10 ± 0.35 |
| lanjian | input-aspidites | 0.8 ± 0.1 | 0.2 | 1.1 | 1.13 ± 0.34 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.15 ± 0.33 |
| mattcl-ts | input-lanjian | 10.4 ± 0.4 | 9.4 | 11.5 | 13.91 ± 3.58 |
| mattcl-ts | input-aspidites | 10.4 ± 0.4 | 9.0 | 11.2 | 13.93 ± 3.58 |
| mattcl-ts | input-mikofo | 10.4 ± 0.4 | 9.1 | 11.5 | 13.94 ± 3.60 |
| mattcl-ts | input-chancalan | 10.4 ± 0.3 | 9.4 | 11.4 | 13.95 ± 3.58 |
| mattcl-ts | input-kcen | 10.4 ± 0.3 | 9.4 | 11.2 | 13.96 ± 3.59 |
| mattcl-ts | input-pting | 10.4 ± 0.4 | 9.2 | 11.4 | 13.98 ± 3.60 |
| mattcl-ts | input-mattcl | 10.4 ± 0.3 | 9.3 | 11.3 | 14.01 ± 3.60 |
| mikofo | input-aspidites | 11.1 ± 0.4 | 10.1 | 12.1 | 14.91 ± 3.83 |
| mikofo | input-mattcl | 11.1 ± 0.4 | 9.8 | 12.6 | 14.92 ± 3.84 |
| mikofo | input-lanjian | 11.1 ± 0.4 | 10.2 | 12.5 | 14.93 ± 3.84 |
| mikofo | input-pting | 11.1 ± 0.4 | 10.2 | 12.6 | 14.95 ± 3.84 |
| mikofo | input-mikofo | 11.1 ± 0.4 | 10.0 | 12.2 | 14.95 ± 3.84 |
| mikofo | input-kcen | 11.2 ± 0.4 | 10.1 | 11.9 | 14.97 ± 3.85 |
| mikofo | input-chancalan | 11.2 ± 0.3 | 10.2 | 11.9 | 15.04 ± 3.86 |
| aspidites | input-kcen | 12.6 ± 0.5 | 11.5 | 13.9 | 16.94 ± 4.37 |
| aspidites | input-aspidites | 12.6 ± 0.5 | 11.6 | 14.2 | 16.94 ± 4.37 |
| aspidites | input-mikofo | 12.6 ± 0.5 | 11.5 | 14.1 | 16.97 ± 4.37 |
| aspidites | input-pting | 12.7 ± 0.4 | 11.7 | 14.1 | 17.10 ± 4.40 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.8 | 13.9 | 17.11 ± 4.40 |
| aspidites | input-lanjian | 12.8 ± 0.4 | 11.8 | 14.0 | 17.13 ± 4.40 |
| aspidites | input-mattcl | 12.8 ± 2.5 | 11.2 | 47.0 | 17.15 ± 5.50 |
| pting | input-mattcl | 14.2 ± 0.5 | 13.4 | 17.1 | 19.03 ± 4.90 |
| pting | input-chancalan | 14.2 ± 0.6 | 13.1 | 17.9 | 19.06 ± 4.92 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.3 | 17.7 | 19.15 ± 4.96 |
| pting | input-kcen | 14.3 ± 0.6 | 13.4 | 18.0 | 19.16 ± 4.96 |
| pting | input-mikofo | 14.3 ± 0.6 | 13.2 | 17.6 | 19.16 ± 4.95 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.4 | 17.5 | 19.18 ± 4.95 |
| mattcl-py | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.5 | 19.20 ± 4.97 |
| pting | input-pting | 14.3 ± 0.7 | 13.4 | 18.1 | 19.20 ± 4.98 |
| mattcl-py | input-mattcl | 14.3 ± 0.5 | 13.3 | 16.8 | 19.20 ± 4.94 |
| mattcl-py | input-kcen | 14.3 ± 0.6 | 13.5 | 17.5 | 19.21 ± 4.97 |
| mattcl-py | input-pting | 14.3 ± 0.7 | 13.3 | 18.3 | 19.22 ± 4.98 |
| mattcl-py | input-mikofo | 14.3 ± 0.6 | 13.4 | 17.3 | 19.22 ± 4.95 |
| pting | input-aspidites | 14.4 ± 0.7 | 13.1 | 17.8 | 19.27 ± 5.01 |
| mattcl-py | input-aspidites | 14.4 ± 0.6 | 13.5 | 17.3 | 19.30 ± 4.99 |
| chancalan | input-lanjian | 14.9 ± 0.5 | 13.8 | 17.7 | 19.99 ± 5.14 |
| chancalan | input-mattcl | 14.9 ± 0.7 | 13.8 | 18.3 | 20.01 ± 5.19 |
| chancalan | input-chancalan | 14.9 ± 0.6 | 14.0 | 18.7 | 20.03 ± 5.17 |
| chancalan | input-kcen | 14.9 ± 0.6 | 13.9 | 18.1 | 20.03 ± 5.17 |
| chancalan | input-pting | 14.9 ± 0.5 | 13.8 | 18.2 | 20.04 ± 5.16 |
| chancalan | input-aspidites | 15.0 ± 0.6 | 14.2 | 18.4 | 20.06 ± 5.18 |
| chancalan | input-mikofo | 15.0 ± 0.7 | 14.0 | 18.3 | 20.14 ± 5.22 |
| kcen | input-kcen | 15.1 ± 0.4 | 14.1 | 18.0 | 20.25 ± 5.19 |
| kcen | input-mattcl | 15.1 ± 0.5 | 14.2 | 18.2 | 20.27 ± 5.22 |
| kcen | input-mikofo | 15.1 ± 0.6 | 14.2 | 18.1 | 20.30 ± 5.23 |
| kcen | input-chancalan | 15.1 ± 0.6 | 14.1 | 18.3 | 20.32 ± 5.25 |
| kcen | input-aspidites | 15.2 ± 0.6 | 14.1 | 18.6 | 20.34 ± 5.25 |
| kcen | input-lanjian | 15.2 ± 0.6 | 14.1 | 18.5 | 20.38 ± 5.26 |
| kcen | input-pting | 15.2 ± 1.4 | 14.1 | 32.9 | 20.43 ± 5.54 |


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