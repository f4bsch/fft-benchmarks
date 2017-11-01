# fft-benchmarks

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


`` 
