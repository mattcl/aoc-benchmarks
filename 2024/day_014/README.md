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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.3 | 2.1 | 1.00 ± 0.19 |
| lanjian | input-kcen | 1.4 ± 0.1 | 0.8 | 1.8 | 1.01 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.5 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.5 | 1.02 ± 0.17 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.3 | 1.03 ± 0.17 |
| kcen | input-mattcl | 25.4 ± 0.9 | 24.4 | 28.4 | 18.25 ± 2.35 |
| kcen | input-lanjian | 28.2 ± 0.7 | 26.9 | 30.2 | 20.27 ± 2.56 |
| kcen | input-kcen | 32.0 ± 0.8 | 31.0 | 35.0 | 22.98 ± 2.91 |
| mattcl-py | input-mattcl | 56.6 ± 1.8 | 54.4 | 64.6 | 40.64 ± 5.20 |
| mattcl-py | input-lanjian | 61.1 ± 1.5 | 59.0 | 66.2 | 43.87 ± 5.55 |
| mattcl-py | input-kcen | 65.8 ± 1.6 | 63.7 | 69.8 | 47.25 ± 5.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|