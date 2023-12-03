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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.26 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.27 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.29 |
| lanjian | input-chancalan | 1.5 ± 0.3 | 0.8 | 2.2 | 1.36 ± 0.37 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.7 | 2.8 | 1.37 ± 0.37 |
| lanjian | input-lanjian | 1.6 ± 0.3 | 0.8 | 2.3 | 1.41 ± 0.38 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.8 | 2.1 | 1.47 ± 0.37 |
| lanjian | input-pting | 1.7 ± 0.2 | 1.0 | 2.2 | 1.52 ± 0.36 |
| kcen | input-kcen | 19.1 ± 0.7 | 18.2 | 22.9 | 17.34 ± 3.53 |
| kcen | input-chancalan | 19.1 ± 0.8 | 18.2 | 21.9 | 17.35 ± 3.54 |
| kcen | input-lanjian | 19.2 ± 0.8 | 18.2 | 22.7 | 17.41 ± 3.55 |
| kcen | input-mattcl | 19.2 ± 0.7 | 18.1 | 22.7 | 17.42 ± 3.55 |
| kcen | input-pting | 19.2 ± 0.7 | 18.2 | 22.7 | 17.43 ± 3.54 |
| mattcl-py | input-mattcl | 20.8 ± 0.5 | 19.5 | 23.3 | 18.82 ± 3.80 |
| mattcl-py | input-chancalan | 20.8 ± 0.6 | 19.7 | 23.9 | 18.86 ± 3.81 |
| mattcl-py | input-kcen | 20.9 ± 0.6 | 19.8 | 23.5 | 18.95 ± 3.83 |
| mattcl-py | input-lanjian | 20.9 ± 0.7 | 19.7 | 23.8 | 18.97 ± 3.85 |
| mattcl-py | input-pting | 20.9 ± 0.5 | 20.0 | 23.8 | 18.99 ± 3.83 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.9 | 26.4 | 20.72 ± 4.20 |
| pting | input-kcen | 22.9 ± 0.7 | 22.0 | 25.6 | 20.75 ± 4.20 |
| pting | input-chancalan | 23.0 ± 1.7 | 21.9 | 39.7 | 20.89 ± 4.44 |
| pting | input-pting | 23.1 ± 0.7 | 22.2 | 25.7 | 20.91 ± 4.23 |
| pting | input-mattcl | 23.1 ± 3.5 | 21.7 | 61.6 | 20.95 ± 5.25 |
| chancalan | input-lanjian | 25.9 ± 0.9 | 24.8 | 29.2 | 23.45 ± 4.75 |
| chancalan | input-kcen | 25.9 ± 0.8 | 25.0 | 28.9 | 23.48 ± 4.75 |
| chancalan | input-mattcl | 25.9 ± 0.8 | 25.0 | 28.6 | 23.51 ± 4.76 |
| chancalan | input-pting | 26.0 ± 0.8 | 24.8 | 28.9 | 23.55 ± 4.77 |
| chancalan | input-chancalan | 26.0 ± 0.9 | 25.0 | 29.0 | 23.56 ± 4.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|