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
| mattcl | input-pting | 0.8 ± 0.2 | 0.5 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.4 | 1.03 ± 0.36 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.5 | 1.4 | 1.03 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.4 | 1.07 ± 0.38 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.6 | 1.6 | 1.13 ± 0.40 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.7 | 1.16 ± 0.41 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.16 ± 0.41 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.19 ± 0.41 |
| mattcl-py | input-kcen | 15.4 ± 0.6 | 14.4 | 18.2 | 18.35 ± 4.74 |
| mattcl-py | input-lanjian | 15.4 ± 0.6 | 14.5 | 17.9 | 18.37 ± 4.73 |
| mattcl-py | input-pting | 15.5 ± 0.6 | 14.5 | 18.3 | 18.50 ± 4.77 |
| mattcl-py | input-mattcl | 15.9 ± 2.7 | 14.3 | 51.1 | 18.95 ± 5.82 |
| pting | input-lanjian | 16.6 ± 0.6 | 15.7 | 19.9 | 19.82 ± 5.10 |
| pting | input-kcen | 16.8 ± 0.7 | 15.9 | 19.9 | 20.06 ± 5.18 |
| pting | input-pting | 16.9 ± 0.7 | 15.6 | 20.5 | 20.14 ± 5.20 |
| pting | input-mattcl | 17.0 ± 0.7 | 15.8 | 19.7 | 20.24 ± 5.22 |
| kcen | input-lanjian | 19.8 ± 0.7 | 18.7 | 22.3 | 23.64 ± 6.08 |
| kcen | input-kcen | 19.8 ± 0.5 | 19.1 | 23.0 | 23.66 ± 6.06 |
| kcen | input-pting | 20.0 ± 0.7 | 18.9 | 22.9 | 23.82 ± 6.13 |
| kcen | input-mattcl | 20.2 ± 0.7 | 18.9 | 22.9 | 24.05 ± 6.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|