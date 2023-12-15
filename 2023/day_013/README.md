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
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.27 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.28 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.15 ± 0.32 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.8 | 1.8 | 1.17 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.19 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.19 ± 0.33 |
| mattcl-py | input-kcen | 15.9 ± 0.6 | 15.1 | 19.2 | 15.37 ± 2.96 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 14.7 | 19.6 | 15.53 ± 3.01 |
| mattcl-py | input-mattcl | 16.1 ± 0.6 | 15.0 | 18.7 | 15.54 ± 2.99 |
| mattcl-py | input-lanjian | 16.2 ± 2.6 | 15.2 | 50.2 | 15.69 ± 3.88 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.3 | 20.6 | 16.62 ± 3.21 |
| pting | input-kcen | 17.2 ± 0.8 | 15.9 | 20.2 | 16.65 ± 3.23 |
| pting | input-pting | 17.2 ± 0.7 | 16.2 | 20.7 | 16.67 ± 3.22 |
| pting | input-mattcl | 17.4 ± 0.8 | 16.5 | 21.1 | 16.84 ± 3.26 |
| kcen | input-kcen | 20.5 ± 1.7 | 19.2 | 38.5 | 19.82 ± 4.07 |
| kcen | input-pting | 20.7 ± 0.8 | 19.1 | 24.0 | 20.03 ± 3.87 |
| kcen | input-mattcl | 20.7 ± 0.8 | 19.7 | 24.4 | 20.05 ± 3.86 |
| kcen | input-lanjian | 21.3 ± 4.1 | 18.9 | 67.5 | 20.65 ± 5.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|