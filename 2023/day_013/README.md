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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.5 | 1.4 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.5 | 1.3 | 1.00 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.5 | 1.01 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.5 | 1.4 | 1.05 ± 0.36 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.38 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.20 ± 0.40 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.21 ± 0.40 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.22 ± 0.40 |
| mattcl-py | input-kcen | 15.5 ± 0.5 | 14.6 | 18.1 | 18.34 ± 4.45 |
| mattcl-py | input-lanjian | 15.6 ± 0.6 | 14.5 | 18.2 | 18.46 ± 4.49 |
| mattcl-py | input-mattcl | 15.7 ± 0.7 | 14.8 | 18.6 | 18.57 ± 4.52 |
| mattcl-py | input-pting | 15.7 ± 0.7 | 14.8 | 18.8 | 18.59 ± 4.55 |
| pting | input-lanjian | 16.6 ± 0.4 | 15.9 | 18.6 | 19.58 ± 4.72 |
| pting | input-kcen | 16.8 ± 0.7 | 15.8 | 20.1 | 19.82 ± 4.84 |
| pting | input-pting | 16.9 ± 0.7 | 15.8 | 19.9 | 19.92 ± 4.85 |
| pting | input-mattcl | 16.9 ± 0.7 | 15.9 | 20.5 | 20.03 ± 4.88 |
| kcen | input-kcen | 20.1 ± 0.8 | 18.8 | 23.2 | 23.73 ± 5.78 |
| kcen | input-lanjian | 20.1 ± 0.8 | 18.8 | 23.4 | 23.75 ± 5.78 |
| kcen | input-pting | 20.2 ± 0.6 | 19.4 | 22.5 | 23.92 ± 5.79 |
| kcen | input-mattcl | 20.3 ± 0.6 | 19.2 | 23.4 | 24.00 ± 5.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|