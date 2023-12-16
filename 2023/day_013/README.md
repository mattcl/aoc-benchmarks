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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.05 ± 0.34 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.6 | 1.06 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.07 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.20 ± 0.38 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.6 | 1.6 | 1.20 ± 0.38 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.21 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.21 ± 0.37 |
| mattcl-py | input-kcen | 15.5 ± 0.6 | 14.6 | 18.3 | 17.73 ± 3.93 |
| mattcl-py | input-pting | 15.5 ± 0.5 | 14.9 | 18.2 | 17.77 ± 3.93 |
| mattcl-py | input-lanjian | 15.6 ± 0.7 | 14.4 | 18.9 | 17.79 ± 3.96 |
| mattcl-py | input-mattcl | 15.6 ± 0.6 | 14.5 | 18.7 | 17.85 ± 3.96 |
| pting | input-lanjian | 16.6 ± 0.6 | 15.7 | 19.8 | 19.01 ± 4.22 |
| pting | input-kcen | 16.7 ± 0.7 | 15.6 | 20.0 | 19.08 ± 4.25 |
| pting | input-pting | 16.8 ± 0.6 | 15.6 | 19.3 | 19.15 ± 4.24 |
| pting | input-mattcl | 16.8 ± 0.5 | 16.1 | 19.5 | 19.22 ± 4.24 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.8 | 22.4 | 22.84 ± 5.05 |
| kcen | input-kcen | 20.0 ± 0.7 | 18.9 | 22.8 | 22.88 ± 5.07 |
| kcen | input-pting | 20.1 ± 0.7 | 19.1 | 22.6 | 22.98 ± 5.08 |
| kcen | input-mattcl | 20.3 ± 0.7 | 19.3 | 23.2 | 23.20 ± 5.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|