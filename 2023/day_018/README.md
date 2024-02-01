# Day 18 benchmarks

[link to problem](https://adventofcode.com/2023/day/18)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 18)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 907.5 ± 205.6 | 170.2 | 1100.3 | 1.00 |
| lanjian | input-pting | 926.2 ± 207.1 | 170.3 | 1573.9 | 1.02 ± 0.32 |
| mattcl | input-mattcl | 958.7 ± 141.7 | 460.6 | 1142.8 | 1.06 ± 0.29 |
| mattcl | input-pting | 960.2 ± 151.7 | 430.2 | 1564.7 | 1.06 ± 0.29 |
| mattcl | input-kcen | 960.6 ± 153.2 | 236.3 | 1336.7 | 1.06 ± 0.29 |
| mattcl | input-lanjian | 971.1 ± 144.4 | 443.4 | 1743.1 | 1.07 ± 0.29 |
| lanjian | input-kcen | 976.8 ± 165.0 | 237.4 | 1676.9 | 1.08 ± 0.30 |
| lanjian | input-mattcl | 985.4 ± 141.1 | 280.1 | 1299.0 | 1.09 ± 0.29 |
| mattcl-py | input-lanjian | 14571.4 ± 632.5 | 13334.6 | 17284.2 | 16.06 ± 3.70 |
| mattcl-py | input-pting | 14653.0 ± 733.9 | 13252.4 | 17809.4 | 16.15 ± 3.75 |
| pting | input-pting | 14770.8 ± 574.7 | 13815.2 | 18272.7 | 16.28 ± 3.74 |
| pting | input-lanjian | 14784.2 ± 560.8 | 13746.9 | 17554.7 | 16.29 ± 3.74 |
| mattcl-py | input-mattcl | 14951.5 ± 582.5 | 13690.1 | 18171.5 | 16.48 ± 3.79 |
| mattcl-py | input-kcen | 15007.6 ± 578.9 | 13769.4 | 18199.0 | 16.54 ± 3.80 |
| pting | input-mattcl | 15169.7 ± 589.4 | 13936.3 | 18521.9 | 16.72 ± 3.84 |
| pting | input-kcen | 15216.5 ± 723.7 | 14112.1 | 18912.0 | 16.77 ± 3.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|