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
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.00 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.00 ± 0.31 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.01 ± 0.32 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.30 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.29 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.29 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.29 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.6 | 1.7 | 1.07 ± 0.28 |
| mattcl-py | input-kcen | 15.5 ± 0.7 | 14.4 | 18.5 | 15.07 ± 3.30 |
| mattcl-py | input-lanjian | 15.6 ± 0.7 | 14.6 | 18.9 | 15.19 ± 3.31 |
| mattcl-py | input-pting | 15.7 ± 0.6 | 14.6 | 18.4 | 15.24 ± 3.32 |
| mattcl-py | input-mattcl | 16.0 ± 3.0 | 14.7 | 48.5 | 15.59 ± 4.46 |
| pting | input-kcen | 16.7 ± 0.6 | 15.8 | 19.5 | 16.22 ± 3.53 |
| pting | input-lanjian | 16.7 ± 0.7 | 15.7 | 19.8 | 16.26 ± 3.54 |
| pting | input-pting | 17.0 ± 0.8 | 16.1 | 20.1 | 16.50 ± 3.61 |
| pting | input-mattcl | 17.1 ± 0.9 | 15.8 | 20.9 | 16.61 ± 3.65 |
| kcen | input-lanjian | 19.9 ± 0.6 | 18.6 | 22.8 | 19.40 ± 4.20 |
| kcen | input-kcen | 20.0 ± 0.8 | 18.8 | 23.0 | 19.47 ± 4.24 |
| kcen | input-pting | 20.1 ± 0.6 | 19.1 | 23.1 | 19.52 ± 4.23 |
| kcen | input-mattcl | 20.3 ± 0.8 | 19.4 | 24.0 | 19.74 ± 4.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|