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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.06 ± 0.31 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.16 ± 0.34 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.36 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.35 |
| mattcl-py | input-kcen | 15.7 ± 0.8 | 14.6 | 20.8 | 17.27 ± 3.74 |
| mattcl-py | input-pting | 15.7 ± 0.7 | 14.7 | 19.9 | 17.30 ± 3.74 |
| mattcl-py | input-mattcl | 15.8 ± 0.8 | 14.7 | 19.1 | 17.38 ± 3.77 |
| mattcl-py | input-lanjian | 15.8 ± 3.2 | 14.3 | 46.0 | 17.47 ± 5.08 |
| pting | input-lanjian | 16.8 ± 0.6 | 15.7 | 19.1 | 18.49 ± 3.96 |
| pting | input-kcen | 16.8 ± 0.6 | 15.8 | 20.2 | 18.53 ± 3.98 |
| pting | input-pting | 16.9 ± 0.7 | 16.1 | 19.9 | 18.61 ± 4.00 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.2 | 20.5 | 18.67 ± 4.00 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.9 | 22.8 | 22.07 ± 4.72 |
| kcen | input-kcen | 20.2 ± 0.9 | 18.8 | 23.3 | 22.24 ± 4.80 |
| kcen | input-mattcl | 20.3 ± 0.6 | 19.3 | 23.2 | 22.34 ± 4.76 |
| kcen | input-pting | 20.3 ± 0.8 | 19.1 | 23.0 | 22.39 ± 4.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|