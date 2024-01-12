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
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.30 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.05 ± 0.31 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.17 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.35 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.8 | 1.8 | 1.18 ± 0.36 |
| mattcl-py | input-mattcl | 15.5 ± 0.4 | 14.7 | 18.5 | 16.20 ± 3.37 |
| mattcl-py | input-kcen | 15.6 ± 0.6 | 14.6 | 18.6 | 16.22 ± 3.40 |
| mattcl-py | input-lanjian | 15.7 ± 2.0 | 14.3 | 41.7 | 16.36 ± 3.97 |
| mattcl-py | input-pting | 15.7 ± 0.6 | 14.9 | 18.5 | 16.36 ± 3.43 |
| pting | input-kcen | 16.8 ± 0.6 | 16.0 | 19.8 | 17.46 ± 3.66 |
| pting | input-lanjian | 16.8 ± 1.5 | 15.6 | 33.6 | 17.47 ± 3.92 |
| pting | input-pting | 16.8 ± 0.7 | 16.1 | 19.7 | 17.54 ± 3.68 |
| pting | input-mattcl | 16.9 ± 0.8 | 15.9 | 19.9 | 17.63 ± 3.72 |
| kcen | input-lanjian | 19.9 ± 0.7 | 18.8 | 22.4 | 20.74 ± 4.33 |
| kcen | input-kcen | 20.0 ± 0.8 | 18.8 | 22.8 | 20.88 ± 4.38 |
| kcen | input-pting | 20.1 ± 0.6 | 19.0 | 22.7 | 20.97 ± 4.37 |
| kcen | input-mattcl | 20.1 ± 0.7 | 19.4 | 23.9 | 20.99 ± 4.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|