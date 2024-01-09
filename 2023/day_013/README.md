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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.35 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.5 | 1.5 | 1.06 ± 0.35 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.11 ± 0.36 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.11 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.6 | 1.6 | 1.16 ± 0.39 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.38 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.8 | 19.0 | 17.28 ± 4.17 |
| mattcl-py | input-mattcl | 15.8 ± 0.5 | 14.8 | 18.4 | 17.30 ± 4.16 |
| mattcl-py | input-pting | 15.8 ± 0.5 | 14.6 | 18.7 | 17.32 ± 4.17 |
| mattcl-py | input-lanjian | 15.9 ± 0.8 | 14.9 | 19.6 | 17.42 ± 4.24 |
| pting | input-kcen | 17.0 ± 0.8 | 15.9 | 20.4 | 18.63 ± 4.51 |
| pting | input-pting | 17.1 ± 0.7 | 15.8 | 20.5 | 18.64 ± 4.50 |
| pting | input-lanjian | 17.1 ± 0.8 | 15.8 | 20.4 | 18.66 ± 4.53 |
| pting | input-mattcl | 17.4 ± 3.2 | 15.9 | 56.7 | 19.04 ± 5.70 |
| kcen | input-lanjian | 20.1 ± 0.6 | 18.6 | 23.8 | 21.98 ± 5.28 |
| kcen | input-kcen | 20.4 ± 0.9 | 19.0 | 23.5 | 22.27 ± 5.39 |
| kcen | input-pting | 20.4 ± 1.1 | 18.9 | 30.6 | 22.32 ± 5.45 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.5 | 23.4 | 22.44 ± 5.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|