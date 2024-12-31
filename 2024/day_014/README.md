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
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.8 | 2.1 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.1 | 0.4 | 2.1 | 1.00 ± 0.13 |
| lanjian | input-kcen | 1.4 ± 0.1 | 0.3 | 2.3 | 1.01 ± 0.14 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.3 | 1.02 ± 0.16 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.6 | 1.02 ± 0.17 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.8 | 2.5 | 1.06 ± 0.21 |
| kcen | input-mattcl | 25.9 ± 0.9 | 24.7 | 28.9 | 18.47 ± 1.75 |
| kcen | input-lanjian | 28.7 ± 0.9 | 27.4 | 31.8 | 20.49 ± 1.92 |
| kcen | input-kcen | 32.4 ± 1.0 | 30.9 | 36.2 | 23.14 ± 2.16 |
| mattcl-py | input-mattcl | 56.1 ± 1.4 | 54.3 | 61.9 | 40.03 ± 3.68 |
| mattcl-py | input-lanjian | 60.7 ± 1.6 | 58.3 | 66.6 | 43.31 ± 3.99 |
| mattcl-py | input-kcen | 65.8 ± 1.9 | 63.6 | 75.3 | 46.98 ± 4.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|