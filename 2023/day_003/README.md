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
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.0 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 2.6 | 1.01 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.2 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.23 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.5 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.8 | 1.36 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.0 | 1.38 ± 0.30 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 2.2 | 1.40 ± 0.31 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.2 | 1.41 ± 0.32 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.8 | 2.2 | 1.41 ± 0.33 |
| mikofo | input-lanjian | 12.7 ± 0.3 | 11.8 | 13.6 | 12.68 ± 2.07 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.9 | 13.8 | 12.68 ± 2.07 |
| mikofo | input-mikofo | 12.7 ± 0.3 | 12.1 | 13.4 | 12.69 ± 2.07 |
| mikofo | input-mattcl | 12.7 ± 0.3 | 11.9 | 13.9 | 12.70 ± 2.08 |
| mattcl-ts | input-mikofo | 12.8 ± 0.4 | 11.7 | 13.6 | 12.74 ± 2.09 |
| mattcl-ts | input-kcen | 12.8 ± 0.4 | 11.9 | 14.1 | 12.74 ± 2.09 |
| mikofo | input-kcen | 12.8 ± 0.3 | 12.2 | 13.8 | 12.75 ± 2.08 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 12.0 | 13.9 | 12.77 ± 2.10 |
| mattcl-ts | input-mattcl | 12.8 ± 0.3 | 11.9 | 13.6 | 12.77 ± 2.09 |
| mattcl-ts | input-lanjian | 12.8 ± 0.4 | 12.0 | 13.7 | 12.78 ± 2.09 |
| kcen | input-chancalan | 16.2 ± 0.6 | 15.0 | 19.6 | 16.14 ± 2.67 |
| kcen | input-mattcl | 16.2 ± 0.5 | 15.0 | 18.8 | 16.20 ± 2.67 |
| kcen | input-mikofo | 16.3 ± 0.6 | 15.2 | 19.9 | 16.26 ± 2.69 |
| kcen | input-lanjian | 16.4 ± 0.8 | 15.2 | 19.6 | 16.35 ± 2.75 |
| kcen | input-kcen | 16.5 ± 2.5 | 15.2 | 49.1 | 16.50 ± 3.67 |
| pting | input-kcen | 17.3 ± 0.7 | 16.5 | 20.6 | 17.30 ± 2.89 |
| pting | input-chancalan | 17.4 ± 0.7 | 16.2 | 20.7 | 17.33 ± 2.89 |
| pting | input-lanjian | 17.4 ± 0.8 | 16.2 | 20.8 | 17.34 ± 2.91 |
| pting | input-mikofo | 17.4 ± 0.8 | 16.1 | 20.9 | 17.39 ± 2.92 |
| mattcl-py | input-lanjian | 17.4 ± 0.6 | 16.5 | 21.2 | 17.41 ± 2.88 |
| pting | input-mattcl | 17.5 ± 0.9 | 16.1 | 20.9 | 17.44 ± 2.97 |
| mattcl-py | input-mattcl | 17.5 ± 0.7 | 16.6 | 20.7 | 17.46 ± 2.92 |
| mattcl-py | input-chancalan | 17.5 ± 0.7 | 16.3 | 20.4 | 17.51 ± 2.91 |
| mattcl-py | input-mikofo | 17.6 ± 0.8 | 16.6 | 20.8 | 17.55 ± 2.93 |
| mattcl-py | input-kcen | 17.6 ± 0.8 | 16.3 | 20.9 | 17.58 ± 2.95 |
| chancalan | input-kcen | 21.5 ± 0.7 | 20.1 | 24.8 | 21.43 ± 3.53 |
| chancalan | input-chancalan | 21.5 ± 0.7 | 20.1 | 24.8 | 21.47 ± 3.54 |
| chancalan | input-mattcl | 21.5 ± 0.7 | 20.5 | 24.5 | 21.47 ± 3.53 |
| chancalan | input-lanjian | 21.6 ± 0.7 | 20.6 | 25.1 | 21.55 ± 3.54 |
| chancalan | input-mikofo | 21.7 ± 0.8 | 20.5 | 24.4 | 21.63 ± 3.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|