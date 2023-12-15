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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.31 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 2.7 | 1.17 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.20 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.20 ± 0.36 |
| lanjian | input-kcen | 2.3 ± 4.8 | 0.7 | 31.5 | 2.52 ± 5.37 |
| mattcl | input-lanjian | 3.2 ± 6.4 | 0.6 | 42.1 | 3.62 ± 7.21 |
| mattcl-py | input-lanjian | 15.9 ± 0.5 | 14.9 | 17.7 | 17.71 ± 3.72 |
| mattcl-py | input-kcen | 16.0 ± 0.5 | 15.0 | 18.5 | 17.90 ± 3.76 |
| mattcl-py | input-mattcl | 17.1 ± 2.8 | 14.8 | 25.5 | 19.07 ± 5.04 |
| pting | input-kcen | 17.1 ± 0.5 | 16.0 | 19.9 | 19.08 ± 4.01 |
| pting | input-mattcl | 17.3 ± 0.5 | 16.2 | 20.0 | 19.30 ± 4.05 |
| pting | input-lanjian | 17.4 ± 2.4 | 16.2 | 48.1 | 19.36 ± 4.84 |
| kcen | input-lanjian | 20.4 ± 0.5 | 19.7 | 22.6 | 22.72 ± 4.75 |
| kcen | input-pting | 20.6 ± 0.6 | 19.6 | 23.2 | 23.00 ± 4.83 |
| kcen | input-mattcl | 20.6 ± 0.5 | 19.5 | 23.1 | 23.03 ± 4.82 |
| kcen | input-kcen | 21.1 ± 3.0 | 19.5 | 34.2 | 23.51 ± 5.91 |
| mattcl-py | input-pting | 22.8 ± 3.6 | 15.3 | 28.7 | 25.46 ± 6.67 |
| pting | input-pting | 28.3 ± 1.4 | 19.7 | 29.6 | 31.55 ± 6.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|