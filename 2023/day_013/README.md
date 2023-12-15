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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.5 | 1.03 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.35 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.37 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.6 | 18.5 | 16.77 ± 3.84 |
| mattcl-py | input-kcen | 15.7 ± 0.8 | 14.7 | 18.8 | 16.78 ± 3.87 |
| mattcl-py | input-pting | 15.7 ± 0.6 | 14.6 | 18.6 | 16.80 ± 3.84 |
| mattcl-py | input-mattcl | 15.8 ± 0.7 | 14.8 | 19.0 | 16.87 ± 3.87 |
| pting | input-lanjian | 16.8 ± 0.6 | 15.7 | 19.7 | 17.91 ± 4.10 |
| pting | input-pting | 16.9 ± 0.7 | 16.0 | 20.0 | 18.11 ± 4.15 |
| pting | input-mattcl | 17.0 ± 0.6 | 15.8 | 19.8 | 18.12 ± 4.14 |
| pting | input-kcen | 17.0 ± 0.9 | 15.6 | 22.4 | 18.14 ± 4.20 |
| kcen | input-kcen | 20.1 ± 0.7 | 19.1 | 23.2 | 21.46 ± 4.90 |
| kcen | input-lanjian | 20.2 ± 0.7 | 18.8 | 23.0 | 21.57 ± 4.93 |
| kcen | input-pting | 20.3 ± 0.8 | 19.1 | 23.0 | 21.68 ± 4.96 |
| kcen | input-mattcl | 20.3 ± 0.6 | 19.3 | 24.3 | 21.69 ± 4.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|