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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.4 | 1.02 ± 0.34 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.38 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.5 | 1.15 ± 0.37 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.16 ± 0.38 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.38 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.7 | 18.9 | 17.37 ± 4.11 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.9 | 19.1 | 17.51 ± 4.15 |
| mattcl-py | input-pting | 16.0 ± 0.6 | 14.9 | 19.3 | 17.55 ± 4.14 |
| mattcl-py | input-mattcl | 16.1 ± 0.7 | 15.0 | 19.6 | 17.65 ± 4.18 |
| pting | input-kcen | 17.2 ± 0.7 | 16.1 | 20.7 | 18.96 ± 4.49 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.4 | 20.5 | 18.98 ± 4.48 |
| pting | input-pting | 17.5 ± 0.8 | 16.2 | 20.9 | 19.20 ± 4.57 |
| pting | input-mattcl | 17.5 ± 0.8 | 15.9 | 21.1 | 19.22 ± 4.56 |
| kcen | input-kcen | 20.6 ± 0.7 | 19.6 | 23.2 | 22.62 ± 5.32 |
| kcen | input-lanjian | 20.7 ± 0.6 | 19.8 | 23.3 | 22.76 ± 5.35 |
| kcen | input-pting | 20.9 ± 0.6 | 19.8 | 23.7 | 22.96 ± 5.38 |
| kcen | input-mattcl | 21.1 ± 0.7 | 20.0 | 24.2 | 23.18 ± 5.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|