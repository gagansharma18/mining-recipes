# mining-recipes
mining related things

RX580
```
REM
REM Example bat file for starting PhoenixMiner.exe to mine ETH  -cclock 1200 -cvddc 890
REM

setx GPU_FORCE_64BIT_PTR 0
setx GPU_MAX_HEAP_SIZE 100
setx GPU_USE_SYNC_OBJECTS 1
setx GPU_MAX_ALLOC_PERCENT 100
setx GPU_SINGLE_ALLOC_PERCENT 100

REM IMPORTANT: Replace the ETH address with your own ETH wallet address in the -wal option (Rig001 is the name of the rig)
PhoenixMiner_5.9d_Windows\PhoenixMiner.exe" -pool asia2.ethermine.org:14444 -wal WALLET.RX580 -amd -hstats 2 -VMR 25 -MT 1 -gt 40 -cclock 1250 -mclock 2070 -cvddc 850 -mvddc 850 -tt 60
pause

```
