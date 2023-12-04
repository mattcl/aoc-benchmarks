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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.03 ± 0.25 |
| mattcl | input-kcen | 1.3 ± 0.1 | 1.0 | 1.8 | 1.09 ± 0.22 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.0 | 1.09 ± 0.25 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 0.5 | 2.2 | 1.40 ± 0.32 |
| lanjian | input-pting | 1.7 ± 0.3 | 0.9 | 2.2 | 1.41 ± 0.33 |
| lanjian | input-chancalan | 1.7 ± 0.3 | 0.7 | 2.4 | 1.44 ± 0.33 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 0.8 | 2.1 | 1.47 ± 0.30 |
| lanjian | input-kcen | 1.8 ± 0.2 | 1.0 | 2.3 | 1.48 ± 0.31 |
| kcen | input-lanjian | 19.0 ± 0.7 | 18.0 | 22.2 | 15.90 ± 2.86 |
| kcen | input-chancalan | 19.0 ± 0.8 | 18.0 | 22.4 | 15.96 ± 2.89 |
| kcen | input-mattcl | 19.2 ± 0.8 | 18.3 | 22.6 | 16.09 ± 2.91 |
| kcen | input-pting | 19.3 ± 0.6 | 18.4 | 22.1 | 16.17 ± 2.90 |
| kcen | input-kcen | 19.7 ± 4.3 | 18.2 | 52.8 | 16.55 ± 4.62 |
| mattcl-py | input-chancalan | 21.0 ± 0.5 | 20.3 | 23.4 | 17.61 ± 3.13 |
| mattcl-py | input-lanjian | 21.1 ± 0.7 | 20.2 | 24.6 | 17.68 ± 3.18 |
| mattcl-py | input-mattcl | 21.1 ± 0.5 | 20.3 | 23.7 | 17.73 ± 3.15 |
| mattcl-py | input-pting | 21.3 ± 0.7 | 20.4 | 24.3 | 17.87 ± 3.21 |
| mattcl-py | input-kcen | 21.5 ± 3.3 | 20.1 | 59.0 | 18.00 ± 4.19 |
| pting | input-chancalan | 23.1 ± 0.7 | 22.2 | 26.2 | 19.40 ± 3.47 |
| pting | input-kcen | 23.1 ± 0.8 | 21.9 | 26.0 | 19.40 ± 3.48 |
| pting | input-mattcl | 23.4 ± 0.9 | 22.4 | 26.4 | 19.60 ± 3.54 |
| pting | input-lanjian | 23.5 ± 1.1 | 22.4 | 29.3 | 19.69 ± 3.58 |
| pting | input-pting | 23.5 ± 0.8 | 22.5 | 26.8 | 19.73 ± 3.54 |
| chancalan | input-kcen | 26.0 ± 0.8 | 24.9 | 28.6 | 21.77 ± 3.90 |
| chancalan | input-lanjian | 26.1 ± 0.8 | 24.7 | 29.3 | 21.86 ± 3.91 |
| chancalan | input-chancalan | 26.3 ± 1.1 | 25.0 | 30.2 | 22.01 ± 3.99 |
| chancalan | input-mattcl | 26.4 ± 1.1 | 25.1 | 29.8 | 22.09 ± 3.99 |
| chancalan | input-pting | 26.4 ± 0.9 | 25.4 | 29.6 | 22.12 ± 3.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|