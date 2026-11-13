days = 180

temperature = [25.0] * days
outside_RH = [75.0] * days

# Example only: use the WVTR from the packaging supplier's
# technical data sheet at the applicable test conditions.
summary, history = simulate_hemp_protein_package(
    temperature,
    outside_RH,
    days=days,
    powder_mass_g=500.0,
    initial_moisture_percent=6.0,
    package_area_m2=0.08,
    WVTR_g_m2_day=0.10,
    seal_leak_factor=1.0
)

for key, value in summary.items():
    print(f"{key}: {value}")
