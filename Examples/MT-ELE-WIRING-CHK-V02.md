# MT-ELE-WIRING-CHK-V02

**Domain:** ELE (Electrical)  
**Method ID:** WIRING-CHK (Wiring Check)  
**Version:** V02

---

## Purpose

Verify the integrity and reliability of the aircraft’s electrical wiring and power distribution systems. Ensuring all circuits are free from damage, corrosion, or loose connections improves safety, prevents electrical failures, and maintains optimal performance.

## Applicability

- Aircraft Model: A360XWLRGA  
- All electrical circuits, focusing on main busbars, junction boxes, and distribution panels.

## Tools & Equipment

- **Multimeter:** For continuity and voltage checks.  
- **Inspection Camera:** To inspect wiring in confined or hard-to-reach areas.  
- **PPE:** Insulated gloves, safety glasses, and hearing protection (if necessary).

## Safety Notes

1. **Disconnect Power:**  
   Ensure the aircraft’s electrical power is fully disconnected before inspection to prevent electrical shock.

2. **Use PPE:**  
   Wear insulated gloves and safety glasses to protect against electrical hazards and potential debris.

3. **Environmental Considerations:**  
   Conduct the inspection in a well-lit area with stable temperature and humidity conditions.

## Procedure Summary

1. **Pre-Inspection Setup:**
   - Confirm aircraft power is off.
   - Verify multimeter calibration (`MT-CAL-MULTI-V01` if applicable).
   - Ensure access panels are open and wiring bundles are visible.

2. **Visual Inspection:**
   - Check wiring bundles for signs of fraying, discoloration, or corrosion.
   - Use the inspection camera to examine tight or hidden areas.
   - Confirm that all connectors, ties, and clamps are secure.

3. **Continuity and Voltage Checks:**
   - Set the multimeter to continuity mode to verify electrical paths are intact.
   - Test selected circuits to ensure expected voltage levels match engineering specifications.
   - Record readings and compare them against baseline values from `GAA-2400-MP-00-E-0003`.

4. **Connector Verification:**
   - Inspect terminals and connectors for loose or damaged pins.
   - Tighten or replace connectors as necessary following `MT-ELE-CONN-V01` (if defined).

5. **Final Verification:**
   - Close access panels.
   - Restore aircraft power and run a functional test of critical electrical systems if required.

## References

- **S1000D Data Module:** `GAA-2400-MP-00-E-0003` (Electrical Maintenance Procedure)
- **ATA Chapter:** 24 (Electrical Power)
- **Regulatory Compliance:** FAA AD 2024-05-12
- **Related Tokens:**  
  - `MT-ELE-CONN-V01` (Connector Inspection)
  - `MT-CAL-MULTI-V01` (Multimeter Calibration)

## Integration with Digital Tools

- **AR/VR:**  
  When a technician uses AR glasses, instructions from `MT-ELE-WIRING-CHK-V02` can overlay onto the live camera view. The system highlights wiring paths, suggests test points, and displays expected readings.

- **IoT and Predictive Maintenance:**  
  If IoT sensors detect unusual electrical load patterns, the CMS may recommend performing `MT-ELE-WIRING-CHK-V02` early to prevent potential failures.

## Version History

- **V02:**  
  - Updated procedure steps for clarity.  
  - Added reference to `MT-ELE-CONN-V01` for connector-related checks.
- **V01:**  
  - Initial method token created and integrated into MTL.

---

**End of Document**
