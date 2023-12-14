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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.4 | 0.6 | 4.1 | 1.10 ± 0.49 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.3 | 0.7 | 1.7 | 1.22 ± 0.38 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.8 | 18.4 | 17.13 ± 3.72 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.7 | 19.4 | 17.28 ± 3.77 |
| mattcl-py | input-lanjian | 16.0 ± 0.7 | 14.6 | 19.4 | 17.36 ± 3.80 |
| mattcl-py | input-pting | 16.1 ± 0.7 | 14.6 | 19.1 | 17.42 ± 3.81 |
| pting | input-lanjian | 16.9 ± 0.7 | 15.5 | 20.6 | 18.36 ± 3.99 |
| pting | input-kcen | 17.1 ± 0.7 | 16.0 | 20.7 | 18.54 ± 4.05 |
| pting | input-mattcl | 17.2 ± 0.7 | 16.2 | 20.8 | 18.68 ± 4.06 |
| pting | input-pting | 17.3 ± 0.8 | 16.3 | 20.8 | 18.75 ± 4.10 |
| kcen | input-kcen | 20.1 ± 0.5 | 19.1 | 23.1 | 21.83 ± 4.71 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.1 | 22.8 | 22.00 ± 4.77 |
| kcen | input-pting | 20.5 ± 0.8 | 19.5 | 23.5 | 22.26 ± 4.83 |
| kcen | input-mattcl | 20.7 ± 0.9 | 19.4 | 24.2 | 22.42 ± 4.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|