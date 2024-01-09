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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.33 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.5 | 1.06 ± 0.34 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.37 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.8 | 1.17 ± 0.37 |
| mattcl | input-mattcl | 1.2 ± 3.6 | 0.6 | 51.6 | 1.27 ± 3.91 |
| mattcl-py | input-kcen | 15.6 ± 0.7 | 14.4 | 18.5 | 16.92 ± 3.82 |
| mattcl-py | input-lanjian | 15.6 ± 0.6 | 14.6 | 18.5 | 16.94 ± 3.81 |
| mattcl-py | input-pting | 15.7 ± 0.8 | 14.6 | 19.1 | 17.06 ± 3.87 |
| mattcl-py | input-mattcl | 16.0 ± 3.2 | 14.6 | 45.9 | 17.39 ± 5.19 |
| pting | input-lanjian | 16.6 ± 0.4 | 15.8 | 18.3 | 18.03 ± 4.03 |
| pting | input-kcen | 16.7 ± 0.6 | 15.9 | 19.9 | 18.16 ± 4.08 |
| pting | input-pting | 16.9 ± 0.8 | 15.8 | 20.7 | 18.41 ± 4.17 |
| pting | input-mattcl | 16.9 ± 0.8 | 15.8 | 20.1 | 18.42 ± 4.17 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.9 | 22.9 | 21.72 ± 4.88 |
| kcen | input-kcen | 20.1 ± 0.8 | 18.6 | 22.7 | 21.82 ± 4.91 |
| kcen | input-pting | 20.1 ± 0.7 | 19.0 | 23.0 | 21.83 ± 4.90 |
| kcen | input-mattcl | 21.0 ± 5.4 | 18.9 | 76.9 | 22.87 ± 7.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|