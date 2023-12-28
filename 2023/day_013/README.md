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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.33 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.09 ± 0.34 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.36 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.16 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.38 |
| mattcl-py | input-pting | 16.2 ± 0.5 | 15.0 | 18.7 | 17.85 ± 3.98 |
| mattcl-py | input-lanjian | 16.2 ± 0.5 | 15.0 | 18.3 | 17.86 ± 3.98 |
| mattcl-py | input-mattcl | 16.9 ± 2.6 | 15.0 | 25.2 | 18.70 ± 5.03 |
| mattcl-py | input-kcen | 17.1 ± 2.7 | 15.0 | 26.7 | 18.93 ± 5.16 |
| pting | input-kcen | 17.3 ± 0.5 | 16.0 | 20.0 | 19.08 ± 4.25 |
| pting | input-mattcl | 17.5 ± 0.6 | 16.5 | 20.6 | 19.32 ± 4.31 |
| pting | input-lanjian | 18.2 ± 3.1 | 15.8 | 33.6 | 20.05 ± 5.61 |
| pting | input-pting | 18.7 ± 3.0 | 16.8 | 27.9 | 20.64 ± 5.63 |
| kcen | input-lanjian | 20.5 ± 0.6 | 19.4 | 22.8 | 22.68 ± 5.05 |
| kcen | input-kcen | 20.7 ± 0.6 | 19.5 | 23.2 | 22.81 ± 5.08 |
| kcen | input-mattcl | 20.8 ± 0.5 | 19.7 | 23.4 | 22.91 ± 5.09 |
| kcen | input-pting | 20.9 ± 0.6 | 19.9 | 23.7 | 23.03 ± 5.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|