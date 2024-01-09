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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.35 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.38 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.6 | 1.15 ± 0.39 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.38 |
| mattcl | input-lanjian | 1.1 ± 3.2 | 0.6 | 46.3 | 1.23 ± 3.50 |
| lanjian | input-mattcl | 1.3 ± 3.8 | 0.7 | 55.2 | 1.43 ± 4.17 |
| mattcl-py | input-kcen | 15.7 ± 0.5 | 14.7 | 18.6 | 16.97 ± 4.18 |
| mattcl-py | input-lanjian | 15.8 ± 0.5 | 14.8 | 18.3 | 17.14 ± 4.22 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.8 | 18.8 | 17.18 ± 4.24 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 14.7 | 19.3 | 17.19 ± 4.27 |
| pting | input-lanjian | 16.8 ± 0.6 | 15.7 | 19.8 | 18.23 ± 4.49 |
| pting | input-kcen | 16.9 ± 0.7 | 15.6 | 19.8 | 18.31 ± 4.52 |
| pting | input-pting | 17.1 ± 0.8 | 16.0 | 20.0 | 18.54 ± 4.60 |
| pting | input-mattcl | 17.2 ± 0.7 | 16.0 | 19.9 | 18.67 ± 4.63 |
| kcen | input-lanjian | 20.2 ± 0.6 | 18.9 | 22.6 | 21.85 ± 5.38 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.1 | 23.4 | 21.94 ± 5.42 |
| kcen | input-pting | 20.4 ± 0.6 | 19.2 | 23.1 | 22.06 ± 5.43 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.5 | 23.3 | 22.22 ± 5.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|