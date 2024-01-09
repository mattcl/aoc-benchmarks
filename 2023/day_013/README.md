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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.4 | 1.04 ± 0.35 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.12 ± 0.38 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.38 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.38 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.22 ± 0.41 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.8 | 19.3 | 17.72 ± 4.43 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.8 | 19.1 | 17.76 ± 4.42 |
| mattcl-py | input-pting | 15.9 ± 0.8 | 14.7 | 19.0 | 17.79 ± 4.45 |
| mattcl-py | input-kcen | 16.0 ± 2.0 | 14.6 | 40.7 | 17.84 ± 4.90 |
| pting | input-kcen | 17.0 ± 0.7 | 16.0 | 20.0 | 19.02 ± 4.73 |
| pting | input-pting | 17.2 ± 0.7 | 16.0 | 20.2 | 19.18 ± 4.77 |
| pting | input-mattcl | 17.3 ± 0.8 | 16.2 | 20.6 | 19.28 ± 4.81 |
| pting | input-lanjian | 17.5 ± 3.5 | 15.7 | 46.2 | 19.50 ± 6.21 |
| kcen | input-lanjian | 20.2 ± 0.7 | 18.9 | 23.6 | 22.55 ± 5.61 |
| kcen | input-kcen | 20.4 ± 0.9 | 18.7 | 23.8 | 22.76 ± 5.68 |
| kcen | input-pting | 20.5 ± 0.7 | 19.1 | 23.2 | 22.93 ± 5.69 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.4 | 23.5 | 22.95 ± 5.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|