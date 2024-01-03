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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.33 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.10 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.8 | 1.14 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.8 | 1.14 ± 0.37 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.36 |
| mattcl-py | input-lanjian | 15.8 ± 0.5 | 15.0 | 18.8 | 16.31 ± 3.68 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.4 | 18.5 | 16.32 ± 3.69 |
| mattcl-py | input-mattcl | 15.8 ± 0.6 | 14.5 | 18.8 | 16.39 ± 3.71 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 14.9 | 19.1 | 16.57 ± 3.77 |
| pting | input-lanjian | 17.0 ± 0.7 | 16.1 | 19.8 | 17.62 ± 3.99 |
| pting | input-kcen | 17.0 ± 0.7 | 15.9 | 20.1 | 17.63 ± 4.00 |
| pting | input-mattcl | 17.1 ± 0.7 | 15.8 | 20.4 | 17.67 ± 4.01 |
| pting | input-pting | 17.2 ± 0.9 | 16.1 | 20.4 | 17.84 ± 4.07 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.2 | 22.7 | 20.86 ± 4.69 |
| kcen | input-lanjian | 20.2 ± 0.8 | 19.3 | 23.6 | 20.95 ± 4.74 |
| kcen | input-pting | 20.5 ± 0.8 | 19.3 | 23.5 | 21.16 ± 4.78 |
| kcen | input-mattcl | 20.5 ± 0.6 | 19.3 | 22.7 | 21.20 ± 4.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|