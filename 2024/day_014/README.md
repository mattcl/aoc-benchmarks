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
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.3 | 2.5 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.00 ± 0.21 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.2 | 1.00 ± 0.20 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.5 | 1.01 ± 0.21 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.4 | 2.6 | 1.01 ± 0.22 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.9 | 2.5 | 1.07 ± 0.26 |
| kcen | input-mattcl | 25.7 ± 0.8 | 24.5 | 28.5 | 18.17 ± 2.95 |
| kcen | input-lanjian | 28.7 ± 0.9 | 27.3 | 31.5 | 20.29 ± 3.29 |
| kcen | input-kcen | 32.6 ± 0.9 | 31.2 | 35.1 | 23.10 ± 3.73 |
| mattcl-py | input-mattcl | 56.2 ± 1.4 | 54.0 | 61.3 | 39.77 ± 6.40 |
| mattcl-py | input-lanjian | 60.9 ± 1.1 | 58.5 | 64.2 | 43.08 ± 6.90 |
| mattcl-py | input-kcen | 65.7 ± 1.9 | 63.4 | 72.1 | 46.52 ± 7.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|