# SRBMiner-MULTI

**CPU & AMD/NVIDIA/Intel GPU miner**  
Mine up to 4 different algorithms at the same time · Lowest dev fees in class**

## Features
- Extremely low developer fees (0.00 % – 2.00 %)
- Simultaneous mining of up to 4 algorithms (dual / triple / quad)
- Full support for CPU + AMD + NVIDIA + Intel Arc GPUs
- Built-in watchdog, auto-restart, pool failover
- Web monitoring dashboard & full JSON-API
- Ready for HiveOS, RaveOS, minerstat, SimpleMining OS
- Advanced tuning parameters and overclocking profiles

## Supported Algorithms & Dev Fee

| Dev Fee | CPU | AMD | NVIDIA | Intel | Algorithm                  |
|---------|-----|-----|--------|-------|----------------------------|
| 0.65 %  |     | ✓   | ✓      | ✓     | ethash / etchash           |
| 0.85 %  |     | ✓   | ✓      | ✓     | kawpow                     |
| 1.00 %  |     | ✓   | ✓      | ✓     | autolykos2                 |
| 0.85 %  |     | ✓   | ✓      | ✓     | heavyhash                  |
| 0.85 %  |     | ✓   | ✓      | ✓     | fishhash                   |
| 1.00 %  |     | ✓   | ✓      | ✓     | karlsenhashv2              |
| 0.85 %  | ✓   | ✓   | ✓      |       | randomx & all Random* forks|
| 0.85 %  | ✓   |     |        |       | cpupower                   |
| 0.85 %  | ✓   | ✓   |        |       | ghostrider                 |
| 0.00 %  | ✓   |     |        |       | yespowerurx (0 % fee)      |
| … and 60+ more algorithms …                                      |

## Dual / Triple / Quad Mining
Any combination is possible, popular examples:
- ethash + kawpow + heavyhash
- autolykos2 + blake3
- fishhash + sha3x
- randomx + any GPU algorithm

## GPU Compatibility

**AMD**  
RX 7900/7800/7700 · RX 6000 · RX 5000 · Vega · Polaris

**NVIDIA**  
RTX 40xx · RTX 30xx · RTX 20xx · GTX 16/10 series (older cards with `--disable-ptx-check`)

**Intel Arc**  
A770 · A750 · A580 · A380 and newer

## Quick Start Example
```bat
