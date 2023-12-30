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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.00 ± 0.29 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.29 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.10 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.12 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.13 ± 0.31 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.8 | 1.7 | 1.13 ± 0.32 |
| mattcl-py | input-kcen | 15.9 ± 0.7 | 15.0 | 19.0 | 15.32 ± 3.15 |
| mattcl-py | input-lanjian | 16.0 ± 0.7 | 14.9 | 19.5 | 15.35 ± 3.16 |
| mattcl-py | input-mattcl | 16.1 ± 0.8 | 14.7 | 19.6 | 15.45 ± 3.20 |
| mattcl-py | input-pting | 16.2 ± 0.7 | 14.9 | 18.7 | 15.55 ± 3.20 |
| pting | input-lanjian | 17.1 ± 0.6 | 15.9 | 20.3 | 16.40 ± 3.34 |
| pting | input-kcen | 17.2 ± 0.7 | 16.2 | 20.6 | 16.50 ± 3.37 |
| pting | input-pting | 17.3 ± 0.6 | 16.2 | 20.8 | 16.64 ± 3.39 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.5 | 20.6 | 16.74 ± 3.43 |
| kcen | input-lanjian | 20.2 ± 0.6 | 18.9 | 23.4 | 19.40 ± 3.94 |
| kcen | input-kcen | 20.4 ± 0.8 | 19.4 | 23.7 | 19.65 ± 4.01 |
| kcen | input-pting | 20.7 ± 0.7 | 19.6 | 23.6 | 19.90 ± 4.05 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.6 | 23.5 | 19.90 ± 4.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|