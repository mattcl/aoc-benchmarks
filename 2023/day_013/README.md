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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.4 | 1.01 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.33 |
| lanjian | input-kcen | 1.1 ± 0.3 | 0.7 | 1.7 | 1.14 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.38 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.19 ± 0.36 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.37 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.7 | 19.2 | 17.08 ± 3.93 |
| mattcl-py | input-lanjian | 15.9 ± 0.6 | 14.7 | 18.8 | 17.14 ± 3.93 |
| mattcl-py | input-pting | 15.9 ± 0.5 | 15.1 | 19.0 | 17.16 ± 3.91 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.9 | 19.5 | 17.19 ± 3.94 |
| pting | input-kcen | 16.9 ± 0.7 | 15.6 | 20.4 | 18.27 ± 4.18 |
| pting | input-lanjian | 17.1 ± 0.8 | 15.8 | 20.4 | 18.46 ± 4.25 |
| pting | input-pting | 17.2 ± 0.6 | 16.1 | 19.8 | 18.51 ± 4.24 |
| pting | input-mattcl | 17.3 ± 0.8 | 16.2 | 20.6 | 18.67 ± 4.31 |
| kcen | input-lanjian | 20.2 ± 0.6 | 19.1 | 23.6 | 21.79 ± 4.96 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.3 | 23.0 | 21.79 ± 4.96 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.1 | 23.5 | 22.20 ± 5.08 |
| kcen | input-pting | 21.3 ± 6.1 | 19.4 | 80.9 | 22.97 ± 8.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|