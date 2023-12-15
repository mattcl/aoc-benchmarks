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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.5 | 1.5 | 1.02 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.4 | 1.02 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.4 | 1.04 ± 0.34 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.7 | 1.14 ± 0.38 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.39 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.7 | 1.16 ± 0.39 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.39 |
| mattcl-py | input-kcen | 15.5 ± 0.7 | 14.7 | 19.2 | 17.81 ± 4.39 |
| mattcl-py | input-mattcl | 15.6 ± 0.6 | 14.6 | 18.3 | 17.91 ± 4.41 |
| mattcl-py | input-lanjian | 15.7 ± 0.7 | 14.8 | 19.1 | 17.93 ± 4.44 |
| mattcl-py | input-pting | 15.7 ± 0.7 | 14.5 | 18.8 | 18.00 ± 4.45 |
| pting | input-lanjian | 16.7 ± 0.7 | 15.9 | 20.4 | 19.14 ± 4.73 |
| pting | input-pting | 16.8 ± 0.6 | 15.7 | 19.4 | 19.22 ± 4.72 |
| pting | input-kcen | 16.8 ± 0.7 | 15.9 | 19.8 | 19.30 ± 4.77 |
| pting | input-mattcl | 16.9 ± 0.6 | 15.7 | 19.9 | 19.35 ± 4.76 |
| kcen | input-kcen | 20.0 ± 0.7 | 18.9 | 23.3 | 22.89 ± 5.62 |
| kcen | input-lanjian | 20.0 ± 0.7 | 19.2 | 22.9 | 22.95 ± 5.63 |
| kcen | input-pting | 20.1 ± 0.6 | 19.0 | 22.8 | 23.04 ± 5.64 |
| kcen | input-mattcl | 20.2 ± 0.5 | 19.4 | 22.2 | 23.09 ± 5.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|