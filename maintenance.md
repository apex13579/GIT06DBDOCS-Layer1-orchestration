## Home Lab Level 1 (Physical) Maintenance Checklist

### Daily/Weekly: Environmental & Visual Inspections

* [ ] **Indicator Check:** Visually confirm normal status LEDs on the UCG-Fiber, network switch, Meerkat nodes, and TrueNAS chassis (look for amber/red fault lights).
* [ ] **Acoustic Audit:** Listen to the rack for abnormal mechanical noises (e.g., clicking HDDs, grinding fan bearings, or UPS inverter coil whine).
* [ ] **Airflow Check:** Verify the AC Infinity rack exhaust is actively pushing warm air out and the room's ambient temperature buffer is stable.

### Monthly: Filtration & Interconnects

* [ ] **Dust Defense:** Remove and wash/vacuum all physical dust filters on the Pop!_OS desktop case, Meerkat intakes, and server rack doors.
* [ ] **Fiber & DAC Integrity:** Inspect the 10G SFP+ fiber patches and OM4 cables. Ensure there are no severe bends, pinch points, or tension on the cables leading into the UCG-Fiber or switch.
* [ ] **Peripheral Wipe-down:** Clean the Stream Deck Mini/XL buttons, keyboard, and mouse to prevent sticky keys and sensor tracking issues.

### Quarterly: Deep Cleaning & Moving Parts

* [ ] **System Blowout:** Power down the nodes and use compressed air to blow out the internal CPU heatsinks, power supply fans, and the 3D-printed Noctua SFP+ cooling shroud.
* [ ] **Bearing Spin Test:** While powered down, physically spin the case and rack fans with your finger. Replace any fan that feels stiff or stops immediately (indicating dried-out fluid dynamic bearings).
* [ ] **Cable Management:** Check the rear rack for cable sag. Re-velcro any heavy power cables pulling down on ethernet or fiber ports.

### Bi-Annually: Power Infrastructure & Structural

* [ ] **UPS Physical Audit:** Inspect the UPS battery chassis for any physical swelling, excessive heat, or chemical smells (signs of lead-acid cell degradation).
* [ ] **Outlet Heat Check:** Touch the wall receptacle where the UPS plugs in while the lab is under load. If the plastic wall plate is warm to the touch, flag it for electrical inspection.
* [ ] **Rack Stability:** Ensure the rack casters are locked, leveling feet are secure, and heavy components (like the UPS and NAS) haven't shifted on their rails.

### Any time a device is stopped for maintenance

* [ ] **Thermal pad/Pasting:** Remove CPU/GPU heatsinks on the Pop!_OS rig or Proxmox nodes, clean the old compound with isopropyl alcohol, and re-apply fresh thermal paste.
* [ ] **Hardware Reseating:** Physically unlatch and reseat RAM sticks, NVMe drives, and PCIe capture cards to resolve any ghost hardware faults caused by thermal expansion/contraction over time.
