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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.5 | 1.00 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.5 | 1.04 ± 0.30 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.8 | 1.7 | 1.10 ± 0.31 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.14 ± 0.32 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.8 | 1.8 | 1.16 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.7 | 1.17 ± 0.33 |
| mattcl-py | input-lanjian | 15.9 ± 0.5 | 14.9 | 18.3 | 15.88 ± 3.25 |
| mattcl-py | input-pting | 16.0 ± 0.6 | 14.9 | 18.6 | 15.95 ± 3.27 |
| mattcl-py | input-mattcl | 16.0 ± 0.7 | 14.5 | 18.5 | 15.97 ± 3.30 |
| mattcl-py | input-kcen | 16.2 ± 3.1 | 14.5 | 56.8 | 16.17 ± 4.49 |
| pting | input-lanjian | 16.9 ± 0.5 | 16.1 | 19.3 | 16.93 ± 3.45 |
| pting | input-pting | 17.2 ± 0.7 | 16.1 | 20.3 | 17.23 ± 3.54 |
| pting | input-mattcl | 17.3 ± 0.8 | 16.0 | 20.7 | 17.32 ± 3.59 |
| pting | input-kcen | 17.4 ± 4.7 | 16.1 | 79.6 | 17.43 ± 5.91 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.2 | 23.1 | 20.26 ± 4.14 |
| kcen | input-pting | 20.5 ± 0.7 | 19.5 | 23.5 | 20.47 ± 4.19 |
| kcen | input-mattcl | 20.5 ± 0.6 | 19.5 | 23.4 | 20.53 ± 4.19 |
| kcen | input-lanjian | 20.8 ± 3.8 | 19.5 | 64.6 | 20.80 ± 5.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|