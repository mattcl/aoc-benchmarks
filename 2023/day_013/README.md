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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.6 | 1.02 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.32 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.4 | 1.05 ± 0.31 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.35 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.15 ± 0.37 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.7 | 18.7 | 17.19 ± 3.76 |
| mattcl-py | input-lanjian | 15.8 ± 0.6 | 14.8 | 19.3 | 17.19 ± 3.74 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.7 | 18.9 | 17.22 ± 3.75 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.8 | 18.5 | 17.23 ± 3.75 |
| pting | input-pting | 17.0 ± 0.7 | 16.0 | 20.4 | 18.47 ± 4.02 |
| pting | input-lanjian | 17.0 ± 0.8 | 15.6 | 20.1 | 18.49 ± 4.05 |
| pting | input-mattcl | 17.2 ± 0.8 | 16.2 | 20.5 | 18.64 ± 4.08 |
| pting | input-kcen | 17.4 ± 4.2 | 15.9 | 64.0 | 18.92 ± 6.12 |
| kcen | input-kcen | 20.2 ± 0.6 | 18.8 | 22.5 | 21.93 ± 4.75 |
| kcen | input-lanjian | 20.3 ± 0.8 | 19.2 | 23.4 | 21.97 ± 4.78 |
| kcen | input-pting | 20.5 ± 0.7 | 19.2 | 23.0 | 22.21 ± 4.82 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.4 | 23.5 | 22.36 ± 4.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|