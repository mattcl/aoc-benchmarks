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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.33 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.35 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.36 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.36 |
| mattcl-py | input-kcen | 15.5 ± 0.7 | 14.8 | 18.9 | 16.89 ± 3.77 |
| mattcl-py | input-lanjian | 15.6 ± 0.6 | 14.6 | 18.5 | 16.95 ± 3.76 |
| mattcl-py | input-pting | 15.8 ± 2.4 | 14.9 | 46.8 | 17.18 ± 4.56 |
| mattcl-py | input-mattcl | 16.0 ± 3.1 | 14.6 | 46.9 | 17.44 ± 5.07 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.7 | 20.3 | 18.13 ± 4.02 |
| pting | input-kcen | 16.7 ± 0.7 | 15.7 | 19.8 | 18.20 ± 4.05 |
| pting | input-mattcl | 17.1 ± 1.4 | 15.9 | 33.2 | 18.58 ± 4.33 |
| pting | input-pting | 17.8 ± 5.7 | 16.2 | 57.2 | 19.31 ± 7.49 |
| kcen | input-lanjian | 19.9 ± 0.8 | 18.7 | 23.5 | 21.69 ± 4.82 |
| kcen | input-kcen | 20.0 ± 0.8 | 18.7 | 22.6 | 21.76 ± 4.82 |
| kcen | input-mattcl | 20.2 ± 0.7 | 19.2 | 23.1 | 21.97 ± 4.86 |
| kcen | input-pting | 20.2 ± 0.8 | 18.8 | 23.3 | 22.00 ± 4.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|