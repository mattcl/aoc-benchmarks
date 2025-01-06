# Day 14 benchmarks

[link to problem](https://adventofcode.com/2024/day/14)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 14)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.1 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.1 | 1.00 ± 0.15 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.2 | 1.00 ± 0.15 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.8 | 1.9 | 1.00 ± 0.14 |
| lanjian | input-kcen | 1.5 ± 0.1 | 0.8 | 2.4 | 1.01 ± 0.15 |
| lanjian | input-lanjian | 1.5 ± 0.1 | 0.8 | 2.3 | 1.02 ± 0.15 |
| kcen | input-mattcl | 25.6 ± 1.0 | 24.5 | 28.7 | 17.93 ± 2.05 |
| kcen | input-lanjian | 28.4 ± 0.9 | 27.2 | 32.0 | 19.89 ± 2.24 |
| kcen | input-kcen | 32.1 ± 0.9 | 30.6 | 34.8 | 22.43 ± 2.50 |
| mattcl-py | input-mattcl | 55.7 ± 1.1 | 54.3 | 60.6 | 39.00 ± 4.29 |
| mattcl-py | input-lanjian | 60.2 ± 1.1 | 58.6 | 63.8 | 42.10 ± 4.62 |
| mattcl-py | input-kcen | 65.5 ± 1.2 | 63.5 | 68.5 | 45.83 ± 5.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|