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
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.5 | 1.00 ± 0.30 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.31 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.31 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.08 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.8 | 1.7 | 1.13 ± 0.34 |
| lanjian | input-lanjian | 1.4 ± 4.4 | 0.7 | 63.9 | 1.41 ± 4.50 |
| mattcl-py | input-lanjian | 15.5 ± 0.7 | 14.5 | 19.0 | 15.61 ± 3.56 |
| mattcl-py | input-kcen | 15.5 ± 0.6 | 14.6 | 18.5 | 15.62 ± 3.54 |
| mattcl-py | input-pting | 15.5 ± 0.6 | 14.6 | 18.6 | 15.64 ± 3.55 |
| mattcl-py | input-mattcl | 15.6 ± 0.7 | 14.5 | 18.7 | 15.73 ± 3.59 |
| pting | input-lanjian | 16.8 ± 0.8 | 15.9 | 19.8 | 16.91 ± 3.86 |
| pting | input-kcen | 16.8 ± 0.6 | 15.8 | 19.7 | 16.92 ± 3.84 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.0 | 20.3 | 17.01 ± 3.85 |
| pting | input-pting | 16.9 ± 0.7 | 15.6 | 19.6 | 17.06 ± 3.88 |
| kcen | input-kcen | 20.0 ± 0.6 | 18.8 | 22.8 | 20.12 ± 4.54 |
| kcen | input-pting | 20.1 ± 0.7 | 19.0 | 23.5 | 20.26 ± 4.59 |
| kcen | input-mattcl | 20.2 ± 0.8 | 19.3 | 23.5 | 20.39 ± 4.63 |
| kcen | input-lanjian | 20.2 ± 1.4 | 19.2 | 33.8 | 20.40 ± 4.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|