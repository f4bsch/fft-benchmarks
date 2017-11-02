# fft-benchmarks

i7 skylake
```
                       Halide                  FFTW     
    DFT type  Time (us)    MFLOP/s  Time (us)    MFLOP/s      Ratio
         c2c      0.232   44066.70      0.321   31881.24       1.38
         r2c      0.167   30709.44      0.322   15907.88       1.93
         c2r      0.164   31176.17      0.318   16100.27       1.94
./bin/bench_fft 32 32 ./bin/
                       Halide                  FFTW     
    DFT type  Time (us)    MFLOP/s  Time (us)    MFLOP/s      Ratio
         c2c      1.985   25798.87      1.390   36836.12        0.7
         r2c      0.747   34280.24      1.465   17472.39       1.96
         c2r      0.814   31447.39      1.485   17243.31       1.82
./bin/bench_fft 48 48 ./bin/
                       Halide                  FFTW     
    DFT type  Time (us)    MFLOP/s  Time (us)    MFLOP/s      Ratio
         c2c      5.783   22252.18      4.228   30437.02      0.731
         r2c      2.269   28352.27      4.437   14501.39       1.96
         c2r      2.370   27149.15      4.252   15130.43       1.79
./bin/bench_fft 64 64 ./bin/
                       Halide                  FFTW     
    DFT type  Time (us)    MFLOP/s  Time (us)    MFLOP/s      Ratio
         c2c     13.212   18601.33      6.387   38480.45      0.483
         r2c      4.861   25277.14      6.491   18931.69       1.34
         c2r      4.176   29422.22      6.141   20011.03       1.47

./bin/bench_fft 256 256 ./bin/
    DFT type  Time (us)    MFLOP/s  Time (us)    MFLOP/s      Ratio

         c2c      0.000        inf    152.402   34401.55        inf
         r2c    169.798   15438.56    124.872   20992.95      0.735
         c2r    106.468   24621.79    115.906   22617.02       1.09

512x512
                       Halide                  FFTW     
    DFT type  Time (us)    MFLOP/s  Time (us)    MFLOP/s      Ratio
         c2c      0.000        inf    673.710   35019.44        inf
         r2c    948.491   12437.11    528.937   22302.24      0.558
         c2r    586.147   20125.47    498.579   23660.21      0.851
1024x1024
    DFT type  Time (us)    MFLOP/s  Time (us)    MFLOP/s      Ratio
         c2c      0.000        inf   3605.260   29084.61        inf
         r2c   5937.125    8830.67   2652.942   19762.51      0.447
         c2r   5702.957    9193.27   2187.367   23968.91      0.384



`` 
