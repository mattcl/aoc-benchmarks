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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.8 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.6 | 1.6 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.6 | 1.5 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.26 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.9 | 1.05 ± 0.27 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.8 | 2.2 | 1.39 ± 0.36 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.7 | 2.2 | 1.40 ± 0.37 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.9 | 2.2 | 1.48 ± 0.37 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.8 | 2.2 | 1.49 ± 0.37 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.8 | 2.2 | 1.54 ± 0.37 |
| kcen | input-pting | 18.6 ± 0.6 | 17.7 | 21.8 | 17.33 ± 3.50 |
| kcen | input-mattcl | 18.7 ± 0.6 | 17.8 | 21.5 | 17.37 ± 3.51 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.7 | 21.6 | 17.41 ± 3.53 |
| kcen | input-kcen | 18.8 ± 0.8 | 18.0 | 21.9 | 17.47 ± 3.57 |
| kcen | input-chancalan | 18.8 ± 1.3 | 17.8 | 33.3 | 17.49 ± 3.70 |
| mattcl-py | input-kcen | 20.8 ± 0.6 | 19.9 | 24.3 | 19.35 ± 3.91 |
| mattcl-py | input-mattcl | 20.8 ± 0.7 | 19.6 | 23.8 | 19.36 ± 3.92 |
| mattcl-py | input-pting | 20.9 ± 0.6 | 20.0 | 24.2 | 19.42 ± 3.92 |
| mattcl-py | input-lanjian | 20.9 ± 0.7 | 19.8 | 23.5 | 19.45 ± 3.95 |
| mattcl-py | input-chancalan | 21.0 ± 0.8 | 20.1 | 24.3 | 19.49 ± 3.97 |
| pting | input-mattcl | 22.7 ± 0.7 | 21.7 | 26.2 | 21.15 ± 4.28 |
| pting | input-kcen | 22.8 ± 0.6 | 22.0 | 25.7 | 21.18 ± 4.27 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.7 | 25.4 | 21.23 ± 4.30 |
| pting | input-chancalan | 22.9 ± 0.9 | 21.5 | 26.5 | 21.30 ± 4.33 |
| pting | input-pting | 23.1 ± 0.7 | 22.0 | 26.0 | 21.47 ± 4.35 |
| chancalan | input-mattcl | 25.8 ± 0.8 | 24.7 | 28.9 | 23.99 ± 4.85 |
| chancalan | input-chancalan | 25.8 ± 0.8 | 24.9 | 28.6 | 24.02 ± 4.85 |
| chancalan | input-lanjian | 25.8 ± 0.7 | 24.9 | 28.5 | 24.03 ± 4.84 |
| chancalan | input-kcen | 25.8 ± 0.9 | 24.7 | 28.7 | 24.03 ± 4.87 |
| chancalan | input-pting | 26.0 ± 0.8 | 25.1 | 28.8 | 24.21 ± 4.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|