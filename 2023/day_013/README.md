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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.4 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.32 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.36 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.37 |
| lanjian | input-pting | 1.3 ± 3.0 | 0.7 | 43.0 | 1.37 ± 3.18 |
| mattcl-py | input-kcen | 15.9 ± 0.6 | 14.9 | 18.7 | 16.86 ± 3.80 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.6 | 19.0 | 16.92 ± 3.83 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.8 | 19.3 | 16.93 ± 3.80 |
| mattcl-py | input-pting | 16.3 ± 3.3 | 15.0 | 48.1 | 17.35 ± 5.20 |
| pting | input-lanjian | 16.9 ± 0.5 | 15.7 | 20.4 | 17.97 ± 4.02 |
| pting | input-kcen | 17.0 ± 0.7 | 15.9 | 21.0 | 18.10 ± 4.08 |
| pting | input-pting | 17.1 ± 0.7 | 15.7 | 20.6 | 18.16 ± 4.09 |
| pting | input-mattcl | 17.5 ± 2.8 | 15.8 | 52.8 | 18.59 ± 5.08 |
| kcen | input-lanjian | 20.2 ± 0.7 | 19.0 | 22.8 | 21.51 ± 4.83 |
| kcen | input-kcen | 20.4 ± 0.9 | 18.7 | 23.8 | 21.64 ± 4.88 |
| kcen | input-mattcl | 20.5 ± 0.8 | 19.5 | 23.9 | 21.83 ± 4.91 |
| kcen | input-pting | 20.8 ± 2.1 | 19.4 | 44.0 | 22.08 ± 5.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|