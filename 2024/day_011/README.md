# Day 11 benchmarks

[link to problem](https://adventofcode.com/2024/day/11)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 11)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 3.3 ± 0.4 | 2.5 | 4.9 | 1.00 |
| mattcl | input-mattcl | 3.4 ± 0.4 | 2.3 | 5.5 | 1.02 ± 0.17 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.7 | 6.8 | 1.04 ± 0.17 |
| lanjian | input-lanjian | 11.0 ± 0.5 | 10.2 | 14.4 | 3.31 ± 0.40 |
| lanjian | input-kcen | 11.4 ± 0.6 | 10.2 | 15.0 | 3.41 ± 0.42 |
| lanjian | input-mattcl | 11.6 ± 0.7 | 10.4 | 15.1 | 3.49 ± 0.44 |
| kcen | input-lanjian | 19.6 ± 0.7 | 18.5 | 22.9 | 5.89 ± 0.69 |
| kcen | input-kcen | 21.0 ± 0.7 | 20.0 | 24.6 | 6.29 ± 0.73 |
| kcen | input-mattcl | 21.1 ± 0.6 | 20.1 | 23.7 | 6.33 ± 0.73 |
| mattcl-py | input-lanjian | 63.6 ± 1.5 | 61.0 | 67.6 | 19.08 ± 2.18 |
| mattcl-py | input-kcen | 69.5 ± 1.0 | 67.3 | 71.9 | 20.85 ± 2.35 |
| mattcl-py | input-mattcl | 70.3 ± 1.1 | 68.2 | 72.8 | 21.09 ± 2.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>194782</pre>|<pre>233007586663131</pre>|
|input-lanjian|<pre>218956</pre>|<pre>259593838049805</pre>|
|input-mattcl|<pre>189547</pre>|<pre>224577979481346</pre>|