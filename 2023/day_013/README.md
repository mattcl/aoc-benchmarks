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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.32 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.08 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.10 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.7 | 1.15 ± 0.38 |
| mattcl-py | input-lanjian | 15.5 ± 0.7 | 14.5 | 19.1 | 16.40 ± 3.82 |
| mattcl-py | input-pting | 15.6 ± 0.7 | 14.6 | 18.8 | 16.50 ± 3.85 |
| mattcl-py | input-mattcl | 15.6 ± 0.6 | 14.8 | 18.5 | 16.51 ± 3.83 |
| mattcl-py | input-kcen | 15.6 ± 2.5 | 14.5 | 48.4 | 16.53 ± 4.64 |
| pting | input-kcen | 16.6 ± 0.7 | 15.8 | 19.9 | 17.56 ± 4.09 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.7 | 19.8 | 17.66 ± 4.10 |
| pting | input-mattcl | 16.8 ± 0.7 | 15.9 | 20.5 | 17.76 ± 4.14 |
| pting | input-pting | 16.9 ± 0.7 | 15.7 | 19.9 | 17.84 ± 4.16 |
| kcen | input-lanjian | 19.9 ± 0.7 | 19.0 | 22.6 | 21.07 ± 4.88 |
| kcen | input-pting | 20.1 ± 0.7 | 19.4 | 23.4 | 21.23 ± 4.91 |
| kcen | input-mattcl | 20.2 ± 0.8 | 18.8 | 23.0 | 21.39 ± 4.97 |
| kcen | input-kcen | 20.6 ± 4.4 | 18.7 | 63.9 | 21.74 ± 6.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|