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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.33 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.10 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.37 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.36 |
| mattcl-py | input-lanjian | 15.7 ± 0.5 | 14.9 | 18.0 | 16.63 ± 3.78 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.8 | 18.5 | 16.67 ± 3.80 |
| mattcl-py | input-mattcl | 15.8 ± 0.7 | 15.0 | 19.4 | 16.71 ± 3.83 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 14.9 | 19.0 | 16.77 ± 3.85 |
| pting | input-lanjian | 16.9 ± 0.7 | 15.8 | 20.5 | 17.81 ± 4.06 |
| pting | input-kcen | 17.0 ± 0.6 | 15.9 | 19.7 | 17.92 ± 4.08 |
| pting | input-pting | 17.1 ± 0.7 | 15.9 | 20.7 | 18.01 ± 4.12 |
| pting | input-mattcl | 17.1 ± 0.6 | 16.1 | 20.1 | 18.02 ± 4.10 |
| kcen | input-lanjian | 20.2 ± 0.7 | 19.1 | 23.7 | 21.33 ± 4.85 |
| kcen | input-pting | 20.4 ± 0.7 | 19.1 | 23.1 | 21.57 ± 4.90 |
| kcen | input-kcen | 20.4 ± 1.9 | 18.8 | 40.8 | 21.57 ± 5.24 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.5 | 23.3 | 21.82 ± 4.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|