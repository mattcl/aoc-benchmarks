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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.1 | 1.6 | 1.03 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.04 ± 0.30 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.07 ± 0.30 |
| mattcl | input-mattcl | 1.1 ± 3.2 | 0.2 | 45.4 | 1.22 ± 3.42 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 2.0 | 1.44 ± 0.40 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.44 ± 0.40 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.8 | 1.9 | 1.45 ± 0.40 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.5 | 2.1 | 1.48 ± 0.40 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.57 ± 0.45 |
| mikofo | input-mikofo | 12.6 ± 0.3 | 11.6 | 13.5 | 13.57 ± 3.20 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.6 | 13.4 | 13.57 ± 3.20 |
| mikofo | input-mattcl | 12.6 ± 0.3 | 11.8 | 13.3 | 13.58 ± 3.20 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.6 | 14.1 | 13.58 ± 3.20 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.5 | 13.5 | 13.58 ± 3.20 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 12.0 | 13.6 | 13.64 ± 3.22 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 12.0 | 13.7 | 13.64 ± 3.22 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.8 | 14.3 | 13.64 ± 3.22 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.8 | 13.5 | 13.65 ± 3.22 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 11.9 | 14.3 | 13.69 ± 3.24 |
| kcen | input-lanjian | 16.1 ± 0.6 | 15.0 | 19.3 | 17.41 ± 4.15 |
| kcen | input-mattcl | 16.1 ± 0.6 | 14.9 | 19.5 | 17.45 ± 4.15 |
| kcen | input-mikofo | 16.2 ± 0.6 | 15.1 | 19.3 | 17.46 ± 4.15 |
| kcen | input-kcen | 16.2 ± 0.8 | 15.1 | 19.6 | 17.53 ± 4.20 |
| kcen | input-chancalan | 16.2 ± 0.7 | 15.1 | 19.8 | 17.56 ± 4.20 |
| pting | input-mattcl | 17.0 ± 0.6 | 15.8 | 19.6 | 18.39 ± 4.37 |
| pting | input-chancalan | 17.1 ± 0.7 | 16.0 | 20.3 | 18.44 ± 4.39 |
| pting | input-kcen | 17.1 ± 0.6 | 16.3 | 19.7 | 18.47 ± 4.38 |
| pting | input-mikofo | 17.1 ± 0.6 | 16.4 | 20.5 | 18.50 ± 4.39 |
| pting | input-lanjian | 17.2 ± 0.8 | 16.2 | 20.0 | 18.56 ± 4.43 |
| mattcl-py | input-lanjian | 17.3 ± 0.6 | 16.4 | 19.9 | 18.72 ± 4.44 |
| mattcl-py | input-kcen | 17.4 ± 0.7 | 16.3 | 20.8 | 18.80 ± 4.49 |
| mattcl-py | input-chancalan | 17.4 ± 0.7 | 16.0 | 20.4 | 18.82 ± 4.49 |
| mattcl-py | input-mikofo | 17.4 ± 0.7 | 16.7 | 20.7 | 18.85 ± 4.48 |
| mattcl-py | input-mattcl | 17.8 ± 3.4 | 16.3 | 55.5 | 19.21 ± 5.85 |
| chancalan | input-kcen | 21.2 ± 0.6 | 20.4 | 24.2 | 22.91 ± 5.42 |
| chancalan | input-lanjian | 21.3 ± 0.5 | 20.3 | 23.6 | 22.98 ± 5.43 |
| chancalan | input-mikofo | 21.3 ± 0.6 | 20.3 | 24.9 | 23.01 ± 5.45 |
| chancalan | input-mattcl | 21.3 ± 0.6 | 20.5 | 24.4 | 23.02 ± 5.44 |
| chancalan | input-chancalan | 21.4 ± 0.7 | 20.5 | 24.3 | 23.18 ± 5.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|