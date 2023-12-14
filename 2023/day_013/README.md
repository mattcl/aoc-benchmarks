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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.5 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.5 | 1.4 | 1.00 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.4 | 1.03 ± 0.36 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.5 | 1.5 | 1.05 ± 0.37 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.18 ± 0.40 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.19 ± 0.40 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.20 ± 0.40 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.21 ± 0.40 |
| mattcl-py | input-mattcl | 15.5 ± 0.5 | 14.6 | 18.3 | 18.59 ± 4.62 |
| mattcl-py | input-kcen | 15.5 ± 0.7 | 14.6 | 18.6 | 18.61 ± 4.65 |
| mattcl-py | input-lanjian | 15.6 ± 0.6 | 14.6 | 18.2 | 18.65 ± 4.66 |
| mattcl-py | input-pting | 15.6 ± 0.7 | 14.8 | 19.3 | 18.70 ± 4.68 |
| pting | input-lanjian | 16.6 ± 0.7 | 15.7 | 19.5 | 19.93 ± 4.98 |
| pting | input-pting | 16.7 ± 0.6 | 15.8 | 19.5 | 20.07 ± 5.00 |
| pting | input-kcen | 16.8 ± 0.8 | 15.6 | 19.8 | 20.13 ± 5.05 |
| pting | input-mattcl | 16.8 ± 0.6 | 16.0 | 19.8 | 20.17 ± 5.03 |
| kcen | input-kcen | 20.0 ± 0.7 | 18.8 | 22.9 | 23.99 ± 5.97 |
| kcen | input-pting | 20.0 ± 0.6 | 19.0 | 22.6 | 24.00 ± 5.96 |
| kcen | input-lanjian | 20.1 ± 1.6 | 18.9 | 37.2 | 24.13 ± 6.24 |
| kcen | input-mattcl | 20.1 ± 0.7 | 19.3 | 22.7 | 24.16 ± 6.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|