**F1_baseline_g0**: Baseline, g = 0. (a) P_R(t): analytic sin²t (line), Trotter-2 SV (circles, max deviation 5e-14) and shots (StatevectorSampler, N = 1000, ±1σ; χ²/dof = 1.48). A fit to the shots gives amplitude 0.992 ± 0.006 and period 3.142 ± 0.003. (b) ⟨Z₁⟩ from shots at g = 0 and g = 2 (±1σ), grey band ±2/√N; SV |⟨Z₁⟩| < 1e-15.

**F2_PR_vs_time**: P_R(t) for six values of g. Blue: SV. Black dashed: analytic A sin²(Ωt). Orange: shots (StatevectorSampler, exact circuit, 2000 shots per point, ±1σ). Dotted: A = 1/(1+(g/2Δ)²).

**F3_tunnelling_trend**: (a) Tunnelling amplitude A vs g: SV fits, SV time average 2⟨P_R⟩, shot fits (±1σ), and 1/(1+(g/2Δ)²). (b) Frequency Ω vs g against √(Δ²+g²/4). (c) 1/A and Ω²/Δ² vs g². Weighted fit to the shot data: slope 0.2507 ± 0.0014, intercept 1.0002 ± 0.0005, giving Δ = 0.9987 ± 0.0028.

**F4_trotter_convergence**: Trotter convergence at g = 2 (solid, circles) and g = 8 (dashed, squares); SV, maximum over t ∈ [0, 10]. (a) Infidelity scales as dt^2 (Trotter-1) and dt^4 (Trotter-2). (b) max |ΔP_R| scales as dt^2 for both orders. Dash-dotted: shot noise 0.5/√N; errors in the shaded region are below the N = 1000 noise.

**F5_trotter_gsweep**: g-sweep with Trotter-2 (error bound ≤ 0.001). (a) Trotter-2 SV (circles) and expm (lines) for g = 0, 2, 8. (b, c) A and Ω fitted to the Trotter data against the analytic forms; agreement 4e-05 (A) and 1e-05 (Ω, relative).

**F6_spin_and_concurrence**: SV. (a) Spin Bloch components at g = 2Δ: ⟨Z₁⟩ = 0 at all times; |r| reaches 0 at t* = π/(2√2). (b) Concurrence for g = 0.5, 2, 8 with the analytic C(t) = (gΔ/Ω²) sin²(Ωt) dashed. (c) C against (g/Δ)·P_R over all g and t (max deviation 6e-16).

**F7_entanglement_vs_g**: SV. (a) Peak concurrence and tunnelling amplitude vs g (log scale): C_max = 1 at g = 2Δ, where A = 1/2, and C_max(g) = C_max(4Δ²/g). (b) Connected position–spin correlators at g = 2Δ: ⟨Z₀Z₁⟩_c is zero at all times while ⟨X₀Z₁⟩_c, ⟨Z₀X₁⟩_c and ⟨Y₀Y₁⟩_c reach ±1.

**F8_entanglement_from_shots**: Shots (StatevectorSampler, exact circuit, 9-setting tomography, 2000 shots per setting, mean ± sd over 10 seeds). (a) Measured connected correlation matrix at g = 2Δ, t*; the boxed entry is the only one accessible from computational-basis counts. (b) Entanglement estimators vs exact concurrence. Grey: product state with a classically dephased spin; the Bloch estimator gives ≈ 1, tomography concurrence and negativity ≈ 0.

**F9_gate_noise**: Gate noise (density matrix; two-qubit depolarizing error p after every CX; g = 2). (a) Trace distance to the exact state at t = 5 vs number of Trotter-2 steps; stars mark the optimum (n = 24 at p = 1e-3, distance 0.047); dotted lines: exact 2-CX circuit under the same noise (1.5e-03 at p = 1e-3); dash-dot: Trotter-1 at p = 1e-3. (b) 2×negativity at t* vs p for circuits with 2, 20 and 200 CX; dashed: spin-only Bloch estimator, which stays near 1 while the entanglement is lost.

**F10_robustness**: (a) Maximum 2×negativity at g = 2Δ for different initial spin states (SV). All give the same P_R(t) (max deviation 4e-16); only spin superpositions become entangled, independent of their relative phase. (b) P_R against Δt for Δ = 0.5, 1, 2 at fixed g/2Δ (SV); curves coincide to 2e-15.

