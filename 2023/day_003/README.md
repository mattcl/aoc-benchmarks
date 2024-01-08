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
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.5 | 1.00 ± 0.21 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.24 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.4 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.6 | 1.4 | 1.03 ± 0.20 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.5 | 2.1 | 1.35 ± 0.30 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.9 | 2.2 | 1.36 ± 0.26 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.8 | 1.9 | 1.37 ± 0.27 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.8 | 2.2 | 1.39 ± 0.29 |
| lanjian | input-kcen | 1.5 ± 0.2 | 1.1 | 2.4 | 1.42 ± 0.28 |
| mikofo | input-lanjian | 12.7 ± 0.3 | 11.8 | 13.7 | 11.93 ± 1.77 |
| mikofo | input-mattcl | 12.7 ± 0.3 | 11.7 | 13.5 | 11.93 ± 1.77 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.6 | 13.9 | 11.95 ± 1.77 |
| mikofo | input-kcen | 12.7 ± 0.3 | 12.0 | 13.8 | 11.99 ± 1.77 |
| mattcl-ts | input-kcen | 12.7 ± 0.4 | 11.7 | 14.3 | 12.00 ± 1.79 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.7 | 13.8 | 12.00 ± 1.78 |
| mikofo | input-mikofo | 12.8 ± 0.3 | 11.8 | 13.9 | 12.02 ± 1.78 |
| mattcl-ts | input-mattcl | 12.8 ± 0.4 | 11.9 | 13.7 | 12.03 ± 1.79 |
| mattcl-ts | input-lanjian | 12.8 ± 0.3 | 12.0 | 13.8 | 12.05 ± 1.79 |
| mattcl-ts | input-mikofo | 12.8 ± 0.3 | 12.0 | 13.7 | 12.07 ± 1.79 |
| kcen | input-kcen | 16.3 ± 0.7 | 15.0 | 19.3 | 15.32 ± 2.34 |
| kcen | input-mattcl | 16.3 ± 0.6 | 15.5 | 19.3 | 15.36 ± 2.32 |
| kcen | input-chancalan | 16.3 ± 0.7 | 15.4 | 19.4 | 15.36 ± 2.33 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.4 | 15.39 ± 2.34 |
| kcen | input-mikofo | 16.4 ± 0.7 | 15.1 | 19.6 | 15.42 ± 2.35 |
| pting | input-chancalan | 17.2 ± 0.5 | 16.0 | 19.8 | 16.24 ± 2.43 |
| pting | input-kcen | 17.3 ± 0.7 | 16.4 | 20.3 | 16.29 ± 2.46 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.2 | 20.7 | 16.32 ± 2.47 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.1 | 20.5 | 16.36 ± 2.49 |
| pting | input-mikofo | 17.4 ± 0.7 | 16.3 | 20.2 | 16.36 ± 2.48 |
| mattcl-py | input-lanjian | 17.5 ± 0.6 | 16.6 | 21.0 | 16.47 ± 2.46 |
| mattcl-py | input-mikofo | 17.7 ± 0.8 | 16.5 | 21.2 | 16.64 ± 2.54 |
| mattcl-py | input-chancalan | 17.7 ± 0.8 | 16.5 | 20.9 | 16.65 ± 2.55 |
| mattcl-py | input-kcen | 17.7 ± 0.7 | 16.6 | 20.8 | 16.65 ± 2.53 |
| mattcl-py | input-mattcl | 17.7 ± 2.3 | 16.5 | 45.9 | 16.66 ± 3.26 |
| chancalan | input-kcen | 21.5 ± 0.6 | 20.8 | 24.3 | 20.22 ± 3.02 |
| chancalan | input-lanjian | 21.5 ± 0.7 | 20.6 | 24.5 | 20.28 ± 3.03 |
| chancalan | input-chancalan | 21.6 ± 0.8 | 20.3 | 24.7 | 20.34 ± 3.06 |
| chancalan | input-mikofo | 21.6 ± 0.7 | 20.7 | 24.8 | 20.37 ± 3.05 |
| chancalan | input-mattcl | 22.3 ± 4.0 | 20.6 | 56.5 | 20.96 ± 4.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|