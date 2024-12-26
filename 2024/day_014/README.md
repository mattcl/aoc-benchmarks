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
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 0.7 | 2.2 | 1.00 ± 0.17 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.5 | 1.00 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.2 | 1.01 ± 0.18 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.5 | 1.01 ± 0.18 |
| lanjian | input-kcen | 1.4 ± 0.1 | 0.9 | 2.7 | 1.01 ± 0.17 |
| kcen | input-mattcl | 25.5 ± 0.8 | 24.4 | 28.5 | 18.11 ± 2.56 |
| kcen | input-lanjian | 28.4 ± 1.0 | 27.2 | 31.3 | 20.21 ± 2.87 |
| kcen | input-kcen | 31.9 ± 0.8 | 30.4 | 34.4 | 22.68 ± 3.17 |
| mattcl-py | input-mattcl | 56.8 ± 4.1 | 54.7 | 85.4 | 40.36 ± 6.28 |
| mattcl-py | input-lanjian | 60.9 ± 1.1 | 58.9 | 64.7 | 43.28 ± 6.00 |
| mattcl-py | input-kcen | 66.0 ± 1.4 | 63.9 | 71.7 | 46.95 ± 6.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|