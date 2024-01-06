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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 ± 0.30 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.31 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.31 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.07 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.07 ± 0.33 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.10 ± 0.32 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.7 | 1.10 ± 0.35 |
| mattcl-py | input-pting | 15.8 ± 0.7 | 14.5 | 19.0 | 16.10 ± 3.55 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.8 | 19.2 | 16.15 ± 3.57 |
| mattcl-py | input-kcen | 16.0 ± 0.8 | 14.9 | 19.4 | 16.22 ± 3.59 |
| mattcl-py | input-mattcl | 16.0 ± 0.7 | 14.8 | 19.4 | 16.29 ± 3.60 |
| pting | input-lanjian | 17.0 ± 0.5 | 16.1 | 19.7 | 17.23 ± 3.77 |
| pting | input-kcen | 17.1 ± 0.7 | 16.1 | 20.1 | 17.34 ± 3.82 |
| pting | input-pting | 17.1 ± 0.7 | 15.7 | 20.1 | 17.37 ± 3.83 |
| pting | input-mattcl | 17.2 ± 0.6 | 16.0 | 20.8 | 17.45 ± 3.83 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.3 | 22.7 | 20.60 ± 4.51 |
| kcen | input-kcen | 20.3 ± 0.7 | 18.7 | 23.5 | 20.61 ± 4.52 |
| kcen | input-pting | 20.4 ± 0.7 | 19.0 | 22.9 | 20.70 ± 4.53 |
| kcen | input-mattcl | 20.5 ± 0.5 | 19.2 | 23.7 | 20.79 ± 4.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|