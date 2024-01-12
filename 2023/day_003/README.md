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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.01 ± 0.26 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.5 | 1.01 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.2 | 1.05 ± 0.25 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.7 | 1.7 | 1.41 ± 0.35 |
| lanjian | input-mikofo | 1.4 ± 2.1 | 0.4 | 30.4 | 1.41 ± 2.15 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 1.9 | 1.42 ± 0.36 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 1.9 | 1.43 ± 0.36 |
| lanjian | input-kcen | 1.5 ± 0.2 | 1.0 | 1.9 | 1.49 ± 0.36 |
| mattcl-ts | input-lanjian | 12.1 ± 0.4 | 11.1 | 13.2 | 12.40 ± 2.49 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 10.8 | 13.1 | 12.43 ± 2.50 |
| mattcl-ts | input-kcen | 12.1 ± 0.4 | 11.1 | 13.1 | 12.44 ± 2.49 |
| mikofo | input-chancalan | 12.2 ± 0.4 | 11.0 | 13.4 | 12.47 ± 2.50 |
| mattcl-ts | input-chancalan | 12.2 ± 0.4 | 11.1 | 13.5 | 12.47 ± 2.50 |
| mikofo | input-kcen | 12.2 ± 0.4 | 10.9 | 12.9 | 12.47 ± 2.50 |
| mikofo | input-mikofo | 12.2 ± 0.4 | 10.9 | 13.1 | 12.48 ± 2.50 |
| mikofo | input-mattcl | 12.2 ± 0.4 | 11.1 | 13.1 | 12.49 ± 2.51 |
| mattcl-ts | input-mikofo | 12.2 ± 0.4 | 11.1 | 13.3 | 12.53 ± 2.51 |
| mikofo | input-lanjian | 12.2 ± 0.4 | 11.2 | 13.1 | 12.53 ± 2.50 |
| kcen | input-mattcl | 16.1 ± 0.5 | 14.9 | 19.7 | 16.52 ± 3.31 |
| kcen | input-chancalan | 16.1 ± 0.6 | 14.9 | 19.0 | 16.53 ± 3.32 |
| kcen | input-kcen | 16.2 ± 0.7 | 14.9 | 19.2 | 16.58 ± 3.35 |
| kcen | input-lanjian | 16.2 ± 0.6 | 15.0 | 18.7 | 16.58 ± 3.34 |
| kcen | input-mikofo | 16.6 ± 4.0 | 15.1 | 60.3 | 16.97 ± 5.29 |
| pting | input-kcen | 17.1 ± 0.7 | 16.0 | 20.4 | 17.54 ± 3.53 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.0 | 20.3 | 17.55 ± 3.54 |
| pting | input-mattcl | 17.2 ± 0.7 | 16.3 | 20.0 | 17.60 ± 3.54 |
| pting | input-mikofo | 17.2 ± 0.8 | 15.9 | 20.7 | 17.64 ± 3.58 |
| pting | input-chancalan | 17.2 ± 0.8 | 16.2 | 20.5 | 17.66 ± 3.58 |
| mattcl-py | input-lanjian | 17.4 ± 0.6 | 16.5 | 20.4 | 17.78 ± 3.56 |
| mattcl-py | input-chancalan | 17.4 ± 0.7 | 16.4 | 20.6 | 17.87 ± 3.60 |
| mattcl-py | input-mikofo | 17.5 ± 0.6 | 16.4 | 20.7 | 17.93 ± 3.59 |
| mattcl-py | input-mattcl | 17.5 ± 0.7 | 16.5 | 20.6 | 17.97 ± 3.63 |
| mattcl-py | input-kcen | 17.5 ± 0.8 | 16.3 | 21.1 | 17.98 ± 3.66 |
| chancalan | input-kcen | 21.4 ± 0.8 | 20.5 | 24.6 | 21.92 ± 4.40 |
| chancalan | input-chancalan | 21.4 ± 0.7 | 20.4 | 24.2 | 21.92 ± 4.39 |
| chancalan | input-mattcl | 21.4 ± 0.8 | 20.4 | 24.6 | 21.93 ± 4.40 |
| chancalan | input-mikofo | 21.4 ± 0.7 | 20.4 | 24.3 | 21.95 ± 4.39 |
| chancalan | input-lanjian | 21.4 ± 0.7 | 20.1 | 24.3 | 21.98 ± 4.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|