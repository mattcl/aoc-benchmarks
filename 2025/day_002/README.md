# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 313.2 ± 247.9 | 0.0 | 950.2 | 1.00 |
| whyando | input-mattcl | 506.0 ± 149.1 | 0.0 | 937.5 | 1.62 ± 1.36 |
| whyando | input-whyando | 526.5 ± 143.0 | 0.0 | 973.1 | 1.68 ± 1.41 |
| kcen | input-mattcl | 602.6 ± 292.0 | 0.0 | 1209.1 | 1.92 ± 1.78 |
| kcen | input-whyando | 760.0 ± 127.8 | 204.0 | 1327.5 | 2.43 ± 1.96 |
| kcen | input-lanjian | 765.9 ± 124.0 | 183.0 | 1182.7 | 2.44 ± 1.97 |
| mattcl | input-whyando | 908.4 ± 137.1 | 380.6 | 1455.6 | 2.90 ± 2.34 |
| mattcl | input-mattcl | 911.9 ± 146.6 | 327.4 | 1508.1 | 2.91 ± 2.35 |
| mattcl | input-lanjian | 916.6 ± 137.7 | 362.3 | 1521.6 | 2.93 ± 2.36 |
| lanjian | input-mattcl | 1051.0 ± 199.6 | 393.3 | 1872.0 | 3.36 ± 2.73 |
| lanjian | input-whyando | 1100.2 ± 224.3 | 299.3 | 2098.1 | 3.51 ± 2.87 |
| lanjian | input-lanjian | 1134.4 ± 217.3 | 493.7 | 2185.0 | 3.62 ± 2.95 |
| mattcl-py | input-whyando | 20117.9 ± 582.5 | 18941.8 | 22523.7 | 64.22 ± 50.86 |
| mattcl-py | input-mattcl | 20404.6 ± 550.6 | 19343.7 | 23154.1 | 65.14 ± 51.58 |
| mattcl-py | input-lanjian | 20569.8 ± 815.5 | 18879.6 | 26516.6 | 65.67 ± 52.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|