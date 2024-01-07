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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.33 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.06 ± 0.34 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 2.4 | 1.07 ± 0.36 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.16 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.38 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.9 | 18.7 | 16.90 ± 3.90 |
| mattcl-py | input-mattcl | 15.9 ± 0.5 | 14.8 | 18.5 | 16.93 ± 3.90 |
| mattcl-py | input-kcen | 15.9 ± 0.8 | 14.7 | 18.9 | 16.98 ± 3.96 |
| mattcl-py | input-lanjian | 16.0 ± 0.8 | 15.0 | 19.4 | 17.07 ± 3.99 |
| pting | input-lanjian | 17.1 ± 0.6 | 16.2 | 20.3 | 18.20 ± 4.20 |
| pting | input-kcen | 17.1 ± 0.8 | 15.8 | 20.3 | 18.22 ± 4.23 |
| pting | input-pting | 17.1 ± 0.6 | 15.8 | 19.7 | 18.24 ± 4.21 |
| pting | input-mattcl | 17.2 ± 0.7 | 16.1 | 20.6 | 18.34 ± 4.25 |
| kcen | input-kcen | 20.2 ± 0.7 | 18.7 | 23.2 | 21.58 ± 4.99 |
| kcen | input-lanjian | 20.3 ± 0.7 | 18.9 | 23.8 | 21.60 ± 4.99 |
| kcen | input-pting | 20.5 ± 0.7 | 19.3 | 23.3 | 21.83 ± 5.04 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.5 | 23.8 | 21.92 ± 5.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|