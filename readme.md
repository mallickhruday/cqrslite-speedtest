﻿# Performance testing of CqrsLite
Running on Dell Precision T3610 with specs:  
Intel Xeon E5-1650v2@3.5 GHz  
32 GB DDR ram  
Samsung SSD SM841 512GB  
Windows 10  

## .net full framework
- 0.3.4   - exec: ~57s. per ms: ~1100
- 0.9.9   - exec: ~37s. per ms: ~1700
- 0.11.36 - exec: ~63s. per ms: ~980
- 0.12.0  - exec: ~65s. per ms: ~965
- 0.13.2  - exec: ~10s. per ms: ~6200
- 0.14.4  - exec: ~10s. per ms: ~6200
- 0.15.1  - exec: ~8s.  per ms: ~8000
- 0.16.0  - exec: ~8s.  per ms: ~8200
- 0.17.0  - exec: ~6.2s.  per ms: ~10000
- 0.18.0  - exec: ~5s.  per ms: ~12500
- 0.19.0  - exec: ~5s.  per ms: ~12500
- 0.22.0  - exec: ~5s.  per ms: ~12500

## dotnet core
- 0.12.0  - exec: ~79s. per ms: ~800
- 0.13.2  - exec: ~8.5s. per ms: ~7400
- 0.14.4  - exec: ~8.5s. per ms: ~7400
- 0.15.1  - exec: ~6.3s. per ms: ~10000
- 0.16.0  - exec: ~6.3s. per ms: ~10000
- 0.17.0  - exec: ~5.0s.  per ms: ~12500
- 0.18.0  - exec: ~4.0s.  per ms: ~15500
- 0.19.0  - exec: ~4.0s.  per ms: ~15500
- 0.22.0  - exec: ~4.0s.  per ms: ~15500


## dotnet core macbook 2015
1.3 ghz i7 core m, 8 gb ram, 512 gb ssd.

- 0.12.0 - exec: ~139s per ms: ~450
- 0.13.2 - exec: ~16.7s per ms: ~3800
- 0.14.4 - exec: ~16.7s per ms: ~3800
- 0.15.1 - exec: ~12.5s per ms: ~5000
- 0.16.0 - exec: ~12.5s per ms: ~5000
- 0.17.0 - exec: ~9.6s per ms: ~6500
- 0.18.0 - exec: ~7.5s per ms: ~8300
- 0.19.0 - exec: ~7.5s per ms: ~8300