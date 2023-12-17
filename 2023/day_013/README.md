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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.33 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.35 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.11 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.15 ± 0.37 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.8 | 1.15 ± 0.38 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.37 |
| mattcl-py | input-kcen | 15.4 ± 0.6 | 14.5 | 19.2 | 16.73 ± 3.96 |
| mattcl-py | input-lanjian | 15.5 ± 0.8 | 14.6 | 20.5 | 16.84 ± 4.02 |
| mattcl-py | input-pting | 15.7 ± 0.8 | 14.5 | 18.8 | 16.96 ± 4.04 |
| mattcl-py | input-mattcl | 15.7 ± 0.7 | 14.8 | 18.6 | 17.00 ± 4.04 |
| pting | input-lanjian | 16.6 ± 0.5 | 15.6 | 19.5 | 17.96 ± 4.23 |
| pting | input-pting | 16.8 ± 0.6 | 15.9 | 19.6 | 18.20 ± 4.30 |
| pting | input-mattcl | 16.9 ± 0.6 | 15.9 | 19.7 | 18.29 ± 4.32 |
| pting | input-kcen | 16.9 ± 2.1 | 15.6 | 43.5 | 18.36 ± 4.87 |
| kcen | input-kcen | 20.1 ± 0.8 | 18.8 | 22.9 | 21.80 ± 5.16 |
| kcen | input-mattcl | 20.3 ± 0.7 | 19.2 | 23.5 | 21.95 ± 5.17 |
| kcen | input-lanjian | 20.3 ± 2.8 | 18.9 | 52.9 | 22.00 ± 5.97 |
| kcen | input-pting | 20.4 ± 1.0 | 19.2 | 23.5 | 22.08 ± 5.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|