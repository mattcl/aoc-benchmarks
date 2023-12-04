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
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.25 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 2.0 | 1.03 ± 0.28 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.7 | 1.6 | 1.09 ± 0.25 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.2 | 1.42 ± 0.34 |
| lanjian | input-pting | 1.6 ± 0.2 | 0.7 | 2.1 | 1.47 ± 0.35 |
| lanjian | input-chancalan | 1.6 ± 0.3 | 0.5 | 2.5 | 1.48 ± 0.39 |
| lanjian | input-kcen | 1.6 ± 0.3 | 0.6 | 2.3 | 1.51 ± 0.38 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 1.0 | 2.1 | 1.54 ± 0.33 |
| kcen | input-mattcl | 18.7 ± 0.6 | 17.5 | 21.3 | 17.43 ± 3.32 |
| kcen | input-chancalan | 18.7 ± 0.7 | 17.8 | 22.4 | 17.45 ± 3.34 |
| kcen | input-lanjian | 18.8 ± 0.7 | 17.6 | 22.0 | 17.53 ± 3.35 |
| kcen | input-kcen | 18.8 ± 0.9 | 17.7 | 21.9 | 17.60 ± 3.41 |
| kcen | input-pting | 18.9 ± 0.7 | 17.9 | 21.8 | 17.62 ± 3.37 |
| mattcl-py | input-kcen | 20.7 ± 0.6 | 19.9 | 24.0 | 19.34 ± 3.68 |
| mattcl-py | input-chancalan | 20.8 ± 0.6 | 19.8 | 23.2 | 19.41 ± 3.69 |
| mattcl-py | input-lanjian | 20.9 ± 0.8 | 19.7 | 24.1 | 19.54 ± 3.75 |
| mattcl-py | input-pting | 21.2 ± 0.9 | 19.8 | 24.4 | 19.77 ± 3.80 |
| mattcl-py | input-mattcl | 21.2 ± 3.8 | 19.6 | 55.4 | 19.82 ± 5.17 |
| pting | input-kcen | 22.8 ± 0.8 | 21.9 | 26.4 | 21.31 ± 4.07 |
| pting | input-chancalan | 22.8 ± 0.9 | 21.8 | 26.0 | 21.34 ± 4.10 |
| pting | input-mattcl | 22.9 ± 0.9 | 21.7 | 26.0 | 21.38 ± 4.10 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.7 | 26.2 | 21.45 ± 4.12 |
| pting | input-pting | 23.1 ± 0.7 | 22.0 | 26.3 | 21.57 ± 4.11 |
| chancalan | input-kcen | 25.7 ± 0.7 | 24.3 | 28.3 | 24.00 ± 4.55 |
| chancalan | input-lanjian | 25.9 ± 0.8 | 25.0 | 28.9 | 24.18 ± 4.60 |
| chancalan | input-chancalan | 25.9 ± 0.8 | 24.7 | 29.3 | 24.19 ± 4.61 |
| chancalan | input-mattcl | 25.9 ± 0.9 | 24.8 | 28.7 | 24.20 ± 4.62 |
| chancalan | input-pting | 26.0 ± 0.9 | 25.0 | 28.8 | 24.30 ± 4.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|