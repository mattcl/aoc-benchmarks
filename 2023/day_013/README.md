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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.30 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.30 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.8 | 1.7 | 1.11 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.12 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.8 | 1.9 | 1.12 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.15 ± 0.33 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.8 | 19.4 | 15.37 ± 3.25 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 15.0 | 19.3 | 15.45 ± 3.27 |
| mattcl-py | input-mattcl | 16.1 ± 0.7 | 14.6 | 19.3 | 15.49 ± 3.27 |
| mattcl-py | input-kcen | 16.5 ± 4.2 | 14.9 | 70.3 | 15.88 ± 5.22 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.8 | 20.1 | 16.35 ± 3.44 |
| pting | input-pting | 17.3 ± 0.7 | 16.3 | 20.3 | 16.65 ± 3.50 |
| pting | input-mattcl | 17.3 ± 0.7 | 16.4 | 20.3 | 16.71 ± 3.52 |
| pting | input-kcen | 17.5 ± 3.6 | 15.6 | 52.2 | 16.86 ± 4.90 |
| kcen | input-kcen | 20.4 ± 0.8 | 19.4 | 24.6 | 19.66 ± 4.13 |
| kcen | input-mattcl | 20.5 ± 0.6 | 19.2 | 22.7 | 19.80 ± 4.14 |
| kcen | input-lanjian | 20.6 ± 3.1 | 19.2 | 56.5 | 19.82 ± 5.06 |
| kcen | input-pting | 20.7 ± 0.8 | 19.5 | 24.6 | 19.90 ± 4.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|