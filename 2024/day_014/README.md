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
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.6 | 2.1 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.3 | 1.00 ± 0.16 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.3 | 1.00 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.6 | 1.01 ± 0.17 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.4 | 1.02 ± 0.18 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.3 | 1.03 ± 0.18 |
| kcen | input-mattcl | 25.7 ± 1.0 | 24.3 | 29.1 | 18.64 ± 2.12 |
| kcen | input-lanjian | 28.4 ± 0.7 | 27.2 | 31.1 | 20.55 ± 2.25 |
| kcen | input-kcen | 32.5 ± 1.1 | 31.0 | 35.4 | 23.54 ± 2.63 |
| mattcl-py | input-mattcl | 56.1 ± 1.7 | 53.6 | 62.2 | 40.65 ± 4.52 |
| mattcl-py | input-lanjian | 60.7 ± 1.8 | 58.2 | 69.0 | 43.97 ± 4.87 |
| mattcl-py | input-kcen | 65.7 ± 3.0 | 63.1 | 82.9 | 47.58 ± 5.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|