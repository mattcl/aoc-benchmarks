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
| mattcl | input-chancalan | 1.0 ± 0.3 | 0.3 | 1.3 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.37 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.2 | 1.10 ± 0.36 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.6 | 1.2 | 1.10 ± 0.35 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.7 | 1.11 ± 0.36 |
| lanjian | input-chancalan | 1.1 ± 2.9 | 0.4 | 41.5 | 1.14 ± 3.02 |
| lanjian | input-kcen | 1.2 ± 0.3 | 0.4 | 1.7 | 1.20 ± 0.45 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.7 | 1.33 ± 0.43 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.5 | 1.5 | 1.33 ± 0.44 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.8 | 1.8 | 1.36 ± 0.43 |
| mattcl-ts | input-kcen | 11.7 ± 0.3 | 10.7 | 12.5 | 12.09 ± 3.53 |
| mattcl-ts | input-lanjian | 11.7 ± 0.4 | 11.0 | 13.3 | 12.18 ± 3.56 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.8 | 12.7 | 12.20 ± 3.57 |
| mattcl-ts | input-pting | 11.9 ± 2.1 | 10.9 | 40.4 | 12.35 ± 4.17 |
| mattcl-ts | input-chancalan | 12.0 ± 0.5 | 10.9 | 13.3 | 12.45 ± 3.65 |
| kcen | input-lanjian | 16.1 ± 0.6 | 15.1 | 19.6 | 16.71 ± 4.89 |
| kcen | input-mattcl | 16.2 ± 0.6 | 15.1 | 18.9 | 16.76 ± 4.91 |
| kcen | input-pting | 16.3 ± 0.7 | 15.1 | 19.2 | 16.89 ± 4.96 |
| kcen | input-kcen | 16.3 ± 0.8 | 15.3 | 19.6 | 16.90 ± 4.98 |
| kcen | input-chancalan | 16.6 ± 3.6 | 15.0 | 55.4 | 17.19 ± 6.26 |
| mattcl-py | input-mattcl | 17.4 ± 0.7 | 16.3 | 20.8 | 18.08 ± 5.31 |
| mattcl-py | input-kcen | 17.4 ± 0.6 | 16.4 | 20.7 | 18.09 ± 5.30 |
| mattcl-py | input-lanjian | 17.5 ± 0.8 | 16.1 | 20.9 | 18.14 ± 5.33 |
| mattcl-py | input-pting | 17.5 ± 0.6 | 16.3 | 20.6 | 18.19 ± 5.33 |
| mattcl-py | input-chancalan | 18.0 ± 2.3 | 16.9 | 47.2 | 18.69 ± 5.94 |
| pting | input-lanjian | 18.4 ± 0.7 | 17.4 | 21.5 | 19.12 ± 5.61 |
| pting | input-kcen | 18.4 ± 0.8 | 17.4 | 21.9 | 19.13 ± 5.62 |
| pting | input-mattcl | 18.5 ± 0.8 | 17.6 | 22.2 | 19.20 ± 5.64 |
| pting | input-pting | 18.6 ± 0.7 | 17.4 | 22.0 | 19.27 ± 5.65 |
| pting | input-chancalan | 18.6 ± 0.7 | 17.7 | 22.0 | 19.28 ± 5.65 |
| chancalan | input-mattcl | 21.3 ± 0.5 | 20.4 | 23.5 | 22.07 ± 6.44 |
| chancalan | input-lanjian | 21.3 ± 0.5 | 20.6 | 23.8 | 22.12 ± 6.45 |
| chancalan | input-kcen | 21.4 ± 0.7 | 20.4 | 24.5 | 22.21 ± 6.50 |
| chancalan | input-pting | 21.5 ± 0.7 | 20.8 | 24.6 | 22.33 ± 6.53 |
| chancalan | input-chancalan | 22.1 ± 4.7 | 20.0 | 68.3 | 22.96 ± 8.25 |
| mikofo | input-kcen | 276.1 ± 2.3 | 271.4 | 278.9 | 286.38 ± 83.27 |
| mikofo | input-pting | 276.9 ± 1.4 | 274.3 | 278.8 | 287.23 ± 83.49 |
| mikofo | input-lanjian | 277.4 ± 2.9 | 274.8 | 284.3 | 287.76 ± 83.69 |
| mikofo | input-mattcl | 279.3 ± 2.1 | 276.4 | 283.7 | 289.69 ± 84.22 |
| mikofo | input-chancalan | 282.7 ± 8.8 | 274.0 | 304.0 | 293.19 ± 85.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|