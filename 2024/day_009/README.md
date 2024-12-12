# Day 9 benchmarks

[link to problem](https://adventofcode.com/2024/day/9)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 9)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 1.9 ± 0.5 | 0.9 | 2.8 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.4 | 0.8 | 3.5 | 1.07 ± 0.36 |
| mattcl | input-lanjian | 2.1 ± 0.3 | 1.3 | 2.9 | 1.08 ± 0.34 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.4 | 3.1 | 1.09 ± 0.34 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.4 | 3.4 | 1.29 ± 0.38 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.5 | 4.6 | 1.32 ± 0.40 |
| kcen | input-lanjian | 4.3 ± 0.4 | 3.5 | 7.4 | 2.26 ± 0.66 |
| kcen | input-kcen | 4.6 ± 0.5 | 3.3 | 7.3 | 2.40 ± 0.70 |
| kcen | input-mattcl | 4.6 ± 0.6 | 3.7 | 8.3 | 2.43 ± 0.73 |
| mattcl-py | input-kcen | 31.2 ± 0.8 | 29.9 | 34.5 | 16.35 ± 4.47 |
| mattcl-py | input-mattcl | 31.3 ± 0.8 | 29.8 | 34.3 | 16.41 ± 4.48 |
| mattcl-py | input-lanjian | 31.5 ± 1.1 | 30.2 | 38.5 | 16.53 ± 4.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|