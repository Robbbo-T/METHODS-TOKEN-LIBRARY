# MT-CAL-MULTI-V01

**Domain:** CAL (Calibration)  
**Method ID:** MULTI (Multimeter Calibration)  
**Version:** V01

---

## Purpose

Ensure that the multimeter used for electrical diagnostics is accurate and reliable. Proper calibration of measuring instruments is critical to maintain safety standards and ensure valid readings during maintenance and inspection procedures.

## Applicability

- Aircraft Model: A360XWLRGA  
- Electrical diagnostic tasks (e.g., wiring checks, connector verification).
- Recommended after a defined number of usage hours or following abnormal readings.

## Tools & Equipment

- **Reference Standard:** A calibrated voltage/current source approved by OEM.  
- **Multimeter:** The unit to be calibrated.  
- **PPE:** Safety glasses and gloves, if required by local regulations.

## Safety Notes

1. **Power Off During Connections:**  
   Disconnect the aircraft and external test equipment from power before connecting the reference standard to the multimeter.

2. **Follow OEM Specifications:**  
   Use OEM-approved calibration standards and procedures. Deviation may result in inaccurate readings.

3. **Stable Environment:**  
   Perform calibration in a stable, clean environment free from excessive vibration, moisture, or temperature fluctuations.

## Procedure Summary

1. **Pre-Calibration Setup:**
   - Verify that the reference standard is within its calibration date.
   - Inspect the multimeter’s leads, display, and switches for damage.

2. **Initial Checks:**
   - Set the multimeter to the appropriate range for the test (e.g., DC voltage, AC voltage, resistance).
   - Compare the multimeter’s reading with the known reference standard output (e.g., a 5 V DC signal).

3. **Adjustments:**
   - If readings deviate beyond OEM-specified tolerances, adjust the multimeter’s internal calibration settings as per the OEM’s procedure.
   - Repeat measurements until the multimeter readings are within acceptable limits.

4. **Functional Verification:**
   - Test multiple ranges (e.g., low and high voltage, resistance, continuity) to ensure consistent accuracy.
   - Document all settings and readings.

5. **Record Findings:**
   - Update the calibration sticker or record with the date, technician’s ID, and expiration of calibration validity.
   - Note any adjustments made and reference related DMCs or tokens.

## References

- **S1000D Data Module:** Refer to GAA-2400-MP-00-E-0003 for procedures related to electrical maintenance tasks where calibrated instruments are essential.
- **ATA Chapter:** 24 (Electrical Power)
- **Regulatory Compliance:** FAA AD 2024-05-12
- **Related Tokens:**
  - `MT-ELE-WIRING-CHK-V02` (Wiring Inspection)
  - `MT-ELE-CONN-V01` (Connector Inspection)

## Integration with Digital Tools

- **AR/VR Guidance:**
  AR devices can overlay the calibration steps directly over the multimeter’s display and controls, guiding the technician through adjustments.

- **IoT Sensor Data:**
  Calibration reminders may appear in the CMS after a set number of uses or when sensor data indicates potential reading discrepancies.

## Version History

- **V01:**  
  - Initial calibration method introduced to ensure accurate electrical measurements across GAIA AIR maintenance operations.

---

**End of Document**
