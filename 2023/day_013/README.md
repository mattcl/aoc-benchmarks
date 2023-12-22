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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.5 | 1.05 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.05 ± 0.32 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.17 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.37 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.8 | 19.2 | 16.76 ± 3.81 |
| mattcl-py | input-kcen | 15.9 ± 0.6 | 14.8 | 18.5 | 16.80 ± 3.80 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.9 | 18.9 | 16.83 ± 3.80 |
| mattcl-py | input-pting | 16.0 ± 0.8 | 14.6 | 19.2 | 16.92 ± 3.85 |
| pting | input-lanjian | 17.0 ± 0.5 | 15.9 | 19.4 | 17.93 ± 4.03 |
| pting | input-kcen | 17.1 ± 0.8 | 15.6 | 20.1 | 18.13 ± 4.13 |
| pting | input-mattcl | 17.3 ± 0.8 | 16.1 | 20.4 | 18.28 ± 4.15 |
| pting | input-pting | 17.6 ± 3.8 | 15.9 | 66.7 | 18.60 ± 5.76 |
| kcen | input-kcen | 20.3 ± 0.6 | 19.3 | 22.6 | 21.42 ± 4.82 |
| kcen | input-lanjian | 20.3 ± 0.8 | 19.3 | 22.9 | 21.48 ± 4.85 |
| kcen | input-pting | 20.5 ± 0.7 | 19.6 | 22.8 | 21.72 ± 4.89 |
| kcen | input-mattcl | 20.7 ± 0.8 | 19.4 | 23.9 | 21.85 ± 4.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|