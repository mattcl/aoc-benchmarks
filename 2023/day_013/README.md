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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 2.2 | 1.04 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.11 ± 0.34 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.8 | 1.15 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.37 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.8 | 19.0 | 16.81 ± 3.79 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.7 | 18.7 | 16.89 ± 3.81 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 15.1 | 18.7 | 16.93 ± 3.80 |
| mattcl-py | input-mattcl | 16.1 ± 0.8 | 15.1 | 19.4 | 17.00 ± 3.84 |
| pting | input-lanjian | 16.9 ± 0.6 | 15.8 | 19.7 | 17.88 ± 4.00 |
| pting | input-kcen | 17.0 ± 0.6 | 15.8 | 19.8 | 17.93 ± 4.01 |
| pting | input-pting | 17.1 ± 0.7 | 16.2 | 19.9 | 18.09 ± 4.06 |
| pting | input-mattcl | 17.3 ± 0.7 | 16.4 | 20.5 | 18.25 ± 4.10 |
| kcen | input-lanjian | 20.2 ± 0.7 | 18.8 | 23.0 | 21.33 ± 4.77 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.1 | 23.3 | 21.41 ± 4.79 |
| kcen | input-pting | 20.4 ± 0.8 | 19.0 | 23.9 | 21.58 ± 4.83 |
| kcen | input-mattcl | 20.5 ± 0.6 | 19.1 | 23.3 | 21.68 ± 4.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|