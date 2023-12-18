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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.4 | 1.04 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.06 ± 0.34 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.37 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.19 ± 0.37 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.19 ± 0.38 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.20 ± 0.38 |
| mattcl-py | input-lanjian | 15.5 ± 0.5 | 14.6 | 18.6 | 17.60 ± 4.06 |
| mattcl-py | input-kcen | 15.5 ± 0.7 | 14.4 | 18.9 | 17.65 ± 4.11 |
| mattcl-py | input-pting | 15.7 ± 0.6 | 14.7 | 18.4 | 17.80 ± 4.12 |
| mattcl-py | input-mattcl | 15.7 ± 0.7 | 14.8 | 18.9 | 17.84 ± 4.16 |
| pting | input-kcen | 16.6 ± 0.6 | 16.0 | 19.8 | 18.91 ± 4.37 |
| pting | input-lanjian | 16.7 ± 0.7 | 15.6 | 20.4 | 19.02 ± 4.41 |
| pting | input-pting | 16.8 ± 0.6 | 15.9 | 19.9 | 19.14 ± 4.42 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.0 | 19.8 | 19.19 ± 4.44 |
| kcen | input-kcen | 19.9 ± 0.7 | 19.0 | 22.9 | 22.62 ± 5.22 |
| kcen | input-lanjian | 19.9 ± 0.8 | 18.6 | 24.5 | 22.63 ± 5.24 |
| kcen | input-pting | 20.1 ± 0.7 | 19.3 | 23.6 | 22.87 ± 5.29 |
| kcen | input-mattcl | 20.1 ± 0.5 | 19.4 | 22.6 | 22.87 ± 5.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|