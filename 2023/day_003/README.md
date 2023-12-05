# Day 3 benchmarks

[link to problem](https://adventofcode.com/2023/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.7 | 1.05 ± 0.28 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.5 | 1.5 | 1.07 ± 0.26 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.6 | 1.24 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.25 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.7 | 1.31 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 2.1 | 1.31 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 1.9 | 1.31 ± 0.33 |
| mattcl-ts | input-lanjian | 12.1 ± 0.4 | 11.2 | 13.0 | 12.49 ± 2.53 |
| mattcl-ts | input-chancalan | 12.1 ± 0.4 | 11.1 | 13.1 | 12.53 ± 2.53 |
| mattcl-ts | input-kcen | 12.2 ± 0.4 | 11.2 | 13.5 | 12.58 ± 2.55 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.2 | 13.1 | 12.59 ± 2.55 |
| mattcl-ts | input-pting | 12.3 ± 0.4 | 11.4 | 13.2 | 12.64 ± 2.56 |
| kcen | input-kcen | 16.2 ± 0.7 | 15.3 | 19.5 | 16.66 ± 3.40 |
| kcen | input-lanjian | 16.2 ± 0.6 | 15.4 | 19.0 | 16.73 ± 3.41 |
| kcen | input-mattcl | 16.2 ± 0.5 | 15.2 | 18.5 | 16.74 ± 3.39 |
| kcen | input-pting | 16.3 ± 0.6 | 14.9 | 20.4 | 16.79 ± 3.41 |
| kcen | input-chancalan | 16.4 ± 0.9 | 15.0 | 20.3 | 16.87 ± 3.49 |
| mattcl-py | input-chancalan | 17.4 ± 0.7 | 16.2 | 20.8 | 17.95 ± 3.66 |
| mattcl-py | input-kcen | 17.4 ± 0.6 | 16.5 | 20.0 | 17.98 ± 3.64 |
| mattcl-py | input-lanjian | 17.5 ± 0.6 | 16.6 | 20.5 | 18.01 ± 3.65 |
| mattcl-py | input-pting | 17.5 ± 0.6 | 16.5 | 20.6 | 18.07 ± 3.67 |
| mattcl-py | input-mattcl | 17.5 ± 0.6 | 16.2 | 20.5 | 18.10 ± 3.67 |
| pting | input-chancalan | 18.4 ± 0.6 | 17.0 | 22.1 | 18.94 ± 3.85 |
| pting | input-mattcl | 18.5 ± 0.8 | 17.4 | 22.1 | 19.06 ± 3.89 |
| pting | input-kcen | 18.6 ± 0.7 | 17.4 | 21.4 | 19.15 ± 3.90 |
| pting | input-lanjian | 18.6 ± 0.8 | 17.5 | 21.5 | 19.18 ± 3.92 |
| pting | input-pting | 18.7 ± 0.8 | 17.3 | 22.0 | 19.27 ± 3.94 |
| chancalan | input-chancalan | 21.3 ± 0.7 | 20.4 | 24.1 | 22.00 ± 4.45 |
| chancalan | input-kcen | 21.4 ± 0.8 | 20.4 | 24.6 | 22.03 ± 4.48 |
| chancalan | input-lanjian | 21.4 ± 0.5 | 20.1 | 24.4 | 22.08 ± 4.45 |
| chancalan | input-mattcl | 21.5 ± 0.7 | 20.0 | 24.4 | 22.13 ± 4.48 |
| chancalan | input-pting | 21.6 ± 0.6 | 20.7 | 24.4 | 22.25 ± 4.50 |
| mikofo | input-chancalan | 277.4 ± 2.3 | 274.8 | 280.9 | 286.13 ± 57.33 |
| mikofo | input-kcen | 278.6 ± 1.9 | 276.5 | 281.7 | 287.30 ± 57.54 |
| mikofo | input-pting | 279.2 ± 2.6 | 275.5 | 283.2 | 287.97 ± 57.71 |
| mikofo | input-lanjian | 279.4 ± 2.3 | 275.0 | 283.0 | 288.17 ± 57.74 |
| mikofo | input-mattcl | 283.9 ± 14.7 | 276.6 | 325.5 | 292.80 ± 60.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|