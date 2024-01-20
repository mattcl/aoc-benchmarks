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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.4 | 1.01 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.35 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.37 |
| lanjian | input-lanjian | 1.0 ± 0.3 | 0.7 | 1.8 | 1.16 ± 0.39 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.39 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.7 | 1.22 ± 0.42 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.7 | 18.6 | 17.62 ± 4.16 |
| mattcl-py | input-lanjian | 15.8 ± 0.7 | 14.8 | 19.2 | 17.72 ± 4.20 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 14.7 | 19.0 | 17.79 ± 4.21 |
| mattcl-py | input-mattcl | 16.0 ± 0.8 | 14.7 | 18.6 | 17.87 ± 4.25 |
| pting | input-lanjian | 16.8 ± 0.7 | 15.4 | 20.1 | 18.83 ± 4.45 |
| pting | input-kcen | 17.1 ± 0.8 | 16.0 | 20.0 | 19.08 ± 4.52 |
| pting | input-pting | 17.1 ± 0.7 | 15.8 | 20.2 | 19.12 ± 4.53 |
| pting | input-mattcl | 17.1 ± 0.6 | 16.2 | 19.9 | 19.14 ± 4.50 |
| kcen | input-lanjian | 20.1 ± 0.7 | 18.6 | 23.7 | 22.50 ± 5.30 |
| kcen | input-kcen | 20.1 ± 0.5 | 18.9 | 22.7 | 22.50 ± 5.27 |
| kcen | input-pting | 20.3 ± 0.8 | 18.8 | 23.8 | 22.75 ± 5.36 |
| kcen | input-mattcl | 20.4 ± 0.8 | 19.4 | 23.7 | 22.86 ± 5.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|