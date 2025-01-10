# SSE50Option_specification
Specification analysis of volatility dynamics on option valuation models for SSE 50 options (INCOMPLETE Version)

## Description of each file
  
  - fit characteristics: visualizations of fitted implied volatility smirk and fitting quality;

## What we do
  - Motivated by empirical evidence from daily realized volatility, implied volatility surface dynamics, we go beyond affine variance dynamics and investigate alternative multiple instantaneous variance factors continuous-time models for the Chinese options market;
  - Conducted empirical analysis using large-scale options panel: parameter estimation, fitting performance, diagnostics of estimation procedure, and statistical tests for model comparisons;
  - Notably, for non-affine models, the lack of characteristic function of log spot price makes efficient Fourier inversion technique unavailable. To speed up estimation procedure, we leverage deep learning technique to learn each pricing map for later use;
