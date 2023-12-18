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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.6 | 1.03 ± 0.32 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.36 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.38 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.38 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.20 ± 0.39 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.5 | 18.7 | 17.62 ± 4.12 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.8 | 19.0 | 17.71 ± 4.14 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.6 | 19.1 | 17.77 ± 4.18 |
| mattcl-py | input-lanjian | 16.1 ± 3.1 | 14.7 | 57.6 | 17.93 ± 5.41 |
| pting | input-kcen | 17.0 ± 0.5 | 16.1 | 19.8 | 18.89 ± 4.40 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.6 | 19.8 | 18.92 ± 4.43 |
| pting | input-mattcl | 17.2 ± 0.6 | 16.2 | 19.6 | 19.20 ± 4.48 |
| pting | input-pting | 17.3 ± 0.8 | 16.3 | 20.7 | 19.23 ± 4.52 |
| kcen | input-lanjian | 20.1 ± 0.6 | 19.3 | 23.0 | 22.41 ± 5.21 |
| kcen | input-kcen | 20.1 ± 0.6 | 18.9 | 23.0 | 22.42 ± 5.21 |
| kcen | input-pting | 20.4 ± 0.7 | 19.5 | 23.4 | 22.72 ± 5.30 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.4 | 23.7 | 22.93 ± 5.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|