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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.5 | 1.3 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.5 | 1.4 | 1.01 ± 0.37 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.5 | 1.04 ± 0.38 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.13 ± 0.39 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.17 ± 0.43 |
| mattcl | input-pting | 1.0 ± 3.3 | 0.5 | 47.2 | 1.19 ± 4.02 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.21 ± 0.42 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.21 ± 0.43 |
| mattcl-py | input-kcen | 15.5 ± 0.5 | 14.3 | 18.3 | 18.88 ± 4.91 |
| mattcl-py | input-mattcl | 15.7 ± 0.7 | 14.7 | 18.9 | 19.18 ± 5.01 |
| mattcl-py | input-pting | 15.8 ± 0.8 | 14.6 | 19.0 | 19.23 ± 5.06 |
| mattcl-py | input-lanjian | 15.9 ± 3.1 | 14.7 | 56.5 | 19.43 ± 6.26 |
| pting | input-kcen | 16.6 ± 0.6 | 15.5 | 19.7 | 20.31 ± 5.28 |
| pting | input-lanjian | 16.7 ± 0.7 | 15.6 | 19.8 | 20.32 ± 5.30 |
| pting | input-mattcl | 16.8 ± 0.7 | 15.8 | 20.4 | 20.54 ± 5.35 |
| pting | input-pting | 16.9 ± 0.7 | 15.7 | 20.2 | 20.60 ± 5.38 |
| kcen | input-kcen | 19.9 ± 0.5 | 19.0 | 22.6 | 24.23 ± 6.27 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.6 | 22.8 | 24.37 ± 6.34 |
| kcen | input-mattcl | 20.2 ± 0.6 | 19.4 | 22.8 | 24.69 ± 6.40 |
| kcen | input-pting | 20.4 ± 1.7 | 19.0 | 38.2 | 24.91 ± 6.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|