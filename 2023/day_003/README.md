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
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.4 | 1.01 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.01 ± 0.19 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 1.6 ± 0.3 | 0.7 | 2.3 | 1.36 ± 0.32 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.7 | 2.2 | 1.41 ± 0.29 |
| lanjian | input-pting | 1.7 ± 0.3 | 0.8 | 2.3 | 1.42 ± 0.32 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.6 | 2.2 | 1.44 ± 0.30 |
| lanjian | input-kcen | 1.7 ± 0.2 | 0.9 | 2.2 | 1.44 ± 0.28 |
| kcen | input-chancalan | 18.7 ± 0.5 | 17.8 | 21.3 | 16.02 ± 2.42 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.8 | 21.8 | 16.08 ± 2.46 |
| kcen | input-mattcl | 18.8 ± 0.7 | 17.8 | 22.3 | 16.09 ± 2.46 |
| kcen | input-kcen | 18.8 ± 0.9 | 17.7 | 22.3 | 16.14 ± 2.52 |
| kcen | input-pting | 19.0 ± 1.2 | 18.0 | 31.0 | 16.34 ± 2.65 |
| mattcl-py | input-lanjian | 20.7 ± 0.6 | 19.9 | 23.3 | 17.77 ± 2.70 |
| mattcl-py | input-mattcl | 20.8 ± 0.6 | 19.7 | 23.2 | 17.85 ± 2.70 |
| mattcl-py | input-kcen | 20.8 ± 0.8 | 19.8 | 24.3 | 17.86 ± 2.74 |
| mattcl-py | input-pting | 20.8 ± 0.6 | 19.6 | 23.6 | 17.87 ± 2.71 |
| mattcl-py | input-chancalan | 20.9 ± 0.7 | 19.7 | 24.5 | 17.91 ± 2.74 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.8 | 25.4 | 19.49 ± 2.97 |
| pting | input-kcen | 22.8 ± 0.8 | 21.6 | 27.5 | 19.56 ± 2.99 |
| pting | input-chancalan | 22.9 ± 0.9 | 21.6 | 26.3 | 19.68 ± 3.03 |
| pting | input-mattcl | 22.9 ± 1.6 | 21.4 | 38.0 | 19.68 ± 3.24 |
| pting | input-pting | 23.0 ± 0.6 | 21.9 | 25.3 | 19.75 ± 2.99 |
| chancalan | input-kcen | 25.7 ± 0.6 | 24.7 | 28.4 | 22.08 ± 3.33 |
| chancalan | input-lanjian | 25.8 ± 0.8 | 25.0 | 29.3 | 22.15 ± 3.37 |
| chancalan | input-chancalan | 25.8 ± 0.7 | 24.7 | 28.6 | 22.18 ± 3.36 |
| chancalan | input-mattcl | 25.9 ± 0.9 | 24.9 | 28.9 | 22.25 ± 3.40 |
| chancalan | input-pting | 26.0 ± 0.7 | 25.0 | 28.7 | 22.27 ± 3.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|