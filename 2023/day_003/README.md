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
| lanjian | input-lanjian | 1.0 ± 0.3 | 0.4 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.41 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.40 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.8 | 1.07 ± 0.39 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.08 ± 0.39 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.11 ± 0.41 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.6 | 1.27 ± 0.46 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.8 | 1.29 ± 0.47 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.0 | 1.31 ± 0.48 |
| lanjian | input-pting | 1.5 ± 0.2 | 0.8 | 1.9 | 1.42 ± 0.51 |
| mattcl-ts | input-kcen | 12.2 ± 0.4 | 11.3 | 13.2 | 11.77 ± 3.91 |
| mattcl-ts | input-lanjian | 12.2 ± 0.4 | 11.2 | 13.2 | 11.80 ± 3.92 |
| mattcl-ts | input-mattcl | 12.2 ± 0.3 | 11.5 | 13.1 | 11.83 ± 3.93 |
| mattcl-ts | input-pting | 12.3 ± 0.4 | 11.4 | 13.6 | 11.86 ± 3.94 |
| mattcl-ts | input-chancalan | 12.3 ± 0.4 | 11.2 | 13.4 | 11.86 ± 3.94 |
| kcen | input-lanjian | 16.2 ± 0.6 | 15.2 | 18.6 | 15.68 ± 5.22 |
| kcen | input-mattcl | 16.3 ± 0.7 | 15.1 | 19.0 | 15.74 ± 5.25 |
| kcen | input-pting | 16.3 ± 0.6 | 15.1 | 19.1 | 15.74 ± 5.24 |
| kcen | input-chancalan | 16.3 ± 0.7 | 15.2 | 19.6 | 15.75 ± 5.26 |
| kcen | input-kcen | 16.5 ± 3.0 | 14.9 | 56.4 | 15.96 ± 6.04 |
| mattcl-py | input-lanjian | 17.4 ± 0.6 | 16.2 | 20.4 | 16.86 ± 5.60 |
| mattcl-py | input-mattcl | 17.5 ± 0.7 | 16.2 | 21.0 | 16.92 ± 5.63 |
| mattcl-py | input-pting | 17.5 ± 0.7 | 16.4 | 20.9 | 16.95 ± 5.65 |
| mattcl-py | input-kcen | 17.5 ± 0.7 | 16.5 | 21.1 | 16.96 ± 5.66 |
| mattcl-py | input-chancalan | 17.7 ± 2.3 | 16.5 | 46.5 | 17.11 ± 6.09 |
| pting | input-chancalan | 18.4 ± 0.6 | 17.6 | 21.6 | 17.85 ± 5.93 |
| pting | input-kcen | 18.5 ± 0.7 | 17.5 | 21.8 | 17.88 ± 5.95 |
| pting | input-lanjian | 18.5 ± 0.8 | 17.4 | 21.8 | 17.89 ± 5.96 |
| pting | input-mattcl | 18.5 ± 0.8 | 17.5 | 22.2 | 17.90 ± 5.97 |
| pting | input-pting | 18.6 ± 0.6 | 17.5 | 21.6 | 17.99 ± 5.98 |
| chancalan | input-lanjian | 21.3 ± 0.5 | 20.4 | 24.1 | 20.62 ± 6.84 |
| chancalan | input-mattcl | 21.4 ± 0.6 | 20.7 | 24.3 | 20.70 ± 6.87 |
| chancalan | input-chancalan | 21.4 ± 0.6 | 20.5 | 23.8 | 20.74 ± 6.88 |
| chancalan | input-pting | 21.6 ± 0.9 | 20.7 | 25.0 | 20.91 ± 6.97 |
| chancalan | input-kcen | 22.2 ± 5.5 | 20.3 | 73.8 | 21.46 ± 8.88 |
| mikofo | input-mattcl | 31.4 ± 0.4 | 30.5 | 32.4 | 30.37 ± 10.05 |
| mikofo | input-kcen | 31.4 ± 0.4 | 30.4 | 32.8 | 30.40 ± 10.06 |
| mikofo | input-lanjian | 31.4 ± 0.4 | 30.4 | 32.6 | 30.41 ± 10.07 |
| mikofo | input-pting | 31.4 ± 0.4 | 30.5 | 32.8 | 30.43 ± 10.07 |
| mikofo | input-chancalan | 31.4 ± 0.4 | 30.8 | 32.3 | 30.43 ± 10.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|