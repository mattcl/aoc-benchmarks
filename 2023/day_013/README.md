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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.34 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.6 | 1.03 ± 0.35 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.16 ± 0.38 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.39 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.37 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.7 | 1.17 ± 0.39 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.7 | 19.0 | 18.09 ± 4.26 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.7 | 19.0 | 18.18 ± 4.30 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.6 | 18.9 | 18.30 ± 4.31 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 14.6 | 18.7 | 18.40 ± 4.34 |
| pting | input-kcen | 17.3 ± 0.7 | 16.2 | 20.4 | 19.86 ± 4.68 |
| pting | input-lanjian | 17.3 ± 0.8 | 16.3 | 20.5 | 19.87 ± 4.70 |
| pting | input-pting | 17.4 ± 0.6 | 16.2 | 20.3 | 20.03 ± 4.71 |
| pting | input-mattcl | 17.5 ± 0.8 | 16.4 | 20.6 | 20.17 ± 4.77 |
| kcen | input-lanjian | 20.7 ± 0.8 | 19.0 | 23.7 | 23.80 ± 5.61 |
| kcen | input-kcen | 20.7 ± 0.8 | 19.7 | 24.2 | 23.87 ± 5.62 |
| kcen | input-pting | 21.0 ± 0.9 | 19.8 | 24.1 | 24.15 ± 5.71 |
| kcen | input-mattcl | 21.1 ± 0.8 | 19.8 | 23.7 | 24.28 ± 5.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|