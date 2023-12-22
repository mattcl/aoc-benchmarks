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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.35 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.34 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.5 | 1.06 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.16 ± 0.37 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.37 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.38 |
| mattcl-py | input-kcen | 15.7 ± 0.6 | 14.6 | 18.2 | 17.06 ± 4.00 |
| mattcl-py | input-lanjian | 15.8 ± 0.6 | 14.7 | 19.0 | 17.14 ± 4.01 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.5 | 18.6 | 17.23 ± 4.03 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.9 | 18.7 | 17.23 ± 4.03 |
| pting | input-kcen | 16.9 ± 0.7 | 16.1 | 20.1 | 18.33 ± 4.30 |
| pting | input-lanjian | 17.0 ± 0.7 | 16.1 | 20.2 | 18.38 ± 4.31 |
| pting | input-mattcl | 17.1 ± 0.7 | 16.0 | 20.1 | 18.57 ± 4.36 |
| pting | input-pting | 17.2 ± 0.7 | 16.2 | 20.7 | 18.60 ± 4.37 |
| kcen | input-lanjian | 20.1 ± 0.6 | 19.1 | 22.8 | 21.80 ± 5.08 |
| kcen | input-kcen | 20.4 ± 0.9 | 19.4 | 23.4 | 22.12 ± 5.20 |
| kcen | input-pting | 20.5 ± 0.7 | 19.2 | 23.4 | 22.23 ± 5.20 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.0 | 24.3 | 22.32 ± 5.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|