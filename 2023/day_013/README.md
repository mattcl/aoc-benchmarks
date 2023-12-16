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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.6 | 1.00 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.31 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.6 | 1.17 ± 0.38 |
| mattcl-py | input-kcen | 15.9 ± 0.7 | 14.9 | 19.2 | 16.85 ± 3.82 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 14.8 | 19.0 | 16.86 ± 3.81 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.8 | 18.9 | 16.88 ± 3.82 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 14.9 | 18.9 | 16.97 ± 3.82 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.1 | 20.7 | 18.40 ± 4.15 |
| pting | input-kcen | 17.4 ± 0.7 | 16.2 | 20.9 | 18.43 ± 4.17 |
| pting | input-pting | 17.4 ± 0.7 | 16.4 | 20.5 | 18.44 ± 4.16 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.2 | 20.6 | 18.45 ± 4.17 |
| kcen | input-lanjian | 20.7 ± 0.7 | 19.6 | 23.9 | 21.92 ± 4.93 |
| kcen | input-kcen | 20.8 ± 0.8 | 19.4 | 23.9 | 22.08 ± 4.98 |
| kcen | input-pting | 21.0 ± 0.8 | 20.0 | 24.1 | 22.31 ± 5.03 |
| kcen | input-mattcl | 21.1 ± 0.7 | 19.9 | 24.1 | 22.35 ± 5.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|