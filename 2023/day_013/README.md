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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.34 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.36 |
| mattcl-py | input-kcen | 15.5 ± 0.6 | 14.5 | 18.4 | 16.72 ± 3.72 |
| mattcl-py | input-mattcl | 15.6 ± 0.7 | 14.6 | 18.6 | 16.87 ± 3.77 |
| mattcl-py | input-lanjian | 15.6 ± 0.7 | 14.3 | 18.5 | 16.90 ± 3.77 |
| mattcl-py | input-pting | 15.6 ± 0.6 | 14.7 | 18.4 | 16.91 ± 3.76 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.8 | 19.0 | 18.00 ± 3.99 |
| pting | input-kcen | 16.7 ± 0.6 | 15.7 | 19.7 | 18.06 ± 4.02 |
| pting | input-pting | 16.9 ± 0.6 | 16.2 | 19.6 | 18.25 ± 4.05 |
| pting | input-mattcl | 16.9 ± 0.7 | 15.6 | 20.2 | 18.26 ± 4.07 |
| kcen | input-kcen | 20.0 ± 0.6 | 18.8 | 22.8 | 21.59 ± 4.78 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.8 | 22.8 | 21.61 ± 4.80 |
| kcen | input-pting | 20.1 ± 0.7 | 19.0 | 23.2 | 21.77 ± 4.82 |
| kcen | input-mattcl | 20.1 ± 0.6 | 19.3 | 23.4 | 21.77 ± 4.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|