# Day 13 benchmarks

[link to problem](https://adventofcode.com/2023/day/13)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 13)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.1 ± 0.2 | 0.8 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.7 | 1.03 ± 0.27 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.7 | 1.05 ± 0.28 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.7 | 1.07 ± 0.28 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.12 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.13 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.9 | 1.8 | 1.14 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 1.8 | 1.14 ± 0.29 |
| mattcl-py | input-lanjian | 16.0 ± 0.6 | 15.2 | 18.9 | 14.21 ± 2.72 |
| mattcl-py | input-mattcl | 16.0 ± 0.5 | 14.8 | 19.1 | 14.23 ± 2.72 |
| mattcl-py | input-kcen | 16.0 ± 0.6 | 15.1 | 18.2 | 14.26 ± 2.73 |
| mattcl-py | input-pting | 16.2 ± 0.7 | 15.0 | 19.0 | 14.39 ± 2.77 |
| pting | input-lanjian | 17.2 ± 0.8 | 16.1 | 20.2 | 15.30 ± 2.96 |
| pting | input-kcen | 17.3 ± 0.7 | 16.1 | 20.5 | 15.34 ± 2.96 |
| pting | input-pting | 17.3 ± 0.6 | 16.3 | 20.7 | 15.37 ± 2.95 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.4 | 20.9 | 15.43 ± 2.97 |
| kcen | input-lanjian | 20.2 ± 0.6 | 19.1 | 23.6 | 17.99 ± 3.43 |
| kcen | input-pting | 20.5 ± 0.6 | 19.5 | 23.8 | 18.26 ± 3.48 |
| kcen | input-kcen | 20.6 ± 2.4 | 19.3 | 48.4 | 18.33 ± 4.08 |
| kcen | input-mattcl | 20.8 ± 0.8 | 19.2 | 23.3 | 18.49 ± 3.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|