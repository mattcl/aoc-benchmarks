# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 119.0 ± 95.8 | 0.0 | 620.2 | 1.00 |
| whyando | input-whyando | 130.7 ± 92.5 | 0.0 | 587.9 | 1.10 ± 1.18 |
| whyando | input-mattcl | 135.5 ± 117.1 | 0.0 | 625.9 | 1.14 ± 1.35 |
| mattcl | input-whyando | 161.8 ± 115.7 | 0.0 | 719.8 | 1.36 ± 1.46 |
| mattcl | input-mattcl | 164.2 ± 119.7 | 0.0 | 771.2 | 1.38 ± 1.50 |
| mattcl | input-lanjian | 173.3 ± 109.9 | 0.0 | 605.0 | 1.46 ± 1.49 |
| kcen | input-lanjian | 528.7 ± 186.6 | 0.0 | 903.3 | 4.44 ± 3.91 |
| kcen | input-whyando | 567.9 ± 184.3 | 0.0 | 1192.9 | 4.77 ± 4.15 |
| kcen | input-mattcl | 573.6 ± 153.4 | 63.3 | 1040.8 | 4.82 ± 4.09 |
| mattcl-py | input-lanjian | 17067.3 ± 484.1 | 15933.8 | 20278.6 | 143.46 ± 115.64 |
| mattcl-py | input-whyando | 17348.0 ± 525.8 | 16059.8 | 20392.3 | 145.82 ± 117.55 |
| mattcl-py | input-mattcl | 17889.0 ± 2514.0 | 15921.0 | 34506.6 | 150.36 ± 122.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|